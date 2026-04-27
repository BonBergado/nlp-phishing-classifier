# NLP Phishing Email Classifier

End-to-end NLP pipeline for classifying phishing vs. legitimate messages.

## What it does
- Text preprocessing with phishing-aware tokenization
- Hand-crafted domain features (urgency words, URL presence, caps ratio)
- TF-IDF + Logistic Regression with threshold tuning
- ROC-AUC evaluation + confusion matrix + coefficient visualization

## Dataset
SMS Spam Collection (proxy dataset). Swap in email dataset for production use.

## Run it
Open in Google Colab — no local compute required.

## Stack
Python · scikit-learn · pandas · matplotlib · seaborn

## Next Steps
- Fine-tune DistilBERT for better accuracy
- Parse real .eml email files
- FastAPI deployment
- Adversarial robustness testing
