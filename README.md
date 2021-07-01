# SQuAD
NLP Final Project：SQuAD

## Model
- RoBERTa-large
- RoBERTa-large + Post-Pretraing(textbook corpus+SQuAD corpus, spanmask)
- RoBERTa-large + NewsQA Finetune
- RoBERTa-large + Post-Pretraing(textbook corpus+SQuAD corpus, spanmask) + NewsQA Finetune

## Experiment Settings
SQuAD Finetune: max_len=180, lr=1e-6, batch_size=32

NewsQA Finetune: max_len=512, lr=1e-6, batch_size=8

Python SQuAD_baseline_v1.1.py or SQuAD_baseline_v2.0.py

HowToTest.py is used for build results file

## Result
![avatar](/Figures)
