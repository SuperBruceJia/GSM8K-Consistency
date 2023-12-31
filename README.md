# GSM8K-Consistency Benchmark
**GSM8K-Consistency** is a benchmark database for analyzing the consistency of `Arithmetic Reasoning on GSM8K`. 

## 🚀 The dataset is available on 🤗 Hugging Face!
This is a math-problem-related semantics-preserving perturbation benchmark that can be very helpful for evaluating the consistency of arithmetic reasoning capability.

## 💻 Dataset Usage
Run the following command to load the data:
```python
from datasets import load_dataset

dataset = load_dataset("shuyuej/GSM8K-Consistency")
dataset = dataset['train']
print(dataset)
```

Dataset Description:
```python
Dataset({
    features: ['id', 'original_question', 'paraphrased_question', 'answer_detail', 'numerical_answer'],
    num_rows: 85225
})
```
