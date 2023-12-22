# GSM8K-Consistency Benchmark
**GSM8K-Consistency** is a benchmark database for analyzing the consistency of `Arithmetic Reasoning on GSM8K`.

This is a math-problem-related semantics-preserving perturbation benchmark that can be very helpful for evaluating the consistency of arithmetic reasoning capability.

# Dataset Usage
Run the following command to load the data:
```python
from datasets import load_dataset

dataset = load_dataset("shuyuej/GSM8K-Consistency")
dataset = dataset['train']
```
