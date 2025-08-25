# Amazon Sentiment & Pricing Analysis

> An NLP model that analyzes customer sentiment from Amazon reviews to predict optimal product price ranges, directly linking customer feedback to profitability.

---

### The Business Problem

Companies often struggle to set the right price for their products, leading to declining sales and reduced profitability. It's often difficult to know if negative customer feedback is related to product quality or a perception that the price is too high. This project tackles this uncertainty head-on.

### The Technical Solution

This project uses a data-driven approach to connect the voice of the customer directly to pricing strategy. The end-to-end process included:

1.  **Data Collection:** Web scraping of Amazon electronics reviews.
2.  **Sentiment Analysis:** Using NLP (TF-IDF) to score customer sentiment.
3.  **Predictive Modeling:** Building and training classification models (Logistic Regression, Random Forest) to predict the optimal price range for a product based on its review sentiment.

### Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Matplotlib
*   **Environment:** Jupyter Notebook

### Key Results

The final models achieved an accuracy of up to 79% in predicting price ranges. This demonstrates a strong proof-of-concept for using customer sentiment as a direct input for data-driven pricing and marketing strategies.

