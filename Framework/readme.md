# Hugging face
## Pipeline()
**pipeline()**可以很方便地利用预训练模型进行推理
### text-classification
使用pipeline用于具体的任务：
'''
from transformers import pipeline

pipe = pipeline("text-classification")
print(pipe("This book is difficult to learn!"))
'''
'''
output: [{'label': 'NEGATIVE', 'score': 0.9988523721694946}]
'''
##
