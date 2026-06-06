# Text Summarization System

An AI-powered text summarization application that generates concise and meaningful summaries from lengthy text documents using state-of-the-art Transformer models. The project combines abstractive summarization and grammar correction to produce readable, high-quality summaries suitable for reports, articles, research papers, and technical documents.

---

## Features

- Automatic text summarization
- Grammar correction and refinement
- Transformer-based NLP pipeline
- Supports long-form text inputs
- CPU and GPU execution support
- Offline deployment capability
- Easy integration into other applications
- Jupyter Notebook implementation

---

## Project Overview

Large documents often contain redundant information and require significant time to read. This project addresses that challenge by leveraging Transformer-based Natural Language Processing (NLP) models to generate concise summaries while preserving the key information from the original text.

The system first generates an abstractive summary and then performs grammar correction to improve readability and fluency.

---

## Workflow

```text
Input Text
    │
    ▼
Text Preprocessing
    │
    ▼
Summarization Model
    │
    ▼
Generated Summary
    │
    ▼
Grammar Correction
    │
    ▼
Final Refined Summary
```

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Jupyter Notebook
- Natural Language Processing (NLP)

---

## Models

### Summarization Model
- Facebook BART Large CNN

### Grammar Correction Model
- T5 Grammar Correction

These models are widely used for abstractive summarization and text refinement tasks.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/text-summarization-system.git
cd text-summarization-system
```

Install dependencies:

```bash
pip install torch transformers sentencepiece accelerate
```

---

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook and provide the input text.

Example:

```python
text = """
Artificial Intelligence is transforming industries by enabling
machines to perform tasks that typically require human intelligence.
"""

summary = summarize(text)

print(summary)
```

---

## Example

### Input

```text
Artificial Intelligence is transforming industries by enabling
machines to perform tasks that typically require human intelligence.
It has applications in healthcare, finance, education, and automation.
```

### Output

```text
Artificial Intelligence is transforming industries through intelligent
automation and applications across multiple domains.
```

---

## Offline Deployment

The project can be configured for environments without internet access.

1. Download the required models once.
2. Store them locally in a dedicated `models/` directory.
3. Load models using local paths.

## License

This project is intended for educational, research, and learning purposes.
