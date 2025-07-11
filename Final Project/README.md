This project fine-tunes a pre-trained GPT-2 model on the WikiText-2 dataset to build a simple Next-Word Predictor.

# Project Summary
-	Model: “GPT-2” from Hugging Face Transformers
-	Dataset: 'WikiText-2'
-	Training Epochs: 7
-	Final Loss: 0.88
-	Training Time: ~1460 minutes (on A6000)
-	Inference Enabled: yes
> Due to hardware constraints, training was limited to 7 epochs. Full training over 25–30 epochs is expected to improve performance significantly.

# Results
Epoch	Training Loss
 1	       1.8
 2	       1.5
 3	       1.3
 7.       0.88
 10	      ~.9
 20	      ~0.8


## 🔁 Inference Demo
~python code
from transformers import AutoModelForCausalLM, AutoTokenizer

model = AutoModelForCausalLM.from_pretrained("gpt2-wikitext2-final")
tokenizer = AutoTokenizer.from_pretrained("gpt2-wikitext2-final")

input = tokenizer("The quick brown", return_tensors="pt")
output = model.generate(**input, max_length=10)
print(tokenizer.decode(output[0], skip_special_tokens=True))
