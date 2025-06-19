# 📝 Text Summarization using Natural Language Processing (NLP)

This project implements a basic yet effective **Text Summarization** tool using NLP techniques. It allows users to upload `.txt` files and generates concise summaries by extracting the most relevant sentences based on word frequency.

---

## 📌 Features

- 📂 Upload `.txt` file as input
- ✂️ Extractive summarization using frequency-based scoring
- 🧠 Custom word tokenizer (no reliance on `punkt`)
- 🔤 Preprocessing with stopword removal and normalization
- 📄 Prints entire original text and summary neatly wrapped (no scrollbars)
- 🧾 Outputs are formatted for easy reading in notebooks and consoles

---


## ⚙️ Requirements

- Python 3.6+
- Libraries:
  - `nltk`
  - `re`, `collections`, `heapq`, `textwrap`

You can install dependencies with:

```bash
pip install nltk



