# Exploratory Data Analysis (EDA) on Amazon Alexa Reviews

## Introduction
Exploratory Data Analysis (EDA) is a crucial step in understanding and gaining insights from a dataset. In this report, we conduct EDA on the Amazon Alexa reviews dataset to explore its characteristics, understand customer sentiments, and uncover patterns within the reviews.

## Dataset Overview
The dataset comprises reviews of the Amazon Alexa product, containing information about ratings, variations, feedback (sentiment), and verified reviews. It is stored as a tab-separated values (TSV) file, containing approximately 3000 entries.

## Data Exploration

### Basic Statistics and Missing Values
We initiate the analysis by examining basic statistics and the structure of the dataset. The dataset consists of [YYYY] columns and [ZZZZ] rows. Notably, no missing values are present across the columns, ensuring data integrity.

### Distribution of Ratings
We visualize the distribution of ratings assigned by customers to the Amazon Alexa product. Key insights include:

- A significant proportion of reviews receive high ratings (4 and 5), signifying overall positive sentiment towards the product.
- A smaller portion of reviews are associated with lower ratings (1 and 2), indicating some level of dissatisfaction.

### Distribution of Variations
An investigation into the distribution of product variations reveals the following:

- The dataset encompasses reviews for various versions of the Amazon Alexa product.
- Certain variations attract considerably more reviews than others, suggesting potential popularity differences or targeted marketing strategies.

### Distribution of Sentiment (Feedback)
We delve into the distribution of feedback (sentiment) provided by customers. Noteworthy observations are:

- A majority of reviews express positive sentiment (feedback=1), reflecting a generally favorable reception of the product.
- A minority of reviews convey negative sentiment (feedback=0), spotlighting aspects that might require attention or improvement.

### Review Characteristics

#### Review Length
We quantify the length of each review in terms of characters. The average review length is approximately [NNN] characters. The distribution of review lengths exhibits a positive skew, with the majority of reviews falling within the [MMM] to [PPP] character range.

#### Text Preprocessing
To prepare the textual data for analysis, we undertake the following preprocessing steps:
- Conversion of text to lowercase.
- Removal of URLs and non-alphanumeric characters.
- Tokenization of text into words.
- Elimination of stopwords.
- Application of stemming using the Porter stemming algorithm.

#### Word Cloud Analysis
We construct word clouds for both positive and negative reviews to visualize frequently occurring words in each sentiment category. Notable findings include:

- Positive Reviews Word Cloud: Prominent positive words encompass "great," "love," "excellent," and "easy."
- Negative Reviews Word Cloud: Prominent negative words comprise "problem," "disappoint," "return," and "issue."

