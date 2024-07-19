# Text Analysis Tool

This repository contains a Python-based text analysis tool that performs sentiment analysis, key phrase extraction, and quality assessment on text responses.

## Features

- **Sentiment Analysis**: Determines if a given text is positive, negative, or neutral.
- **Key Phrase Extraction**: Identifies and extracts important noun phrases from the text.
- **Quality Assessment**: Assigns a quality score based on sentiment and the number of key phrases.

## Dependencies

- TextBlob: For sentiment analysis
- spaCy: For natural language processing and key phrase extraction
- Python 3.x

## Installation

1. Clone this repository:
   git clone [https://github.com/yourusername/text-analysis-tool.git](https://github.com/pillaiash/Sentiment-Analysis.git)
   cd text-analysis-tool

2.Install the required packages:
   pip install textblob spacy

3.Download the spaCy English model:
   python -m spacy download en_core_web_sm


# How It Works

-analyze_sentiment(): Uses TextBlob to determine the sentiment of the text.
-extract_key_phrases(): Utilizes spaCy to identify and extract noun chunks as key phrases.
-assess_quality(): Calculates a quality score based on the number of key phrases and the sentiment.
-The main() function: Reads responses from a file, processes each one, and prints the results.


