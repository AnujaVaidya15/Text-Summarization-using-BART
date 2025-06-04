# Text-Summarization-using-BART
# Text Summarization using BART (`facebook/bart-large-cnn`)

This project demonstrates how to generate **abstractive summaries** for long-form news articles using the pretrained **BART model** from Facebook AI: `facebook/bart-large-cnn`. The model is fine-tuned on the **CNN/DailyMail** dataset and produces high-quality, human-like summaries.

---

##  Overview

-  **Model**: `facebook/bart-large-cnn`
-  **Dataset**: CNN/DailyMail (preprocessed and used during model pretraining)
-  **Type**: Abstractive Summarization
-  **Libraries**: Hugging Face Transformers, PyTorch

---

##  Model: BART

BART (Bidirectional and Auto-Regressive Transformers) is a sequence-to-sequence model that combines the encoder structure of BERT and the decoder of GPT. The `bart-large-cnn` variant is specifically fine-tuned for summarization tasks on the CNN/DailyMail dataset.

🔗 [Model Link on Hugging Face](https://huggingface.co/facebook/bart-large-cnn)

---

##  Dataset: CNN/DailyMail

The CNN/DailyMail dataset includes over 300,000 news articles along with corresponding human-written highlights. It is widely used for summarization benchmarks and was used to fine-tune `facebook/bart-large-cnn`.

🔗 [Dataset on Hugging Face](https://huggingface.co/datasets/cnn_dailymail)

---

###Clone the repository

```bash
git clone https://github.com/your-username/bart-summarization.git
cd bart-summarization

