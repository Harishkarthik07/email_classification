# email_classification
#  Email Marketing Campaign Analysis & Classification

This project focuses on analyzing an email marketing campaign and building a machine learning model to predict which users are most likely to click on a link inside the email.

##  Problem Statement

An e-commerce company ran an email campaign to promote a new feature. The goal is to:
- Understand the campaign performance.

- Predict which users are more likely to click the email.

- Use this model to improve future campaigns.

---

##  Dataset Description

There are three CSV files used in this project:

1. **email_table.csv

   - `email_id` – Unique ID for each email.

   - `email_text` – Type of text (short or long).

    - `email_version` – Type of version (personalized or generic).


   - `hour`, `weekday` – When the email was sent.

   - `user_country` – Country of the user.

    - `user_past_purchases` – Number of past purchases.

3. email_opened_table.csv
   - `email_id` – Emails that were opened.

4. link_clicked_table.csv
   - `email_id` – Emails where the link was clicked.

---

##  What This Project Does

 Calculates open and click-through rates.  

 Builds a model to predict which users will click.  

 Evaluates model performance.  

 Finds patterns in user behavior.

---

##  Tech Stack

- Python

- Pandas

- Scikit-learn

- Jupyter Notebook (for analysis)

---

## Model Used

- **Random Forest Classifier**

  - Trained to predict if a user will click the link in the email.

  - Categorical features like `email_text`, `weekday`, `country` were one-hot encoded.

  - Model performance was evaluated using accuracy and classification report.

---

##  Key Results

- Calculated **Open Rate** and **Click Rate**.

- Built a classification model that predicts user behavior.

- Identified patterns such as:

  - Personalized emails and shorter content performed better.

  - Users with past purchases had a higher click rate.

---
