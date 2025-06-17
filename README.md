# CNN/DailyMail Text Summarizer

This project provides an end-to-end implementation of abstractive text summarization using the [CNN/DailyMail dataset](https://huggingface.co/datasets/cnn_dailymail) and Hugging Face Transformers.

## 📌 Features

- Uses `facebook/bart-large-cnn` for generating summaries.
- Loads dataset in **streaming mode** for efficient memory usage.
- Fully compatible with **Google Colab**.
- Installs and configures all dependencies automatically.
- Handles long documents by truncating input to fit model limits.

## 📁 Dataset

- **Name:** CNN/DailyMail
- **Version:** 3.0.0
- **Source:** [Hugging Face Datasets](https://huggingface.co/datasets/cnn_dailymail)

## 🚀 Usage (on Google Colab)

1. Open the notebook: [`text_summarization_colab.ipynb`](./text_summarization_colab.ipynb)
2. Run the first cell to install dependencies.
3. Restart the runtime when prompted.
4. Execute all remaining cells.

## 🔧 Requirements

- Python 3.7+
- HuggingFace Transformers
- Datasets
- SpaCy

All dependencies are installed automatically in the notebook.

## 📈 Sample Output

```

ARTICLE SAMPLE:
\[First 500 characters of the article]

REFERENCE SUMMARY:
\[Ground truth summary]

GENERATED SUMMARY:
\[BART-generated summary]

```

## 📚 Future Enhancements

- Add evaluation using ROUGE scores.
- Enable summarization of multiple samples.
- Integrate extractive summarization (e.g. spaCy, TextRank).
- Add model fine-tuning capability.

## 🧠 Model Used

- **Name:** `facebook/bart-large-cnn`
- **Type:** Transformer-based encoder-decoder
- **Use Case:** Abstractive summarization

## 📜 License

This project is for educational use. Refer to individual library licenses for terms of use.
```

