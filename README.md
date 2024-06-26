# Project Description: Amazon Product Review Analysis
This Python script aims to analyze Amazon product reviews by extracting reviews from a specific product's URL and performing sentiment analysis on those reviews.

## Functions Overview:

1. **get_url_review_page(UrlProduct, i)**:
   - Constructs the URL for a specific page of product reviews.

2. **get_rating(UrlProduct)**:
   - Retrieves the overall rating of the product.

3. **get_product_name(UrlProduct)**:
   - Extracts the name of the product from its URL.

4. **get_global_rating(UrlProduct)**:
   - Fetches the global rating of the product.

5. **get_image_url(UrlProduct)**:
   - Obtains the URL of the product's image.

6. **extract_reviews(UrlProduct)**:
   - Extracts reviews from a specific page of product reviews.

7. **extract_all_reviews(UrlProduct)**:
   - Extracts all reviews from multiple pages of product reviews.

8. **clean_comment(comment)**:
   - Cleans the text of a comment by converting it to lowercase, removing non-alphabetic characters, digits, and stop words.

9. **sentiment_analysis_textblob(text)**:
   - Performs sentiment analysis using TextBlob and returns the sentiment label (Positive, Negative, or Neutral).

10. **comment_dataFrame(UrlProduct)**:
    - Constructs a DataFrame containing cleaned comments and their corresponding sentiments.

11. **sentiment_by_comment(df)**:
    - Calculates the count of comments by sentiment.

## Installation Requirements:

- Python 3.x
- Packages listed in the `requirements.txt` file. Install them using `pip install -r requirements.txt`.
- [en-core-web-sm @ https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.7.1/en_core_web_sm-3.7.1-py3-none-any.whl#sha256=86cc141f63942d4b2c5fcee06630fd6f904788d2f0ab005cce45aadb8fb73889](https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.7.1/en_core_web_sm-3.7.1-py3-none-any.whl#sha256=86cc141f63942d4b2c5fcee06630fd6f904788d2f0ab005cce45aadb8fb73889)
- beautifulsoup4
- selenium
- pandas
- nltk
- spacy
- textblob
- streamlit
- plotly
- requests
- wordcloud
- webdriver_manager

## Team Members:

- El Ouankrimi Ali
- Olamine Zakaria
- Oubella Abdallah
#   A m a P r o d u c t R e v i e w s 
 
 