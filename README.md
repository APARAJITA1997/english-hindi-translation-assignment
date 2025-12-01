# English–Hindi Translation Assignment

This repository contains the complete work for **Assignment 1** and **Assignment 2**.

---

## 📝 Assignment 1 – Dataset Processing

Steps performed:
- Loaded raw dataset from `eng.txt` and `hin.txt`
- Paired English–Hindi sentences
- Computed word counts for both languages
- Applied required filters:
  - Both sentences must contain **5 to 50 words**
  - Word count difference between English & Hindi must be **-10 to +10**
- Saved outputs:
  - `english_hindi_cleaned.csv`
  - `english_hindi_cleaned.xlsx`

---

## 📝 Assignment 2 – Translation with Open-Source LLM

### Steps:
- Selected 100 English sentences from cleaned dataset
- Used **Helsinki-NLP/opus-mt-en-hi** (open-source) for translation
- Generated Hindi translations
- Calculated evaluation metrics:
  - **BLEU**
  - **CHRF**
  - **TER**
- Saved outputs:
  - `assessment2_translations_opusmt.xlsx`
  - `assessment2_metrics_opusmt.txt`

---

## 📌 Files in This Repository

| File | Description |
|------|-------------|
| `Assignment 1 and 2 code.ipynb` | Combined code notebook for both assignments |
| `eng.txt` | Raw English dataset |
| `hin.txt` | Raw Hindi dataset |
| `english_hindi_cleaned.csv` | Cleaned data (Assignment 1) |
| `english_hindi_cleaned.xlsx` | Cleaned data in Excel format |
| `assessment2_translations_opusmt.xlsx` | Model-generated translations |
| `assessment2_metrics_opusmt.txt` | BLEU/CHRF/TER scores |
| `assessment2_submission.xlsx` | Submission format output |

---

## ▶️ How to Run the Notebook

1. Open notebook in Google Colab  
2. Run all cells sequentially  
3. Install required libraries:


---

## ⚠️ Note
- Only open-source models were used.
- No paid API or closed-source model was used.
- No secrets or access tokens are stored in the repository.

---

