# Amharic-Corpus-N-Gram-Analysis

This project involves Natural Language Processing (NLP) techniques applied to an Amharic text corpus. The primary focus is on exploring and analyzing the corpus using **n-grams** (unigrams, bigrams, trigrams, and higher-order n-grams) to understand the linguistic patterns and frequency distributions.  

## Features  
- **Conditional Probability Calculation:**  
  Compute the conditional probability of a word given the previous word using bigrams, providing insights into word dependencies in the Amharic language.

- **Stopword Removal and Frequency Recalculation:**  
  Remove common Amharic stopwords from the corpus and recompute n-gram frequencies to find the most significant and meaningful n-grams for `n = 1, 2, 3, 4`.

- **Top N-Grams Analysis:**  
  Extract and display the top 10 most frequent n-grams for various values of `n`, both with and without stopwords.

## Methodology  
1. **Corpus Preprocessing:**  
   The raw text is tokenized into chunks, cleaned, and preprocessed to ensure high-quality data for n-gram analysis.

2. **Stopword Filtering:**  
   A curated list of Amharic stopwords is utilized to remove commonly occurring but non-informative words from the text.

3. **N-Gram Frequency Analysis:**  
   Calculate n-gram frequencies for unigrams, bigrams, trigrams, and four-grams, providing a detailed view of word patterns in the Amharic corpus.

4. **Conditional Probability Computation:**  
   Use bigram and unigram frequencies to calculate the conditional probabilities of words given their predecessors.

## Technology Stack  
- Python
- Word Cloud
- Amharic-specific stopword list for linguistic analysis  

## Results  
- Identification of high-frequency and contextually significant n-grams in the Amharic corpus.  
- Enhanced understanding of word relationships through conditional probability metrics.  

## Potential Applications  
- Language modeling for Amharic.  
- Improving Amharic text processing for NLP tasks like sentiment analysis, machine translation, and text generation.  

---
