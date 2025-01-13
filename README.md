# Sentiment Analysis and Readability Metrics

This project is a sentiment analysis and text readability evaluation tool. It processes text files to compute sentiment scores, readability indices, and other linguistic metrics. The tool is designed to provide insights into the sentiment and complexity of written content.

## Features

The script performs the following operations:
1. **Text Cleaning**: Prepares raw text by removing special characters, converting to lowercase, and eliminating extra spaces.
2. **Sentiment Analysis**:
   - **Positive Score**: Counts occurrences of positive words.
   - **Negative Score**: Counts occurrences of negative words.
3. **Readability Metrics**:
   - Average Sentence Length
   - Percentage of Complex Words
   - Fog Index (Readability)
   - Complex Word Count
4. **Word Counts**:
   - Total Word Count
   - Personal Pronoun Count

## Data Requirements

1. **Input Text Files**: The script analyzes the following text files:
   - `123.0.txt`
   - `12129.8.txt`
   - `11206.2.txt`
   - `10744.4.txt`

2. **Word Dictionaries**:
   - `positive-words.txt`: A list of positive sentiment words.
   - `negative-words.txt`: A list of negative sentiment words.

Ensure these files are present in the same directory as the script.

## Installation and Usage

### Prerequisites
- Python 3.6 or higher.

### Steps to Run the Script
1. Clone the repository:
   ```bash
   git clone https://github.com/Pranavtiwari30/TEST
