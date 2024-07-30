# Resources for Natural Language Processing of Ottoman Turkish

A repository for resources to be used in NLP of Ottoman Turkish - will be updated gradually.

---
### A colab notebook for fine-tuning BERT-based models for Ottoman Turkish named entity recognition:
https://colab.research.google.com/drive/1MBTRoMAnZrY9p_-J9rZPd0b6rHQFKCBJ?usp=sharing

#### Necessary documents:
- A NER dataset for fine-tuning.
- NER/run_ner_old.py
- NER/utils.py
- NER/tasks.py

*- You can use the BERTurk model already fine-tuned with a modern Turkish dataset: https://huggingface.co/alierenak/berturk_cased_ner*

*- If you first want to pretrain a language model with your own data, this is a good tutorial that explains the process step by step: https://colab.research.google.com/github/huggingface/notebooks/blob/master/examples/language_modeling.ipynb#scrollTo=1Uk8NROQ3l-k*
