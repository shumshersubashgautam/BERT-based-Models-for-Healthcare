# BERT-based-Models-for-Healthcare
About Dataset
This dataset includes two types of models: transformers tailored for medical applications and LayoutLM models for structured documents. 
BioBert

BioBERT (Bidirectional Encoder Representations from Transformers for Biomedical Text Mining) is a domain-specific language representation model pre-trained on large-scale biomedical corpora. With almost the same architecture across tasks, BioBERT largely outperforms BERT and previous state-of-the-art models in a variety of biomedical text mining tasks when pre-trained on biomedical corpora. While BERT obtains performance comparable to that of previous state-of-the-art models, BioBERT significantly outperforms them on the following three representative biomedical text mining tasks: biomedical named entity recognition (0.62% F1 score improvement), biomedical relation extraction (2.80% F1 score improvement) and biomedical question answering (12.24% MRR improvement)

Biomedical Named Entity Recognition
An English Named Entity Recognition (NER) model, trained on Maccrobat to recognize the bio-medical entities (107 entities) from a given text corpus (case reports etc.).

LayoutLM
LayoutLM is a simple but effective multi-modal pre-training method of text, layout and image for visually-rich document understanding and information extraction tasks, such as form understanding and receipt understanding. LayoutLM archives the SOTA results on multiple datasets.

Clinical-Longformer
A clinical knowledge enriched version of Longformer that was further pre-trained using MIMIC-III clinical notes. It allows up to 4,096 tokens as the model input. Clinical-Longformer consistently out-performs ClinicalBERT across 10 baseline dataset for at least 2 percent. Those downstream experiments broadly cover named entity recognition (NER), question answering (QA), natural language inference (NLI) and text classification tasks.

Clinical-BigBird
A clinical knowledge enriched version of BigBird that was further pre-trained using MIMIC-III clinical notes. It allows up to 4,096 tokens as the model input. Clinical-BigBird consistently out-performs ClinicalBERT across 10 baseline dataset. Those downstream experiments broadly cover named entity recognition (NER), question answering (QA), natural language inference (NLI) and text classification tasks.

CORe (Clinical Outcome Representations)
This model is introduced in the paper Clinical Outcome Predictions from Admission Notes using Self-Supervised Knowledge Integration. It is based on BioBERT and further pre-trained on clinical notes, disease descriptions and medical articles with a specialised Clinical Outcome Pre-Training objective.This model checkpoint is fine-tuned on the task of diagnosis prediction. The model expects patient admission notes as input and outputs multi-label ICD9-code predictions.
