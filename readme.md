# Text Summarizer

## Purpose

This project provides a text summarization tool that condenses long documents into shorter, meaningful summaries while preserving key information.

## Usage

```bash
# Install dependencies
pip install -r requirements.txt

# Run the summarizer
python summarizer.py --input input.txt --output summary.txt
```

### Options

- `--input`: Path to the input text file
- `--output`: Path to save the summary (optional)
- `--length`: Desired summary length (optional)

## Example

```python
from summarizer import TextSummarizer

summarizer = TextSummarizer()
summary = summarizer.summarize("Your long text here...")
print(summary)
```