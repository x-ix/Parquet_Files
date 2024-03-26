---
license: mit
task_categories:
- text-classification
- text-generation
language:
- en
tags:
- code
pretty_name: '*'
size_categories:
- 1M<n<10M
---
# Parquet_Files

Hugging Face Link: https://huggingface.co/datasets/iix/Parquet_FIles

# Cross Language (CL) Datasets

Four datasets of language pair translations originating from CORDIS Project News (https://elrc-share.eu/)

```
Structured as follows:

| Field           | Description                                                             |
| --------------- | ----------------------------------------------------------------------- |
| de/es/fr/it     | Non-English transcripts of sentences                                    |
| en              | English translations of sentences                                       |

120k rows (approx. per parquet file)
```

# Characters.parquet

One large dataset of synthetic characters, information regarding them and their outputs. Created by combining other synthetic character datasets which can be found at: https://shorturl.at/gjIJ5, https://shorturl.at/DFQT6 & https://shorturl.at/tHX68.

```
Structured as follows:

| Field          | Description                                                     |
| -------------- | --------------------------------------------------------------- |
| name           | Character name                                                  |
| categories     | Categories or genres associated with the character (array)      |
| personalities  | Personality traits and characteristics of the character (array) |
| description    | Description of the character                                    |
| conversation   | Conversational interactions involving the character (array)     |

17.6k rows 
```

# Flores7Lang.parquet

Seven languages merged from the Flores-200 Dataset (https://github.com/facebookresearch/flores/blob/main/flores200/README.md)

```
Structured as follows:

| Field           | Description                                           |
| --------------- | ----------------------------------------------------- |
| deu             | Sentence translated into German                       |
| eng             | Sentence translated into English                      |
| epo             | Sentence translated into Esperanto                    |
| fra             | Sentence translated into French                       |
| ita             | Sentence translated into Italian                      |
| spa             | Sentence translated into Spanish                      |
| tur             | Sentence translated into Turkish                      |

2.1k rows
```

# Fraud_detection.parquet

A synthetic financial dataset intended for Fraud detection tasks (https://www.kaggle.com/datasets/ealaxi/paysim1).

```
Structured as follows: 

| Field           | Description                                                   |
| --------------- | ------------------------------------------------------------- |
| Step            | Maps a unit of time in the real world (1 step = 1 hour)       |
| Type            | CASH-IN, CASH-OUT, DEBIT, PAYMENT, or TRANSFER                |
| Amount          | Amount of the transaction in local currency                   |
| nameOrig        | Customer who initiated the transaction                        |
| oldbalanceOrg   | Initial balance before the transaction                        |
| newbalanceOrig  | Customer's balance after the transaction                      |
| nameDest        | Recipient ID of the transaction                               |
| oldbalanceDest  | Initial recipient balance before the transaction              |
| newbalanceDest  | Recipient's balance after the transaction                     |
| isFraud         | Identifies a fraudulent transaction (1) or non-fraudulent (0) |

2.27m rows
```