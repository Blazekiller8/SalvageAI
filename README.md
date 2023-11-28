# SalvageAI

## Introduction

Introducing SalvageAI, an AI platform for waste management.  SalvageAI deploys Yolo-NAS, for garbage detection.  The platform integrates GroundingDINO for active learning. Moreover, the integration of ColossalAI to provide recycling recommendations to guide them in recycling.

## Installation

```bash
pip install -r requirements.txt
```

## Datasets Used

- [TrashNet](https://github.com/garythung/trashnet)
- [TACO](https://github.com/pedropro/TACO/)

## To download Dataset

- For the TACO dataset use:

```bash
python3 datasets/TACO/download.py
```
