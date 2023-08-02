# Project Name: Financial News Analyzer for Stocks

## Table of Contents
1. [Introduction](#introduction)
2. [What is Financial News Analyzer for Stocks?](#what-is-financial-news-analyzer-for-stocks)
3. [Badges](#badges)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)
10. [Documentation](#documentation)

## Introduction
The Financial News Analyzer for Stocks is a Python script that helps investors and traders analyze financial news related to a specific stock. It fetches recent news articles from Google News, performs sentiment analysis on each article, and visualizes the sentiment distribution.

## What is Financial News Analyzer for Stocks?
The Financial News Analyzer for Stocks is a tool that provides insights into the sentiment of recent news articles about a specific stock. It utilizes the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from the Natural Language Toolkit (nltk) library to determine the sentiment of each news article.

## Badges
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Installation
To use the Financial News Analyzer for Stocks, you will need Python and the required libraries installed on your system. Follow these steps to get started:

1. Install Python: Download and install Python from the official website: https://www.python.org/downloads/

2. Install necessary libraries: Open a command prompt or terminal and run the following commands:
   ```
   pip install pandas matplotlib nltk newspaper3k GoogleNews
   ```
   The following commands download and install the required libraries: pandas, matplotlib, nltk, newspaper3k, and GoogleNews.

3. Download the 'punkt' tokenizer from the nltk library:
   ```
   import nltk
   nltk.download('punkt')
   ```
   The 'punkt' tokenizer is necessary for text tokenization during sentiment analysis.

## Usage
1. Import the required libraries and the `analyze_stock_trends` function into your Python script.

2. Run the script and provide the name of the company or the stock ticker when prompted.

3. The script will fetch recent news articles related to the specified stock from Google News.

4. The articles are analyzed using sentiment analysis, and the sentiment distribution is displayed as a pie chart.

## Configuration
The script uses the 'Mozilla/5.0' user agent to access websites. No additional configuration is required.

## Contributing
If you find any issues or have suggestions for improvement, please feel free to submit a pull request or open an issue on the GitHub repository.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to Harsh Gupta for creating this project.

## Documentation
For more details on the code implementation and function usage, refer to the code comments and documentation in the source files.
