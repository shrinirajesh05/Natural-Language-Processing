# Retrieval-Augmented Generation (RAG) System for Sustainable Technologies	

This comprehensive project explores the analysis of the Cleantech Media Dataset using advanced Natural Language Processing (NLP) and Artificial Intelligence (AI) techniques. The study focuses on developing a Retrieval-Augmented Generation (RAG) system to extract insights from a large corpus of cleantech articles.

Project Overview

The project utilizes a dataset of 20,122 articles on clean technology innovations, spanning from January 2022 to October 2024. The primary objectives include implementing sophisticated NLP techniques, developing a RAG system, and evaluating its performance using various metrics.

Key Objectives

Implement advanced NLP techniques for text processing

Develop and optimize a RAG system for the cleantech domain

Compare multiple text splitting and embedding techniques

Evaluate system performance using various metrics

Dataset Characteristics

The Cleantech Media Dataset contains:

20,122 articles from diverse platforms

Detailed metadata including publication dates and source information

Content organized as collections of paragraphs

Methodology

Data Preprocessing and Analysis

Handling Missing Data

Removed author column due to lack of values

Addressed anomalies in publication dates

Exploratory Data Analysis

Analyzed domain distribution, revealing skewness towards top sources

Identified and handled duplicated titles and content

Performed language detection and filtered for English articles

Text Processing

Tokenization

Used spaCy English model for tokenization

Filtered non-alphabetic tokens and converted to lowercase

Removed stopwords for meaningful analysis

Advanced Techniques

Retrieval-Augmented Generation (RAG)

Implemented RAG to combine information retrieval with text generation

Experimented with various embedding models and prompt templates

Evaluation Framework

Utilized a complementary evaluation dataset of 23 high-quality instances

Applied multiple evaluation metrics including RAGAS, Rouge, Perplexity, and BERTScore

Results and Insights

Data Distribution

Identified skewed distribution of articles across domains

Discovered anomalies in daily article counts for specific dates

Content Analysis

Most common words include "energy," "solar," and "power," confirming dataset relevance to cleantech

System Performance

Developed a sophisticated RAG system tailored to the cleantech domain

Evaluated system performance using both quantitative metrics and qualitative analysis

Conclusion

This project demonstrates the application of advanced NLP and AI techniques to analyze a large cleantech dataset. By developing a RAG system and employing various evaluation methods, the study contributes to more efficient analysis of cleantech information, potentially accelerating innovation in sustainable technologies
