# Airbnb Victoria Customer Experience Analytics

Business Analytics | Natural Language Processing | Sentiment Analysis | Topic Modelling

## Project Overview

This project analyses Airbnb guest reviews across Victoria, Australia to understand customer satisfaction and identify opportunities for improving host performance. Using Exploratory Data Analysis (EDA), VADER Sentiment Analysis, and Latent Dirichlet Allocation (LDA), the project transforms thousands of customer reviews into actionable business insights.

The analysis focuses on three key business questions:

- Which neighbourhoods have the highest guest satisfaction?
- What factors contribute to negative guest experiences?
- How do guest expectations differ between accommodation types?

---

## Business Objectives

- Analyse Airbnb market activity across Victoria.
- Measure guest satisfaction using sentiment analysis.
- Identify the primary causes of negative customer experiences.
- Discover common discussion topics from guest reviews using LDA.
- Compare guest expectations between Entire Home/Apt and Private Room listings.
- Develop practical recommendations for Airbnb hosts.

---

## Analytical Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis
3. Sentiment Analysis using VADER
4. Negative Review Analysis
5. Topic Modelling using LDA
6. Business Recommendations

---

# Question 1 – Market Performance

The first analysis examines Airbnb listing distribution and guest satisfaction across the ten most active neighbourhoods in Victoria.

![Figure 1](Figure%201%20%E2%80%93%20Number%20of%20Listings%20in%20top%2010%20neighbourhoods.png)

*Figure 1. Number of Listings in Top 10 Neighbourhoods.*

![Figure 2](Figure%202%20-%20Sentiment%20Score%20Distribution%20by%20Top%2010%20Neighbourhoods.png)

*Figure 2. Sentiment Score Distribution by Top 10 Neighbourhoods.*

![Figure 3](Figure%203%20%E2%80%93%20Average%20Guest%20Satisfaction%20Across%20Top%2010%20Neighbourhoods.png)

*Figure 3. Average Guest Satisfaction Across Top 10 Neighbourhoods.*

### Key Findings

- Melbourne contains the largest concentration of Airbnb listings.
- Yarra Ranges records the highest average guest satisfaction.
- Higher listing volume does not necessarily correspond to higher customer satisfaction.

---

# Question 2 – Understanding Customer Dissatisfaction

Negative reviews were analysed using sentence-level sentiment analysis to identify the aspects most strongly associated with poor guest experiences.

![Figure 4](Figure%204%20%E2%80%93%20Comparing%20the%20count%20of%20Positive%20with%20Negative%20Reviews.png)

*Figure 4. Positive vs Negative Reviews.*

![Figure 5](Figure%205%20%E2%80%93%20Average%20Sentiment%20by%20Negative%20Reviews.png)

*Figure 5. Average Sentiment by Aspect.*

![Figure 6](Figure%206%20%E2%80%93%20Heatmap%20of%20Listing%20Features%20vs%20Sentiment.png)

*Figure 6. Correlation Heatmap.*

### Key Findings

- Bathroom cleanliness is the strongest source of dissatisfaction.
- Host responsiveness is another major contributor to negative experiences.
- Structural listing attributes show only weak relationships with guest satisfaction, suggesting that service quality has a greater impact than listing characteristics.

---

# Question 3 – Topic Modelling

Latent Dirichlet Allocation (LDA) was applied to identify recurring themes discussed in Airbnb reviews.

![Figure 7](Figure%207%20%E2%80%93%20Word%20clouds%20of%20Topic%20Popularity.png)

*Figure 7. Word Clouds of Topic Popularity.*

![Figure 8](Figure%208%20-%20Topic%20Popularity.png)

*Figure 8. Topic Popularity.*

![Figure 9](Figure%209%20%E2%80%93%20Topic%20Distributions%20by%20Room%20Type.png)

*Figure 9. Topic Distributions by Room Type.*

### Key Findings

- Accessibility, room quality, and helpful hosts are the most frequently discussed topics.
- Guests staying in Private Rooms place greater emphasis on host interaction and hospitality.
- Guests booking Entire Home/Apt listings prioritise privacy, location, and overall accommodation quality.

---

# Business Recommendations

Based on the analysis, several recommendations were developed for Airbnb hosts:

- Improve bathroom hygiene and property maintenance.
- Enhance host communication and response times.
- Tailor host training according to accommodation type.
- Highlight neighbourhood accessibility and nearby attractions in listing descriptions.
- Encourage guests to leave post-stay reviews to improve platform credibility.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- NLTK
- VADER Sentiment Analysis
- Latent Dirichlet Allocation (LDA)
- WordCloud
- Scikit-learn

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Natural Language Processing
- Sentiment Analysis
- Topic Modelling
- Data Visualisation
- Business Analytics
- Data Storytelling
- Business Recommendation Development

---

## Author

**Huong Linh Vu**

Bachelor of Business Analytics

Deakin University
