# Airbnb Victoria Customer Experience Analytics

Business Analytics | Natural Language Processing | Sentiment Analysis | Topic Modelling | Python

This project analyses Airbnb guest reviews across Victoria, Australia to identify the factors influencing customer satisfaction and provide actionable recommendations for Airbnb hosts.

---

## Project Overview

Airbnb hosts receive thousands of customer reviews, making it difficult to identify recurring issues and understand what guests value most.

This project applies Natural Language Processing (NLP), Sentiment Analysis, Topic Modelling, and Exploratory Data Analysis (EDA) to convert unstructured review data into business insights.

The analysis addresses three business questions:

* Which neighbourhoods achieve the highest guest satisfaction?
* What causes negative guest experiences?
* How do guest expectations differ across accommodation types?

---

## Business Objectives

* Analyse Airbnb listing distribution across Victoria.
* Measure customer satisfaction using review sentiment.
* Identify the primary causes of negative reviews.
* Discover hidden discussion topics using LDA Topic Modelling.
* Compare customer expectations across room types.
* Develop business recommendations for Airbnb hosts.

---

## Dataset

| Dataset        | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| `listings.csv` | Airbnb listing information including neighbourhood, room type and property attributes |
| `comments.csv` | Guest review data used for sentiment and topic analysis                               |

---

## Technologies

* Python
* Pandas
* NumPy
* NLTK
* VADER Sentiment Analysis
* Scikit-learn
* Latent Dirichlet Allocation (LDA)
* Matplotlib
* WordCloud

---

## Project Workflow

```text
Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Sentiment Analysis
    │
    ▼
Negative Review Analysis
    │
    ▼
Topic Modelling
    │
    ▼
Business Insights
```

---

## Key Findings

### Market Performance

* Melbourne has the largest number of Airbnb listings.
* Yarra Ranges records the highest average guest satisfaction.
* High listing volume does not necessarily lead to higher customer satisfaction.

### Customer Dissatisfaction

The most common sources of negative reviews are:

* Bathroom cleanliness
* Host responsiveness
* Property cleanliness

Structural listing characteristics such as price and minimum stay show only weak relationships with customer satisfaction.

### Topic Modelling

Topic modelling identified ten major themes discussed in customer reviews.

The most frequently discussed topics include:

* Accessibility and city exploration
* Room quality
* Helpful hosts
* Overall stay experience

### Room Type Comparison

**Private Room**

* Greater emphasis on host interaction
* Higher expectations for hospitality
* Strong focus on room quality

**Entire Home**

* Greater emphasis on privacy
* Preference for convenient locations
* Higher expectations for overall accommodation quality

---

## Business Recommendations

* Improve bathroom hygiene standards.
* Enhance host communication and response time.
* Provide accommodation-specific host training.
* Highlight neighbourhood accessibility in listing descriptions.
* Encourage guests to leave reviews after their stay.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Natural Language Processing
* Sentiment Analysis
* Topic Modelling
* Data Visualisation
* Business Analytics
* Business Recommendation Development

---

## Repository Structure

```text
airbnb-victoria-customer-insights/
│
├── data/
├── notebooks/
├── images/
├── report/
├── README.md
└── requirements.txt
```

---

## Project Preview

Screenshots of the analysis are available in the `images` folder.

---

## Author

Huong Linh Vu

Bachelor of Business Analytics

Deakin University
