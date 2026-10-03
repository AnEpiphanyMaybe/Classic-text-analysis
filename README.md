# Classic Text Sentiment Analysis

## Overview
Analyzed how sentiment changes throughout a classic novel
using NLP and sentiment analysis.

## Process
- Scraped public-domain text from Project Gutenberg
- Cleaned headers, chapter information, and formatting
- Split the novel into chapters and sentences
- Applied VADER sentiment analysis
- Compared sentiment across chapters

## Tools
Python, Pandas, NLTK, Matplotlib, Requests

## Results
the sentiment of Black Beauty fluctuates substantially between chapters rather than following a consistent positive or negative trend. Most of the language is classified as neutral, however the compound sentiment reveals several pronounced emotional shifts, including strongly positive sections early and midway through the novel, a substantial negative shift around Chapters 39–40, and a return to positive sentiment in the final chapters.

<img width="1255" height="854" alt="classics_graph" src="https://github.com/user-attachments/assets/8a759286-bc86-4da8-8248-942ee09bf0f8" />


## Files
- `ClassicsAnalysis.ipynb` — Complete analysis
