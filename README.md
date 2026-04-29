# Arabic Sentiment Analysis Benchmark (Cross-Dialect Evaluation)

This project benchmarks multiple transformer-based Arabic NLP models across different Arabic dialects for sentiment analysis. It evaluates how well models generalize across dialects using accuracy, F1-score, and robustness metrics.

## 🔍 Models Compared
- AraBERT (`aubmindlab/bert-base-arabertv02`)
- MARBERT (`UBC-NLP/MARBERT`)
- CAMeLBERT (`CAMeL-Lab/bert-base-arabic-camelbert-mix`)
---
## 📄 Manuscript

This project is based on our research manuscript:

**Cross-Dialect Robustness of Arabic Pre-trained Language Models for Sentiment Analysis**
🔗 DOI: https://doi.org/10.21203/rs.3.rs-9527228/v1
----
## 📊 Features
- Sentiment classification (Positive / Negative)
- Cross-dialect evaluation
- Performance comparison across models
- Statistical significance testing (t-test)
- Robustness analysis
- Visualization (heatmaps, violin plots, line plots, box plots)
---

- `text`: Arabic sentence
- `label`: sentiment label (0 = Negative, 1 = Positive)
- `dialect`: Arabic dialect category (e.g., Egyptian, Gulf, Levantine, etc.)

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
