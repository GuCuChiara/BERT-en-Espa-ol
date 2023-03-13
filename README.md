# BERT-en-Español

BETO (Spanish BERT) + Spanish SQuAD2.0 + distillation using 'bert-base-multilingual-cased' as teacher

* This model was fine-tuned on the same dataset but using distillation during the process as mentioned above (and one more train epoch).

* The teacher model for the distillation was bert-base-multilingual-cased. It is the same teacher used for distilbert-base-multilingual-cased AKA DistilmBERT (on average is twice as fast as mBERT-base).
