# Introduction

## Name Entity Recognition using BERT for the Organization Name and Occupation

## Dataset

This dataset consists of the labels for the Names, Organization, and Occupation, which can be used for name entity recognition. The dataset is generated using Chat GPT and then annotated manually. It is a CSV file that has labels for the entities mentioned above. The details for the dataset are given below:

- **Name:** NER dataset (YouTube)
- **Mode:** Tabular Data
- **Number of Samples:** 30
- **Type:** Classification
- **Number of Classes:** 3
- **Classes Name:** B-org, B-occu, B-per

## Preprocessing

The preprocessing steps of the proposed project are the following:

- Importing Dataset
- Giving number to sentences as sentence-id in the CSV file
- Train and Test Split

## Model

For the Name Entity Recognition using BERT, the following model was used:

- BERT (Bidirectional Encoder Representations from Transformers)

## Results

The results of the trained model are the following:

| Evaluation Loss | Precision | Recall | F1-Score |
|-----------------|-----------|--------|----------|
| 0.40            | 86%       | 79%    | 82%      |

## Demo

```
[
  [{'Oliver': 'B-PER'}, {'is': 'O'}, {'working': 'O'}, {'in': 'O'}, {'Google': 'B-ORG'},
   {'as': 'O'}, {'Data': 'B-OCCU'}, {'analyst': 'I-OCCU'}]
]
```
<br>

# Author
**Bisma Saleem** <br>
**Research Officer** <br>
***Intelligent Criminology Research Lab (ICRL)*** <br>
*AL-Khawarizmi Institute of Computer Science (KICS)* UET Lahore <br>
