# sentiment-analysis-mlops-techsara
# Sentiment Analysis MLOps Pipeline (Techsara Assessment)

## Overview
This project implements a sentiment analysis pipeline using Twitter and Reddit data.
The focus is on building a reproducible ML workflow with a conditional deployment
gate based on F1-score, simulating real-world MLOps practices.

## What Was Implemented
- TF-IDF + LinearSVC sentiment classifier
- Preprocessing and data validation
- Model evaluation using F1-score
- Conditional promotion of candidate model
- Optional experiments with transfer learning (DistilBERT)

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run the notebook or scripts step by step.
3. The pipeline compares candidate and production models automatically.

## Assumptions & Limitations
- Local files simulate a model registry.
- Large model artifacts are excluded from source control.
- Dataset is sampled for faster experimentation.
"""

with open("README.md", "w") as f:
    f.write(readme_content)

print("README.md created")
