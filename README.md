# SQuAD
NLP Final Project：SQuAD

## Model
- RoBERTa-large + Post-Pretraing(textbook corpus, spanmask)
- RoBERTa-large + Post-Pretraing(textbook corpus, spanmask) + NewsQA Finetune


## Experiment Settings
SQuAD Finetune: max_len=180, lr=1e-6, batch_size=32

NewsQA Finetune: max_len=512, lr=1e-6, batch_size=8

## Result

- RoBERTa-large + Post-Pretraing(textbook corpus, spanmask)

|3-stage| epoch=8 |  |
|------ | ------- | -------|
|  | **EM** | **F1-score** |
| **Dev** | 81.07 | 84.34 |
| **Test** | - | - |

- RoBERTa-large + Post-Pretraing(textbook corpus, spanmask) + NewsQA Finetune (e2)

|4-stage| epoch=5 | newsqa_e2 |
|------ | ------- | -------|
|  | **EM** | **F1-score** |
| **Dev** | 81.64 | 84.67 |
| **Test** | - | - |

- RoBERTa-large + Post-Pretraing(textbook corpus, spanmask) + NewsQA Finetune (e3)


|4-stage| epoch=3 | newsqa_e3 |
|------ | ------- | -------|
|  | **EM** | **F1-score** |
| **Dev** | 81.25 | 84.24 |
| **Test** | - | - |
