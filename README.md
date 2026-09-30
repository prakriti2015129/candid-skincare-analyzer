# Candid - Skincare Sentiment & Ingredient Research Tool

Candid is a local, read-only Python research application designed to analyze community discussions and sentiment around skincare ingredients across specialized subreddits (e.g., `r/SkincareAddiction`, `r/AsianBeauty`, `r/30PlusSkincare`).

## Application Purpose
- **Read-Only Data Collection**: Fetches public text posts and comments using PRAW.
- **Local Ingredient Extraction**: Parses text to extract specific active ingredients (e.g., Niacinamide, Salicylic Acid, Retinol).
- **Sentiment Analysis**: Maps local sentiment scores to ingredient mentions to analyze community feedback.
- **Privacy & Compliance**: Fully read-only, non-commercial, stores no PII, and performs no automated actions (no posting, messaging, or voting).

## Technical Stack
- **Language**: Python 3.10+
- **API Wrapper**: PRAW (Python Reddit API Wrapper)
- **NLP / Sentiment Analysis**: VADER / NLTK
- **Data Handling**: Pandas
