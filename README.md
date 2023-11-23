# Web Data Extraction and Analysis

## Overview
This Python script is designed for web data extraction and subsequent analysis of the extracted content. It utilizes various libraries for web scraping, text processing, and sentiment analysis. The extracted data is then analyzed for sentiment, readability, and other linguistic features.

## Dependencies
Make sure you have the following libraries installed:
- pandas
- requests
- BeautifulSoup
- nltk
- pyphen

You can install them using the following:
```bash
pip install pandas requests beautifulsoup4 nltk pyphen
```

# Usage
1. Ensure you have an Excel file named Input.xlsx with columns 'URL' and 'URL_ID'.
2. The script will crawl the provided URLs, extract the article title and text, and save the content in separate text files.
3. Specify the paths for stopwords, master dictionary, and data extraction in the script.
4. Run the script.

# Sentiment Analysis and Readability
The script performs sentiment analysis and readability calculations on the extracted text. The analysis includes:

- Positive and negative scores
- Polarity and subjectivity scores
- Average sentence length
- Percentage of complex words
- Fog Index
- Average number of words per sentence
- Complex word count
- Word count
- Syllable count per word
- Personal pronouns count
- Average word length

For more details about these analysis, refer to `Text Analysis.docx` file.

# Output
The computed variables are stored in an Excel file named output Data Structure.xlsx. The script also updates an existing output file with new data.

# How to Run
- Update the input directory and file paths for stopwords and the master dictionary.
- Run the script to perform data extraction, sentiment analysis, and readability calculations.
- Find the results in the output Data Structure.xlsx file and the updated output file.

