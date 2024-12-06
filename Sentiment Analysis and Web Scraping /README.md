# Sentiment Analysis and Web Scraping Project (Freelance Work)

This repository contains work on sentiment analysis and web scraping, focusing on extracting and analyzing customer reviews to uncover actionable insights. **Due to client restrictions, only a subset of the work is shared here.**

---

## Project Overview

The project involves:
1. **Web Scraping**: Extracting customer reviews from various sources to build a comprehensive dataset for analysis.
2. **Sentiment Analysis**: Using Natural Language Processing (NLP) techniques to classify customer sentiments as positive, neutral, or negative.

---

## Key Features

### Web Scraping
- **Data Source**: Customer reviews from online platforms.
- **Extracted Fields**:
  - Review ID, user name, review title, and description.
  - Rating, thumbs up, review date, and app version.
  - Developer response and response date.

### Sentiment Analysis
- **Tools**: Python, `nltk`, and `pandas`.
- **Techniques**:
  - Preprocessing: Tokenization, stopword removal, and lemmatization.
  - Sentiment classification using pre-trained models.

---

## Dataset

### Scraped Data
- A sample dataset is provided in `Scrapped Data Sample.xlsx`.
- **Shape**: 1,884 rows × 14 columns.
- **Columns**:
  - `review_id`: Unique identifier for each review.
  - `review_title` and `review_description`: Review text.
  - `rating`: Numerical rating provided by the user.
  - `developer_response`: Developer’s reply to the review (if available).
  - Other fields: `source`, `user_name`, `appVersion`, etc.

### Sentiment Analysis
- Sentiment analysis performed on `review_description` to classify sentiments.

---

## Tools and Technologies

1. **Programming and Libraries**
   - Python: Data analysis and processing.
   - Libraries: `nltk`, `pandas`, `matplotlib`, `seaborn`.

---

## Limitations

Due to client restrictions, the following aspects are not included:
- Complete datasets and proprietary analysis models.
- Detailed sentiment classification outputs for sensitive customer feedback.

---

