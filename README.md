# Capsule Network Effects on Multi-Label Online Toxic Comment Classification

Patricia Jennifer Leoni Sutikno
C14210092
Developed as part of a final project at Universitas Kristen Petra (2025).

## Objective
Evaluate whether adding Capsule Networks improves:
- Accuracy
- Hamming Loss
- Log Loss

on models:
- CNN + LSTM
- BERT + BiGRU

## Dataset
- Source: Jigsaw Toxic Comment Classification (Kaggle)
- Language: English
- Labels: `toxic`, `severe_toxic`, `obscene`, `threat`, `insult`, `identity_hate`

## Models Used
- CNN + LSTM
- CNN + LSTM + Capsule Network
- BERT + BiGRU
- BERT + BiGRU + Capsule Network

## Results Summary

| Model                    | Accuracy | Log Loss | Hamming Loss |
|-------------------------|----------|----------|---------------|
| CNN + LSTM              | 0.9940   | 0.2008   | 0.0179        |
| CNN + LSTM + Capsule    | 0.9940   | 0.1981   | 0.0173        |
| BERT + BiGRU            | 0.9940   | 0.3023   | 0.0243        |
| BERT + BiGRU + Capsule  | 0.9940   | 0.2584   | 0.0233        |

## Deployment
A Discord bot classifies user messages in real-time and assists admins in moderation decisions.

## Models trained
[Google Drive: Trained Models](https://drive.google.com/drive/folders/1Ppw4faB6vvEXdTeiGOzdwFiv4zW58GGQ?usp=sharing)
