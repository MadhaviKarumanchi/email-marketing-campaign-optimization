# email-marketing-campaign-optimization

##  Project Overview
This project involves analyzing and optimizing an email marketing campaign for an e-commerce platform. The goal is to identify patterns in user interactions with marketing emails and build a machine learning model to predict the likelihood of a user clicking on a link within an email — thereby improving future campaign strategies.

## Case Description
The marketing team of an e-commerce site launched an email campaign to inform users about a new feature. The campaign involved sending emails with different content types and personalization levels at various times and days to a random set of users. The success metric was whether the user clicked on the link inside the email.

## Data Description
The dataset consists of 3 tables:

### email_table

email_id

email_text (long/short)

email_version (generic/personalized)

hour

weekday

user_country

user_past_purchases

### email_opened_table

email_id (emails opened)

### link_clicked_table

email_id (emails where the link was clicked)

## Key Questions Answered
What percentage of users opened the email and clicked on the link inside?

Can a machine learning model be built to predict click probability and optimize future campaigns?

Estimate how much the model would improve the click-through rate (CTR) and propose a testing method.

Identify interesting patterns about email campaign performance across different user segments.

## Technologies Used
Python (Pandas, NumPy, Scikit-learn)

Machine Learning (Random Forest Classifier)

Data Visualization (Pandas groupby analysis)

Jupyter Notebook

## Project Results
### Open & Click Rates: Calculated the percentage of users who opened emails and clicked links.

### Model Performance:

Random Forest Classifier used

Evaluation Metrics: Precision, Recall, F1-score, AUC Score

AUC Score achieved: ~0.5778

### Interesting Patterns Identified:

Short emails and personalized content had higher click rates.

Emails sent between 9 AM to 12 PM performed better.

Tuesdays, Wednesdays, and Thursdays had higher click-through rates.

Users from UK and US were more responsive.

Click rates increased with higher past purchases.

## Conclusion
This project demonstrates how machine learning can enhance email marketing campaigns by targeting the right audience with the right message at the right time — ultimately improving click-through rates and engagement.


