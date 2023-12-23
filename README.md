# GSM8K-Consistency Benchmark
**GSM8K-Consistency** is a benchmark database for analyzing the consistency of `Arithmetic Reasoning on GSM8K`. 

## 🚀 The dataset is available on 🤗 [Hugging Face](https://huggingface.co/datasets/shuyuej/GSM8K-Consistency)!
This is a math-problem-related semantics-preserving perturbation benchmark that can be very helpful for evaluating the consistency of arithmetic reasoning capability.

## 💻 Dataset Usage
Run the following command to load the data:
```python
from datasets import load_dataset

dataset = load_dataset("shuyuej/GSM8K-Consistency")
dataset = dataset['train']
print(dataset)
```

Dataset description:
```python
Dataset({
    features: ['type', 'id', 'original_question', 'question', 'answer'],
    num_rows: 80000
})
```
