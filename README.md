# DataStories Blogging Contest

## Announcement 📢

> The description about the contest

## Blog Topics & Ideas

### 1. Large Language Models
Description about the topic

#### Idea 1: Data Quality with Large Language Models
Do data quality check using Large Language Models.
Here's a sample blog which you can refer to: https://kdnuggets.com/2023/04/finetuning-openai-language-models-noisily-labeled-data.html
Sample dataset of customer service from a bank: [https://cleanlab-public.s3.amazonaws.com/Datasets/banking_intentclassification.zip](https://cleanlab-public.s3.amazonaws.com/Datasets/banking_intentclassification.zip)

### 2. Data Quality
Description about the topic

#### Idea 1: Compare using Cleanlab Studio with traditional data quality tools
Describe how Cleanlab auto-discovers data issues, whereas with traditional data quality tools you have to manually define their potential form. Show how Cleanlab is much more useful especially for unstructured image/text data. Comapare against things like Informatica IDQ, AWS Deepqu, OpenRefine, Data Validation platforms like Great Expectations, etc. 

#### Idea 2: Compare using Cleanlab Studio with other Data-Centric AI platforms
Compare what are the differences between these platforms implementation of Data-Centric AI and what specific capabilities they offer.
Websites that can be used for the experiment: Snorkel.ai or Landing.ai

#### Sample 3: Find issues in a document tagging dataset
Use Cleanlab Studio to automatically find issues in a document tagging dataset.
This is a multi-label classification task, where each document can have multiple tags (the tags are non-disjoint).
Write what are the benefits of correcting such issues in the data.
Example dataset to consider: https://paperswithcode.com/dataset/reuters-21578

#### Sample 4: Find issues in a medical imaging dataset
Use Cleanlab Studio to automatically find issues in a public medical imaging dataset.
Write what are the benefits of correcting such issues in the data.

#### Sample 5: Find issues in a content catalog dataset
Write a blogpost similar to this one: https://cleanlab.ai/blog/studio-ecommerce/
Instead of automatically finding issues in a Product catalog, find them (using Cleanlab Studio) in a Content catalog such as a: event calendar, movie database, book database, music database, etc.
Write what are the benefits of correcting such issues in the data.

#### Sample 6: Find issues in a manufacturing Quality-Control dataset
Use Cleanlab Studio to auto-detect issues in an image dataset where images are taken in a manufacturing setting for quality control purposes (eg. cracks in a product, stains on fabric, etc).
Write what are the benefits of correcting such issues in the data.

#### Sample 7: Find issues in agriculture dataset
For example, an imaging dataset of food items being used for quality control purposes (eg. whether the fruit is in good condition or rotten).
Use Cleanlab Studio to auto-detect issues in such a dataset.
Write what are the benefits of correcting such issues in the data.

#### Sample 8: Find issues in a non-English text dataset
For instance a Chinese or Spanish text classification dataset (say for customer service in a Chinese or Spanish firm).
Write what are the benefits of correcting such issues in the data.

#### Sample 9: Optimize synthetic dataset
Use Cleanlab’s synthetic data scores: https://help.cleanlab.ai/tutorials/synthetic_data/
To evaluate synthetic image or text or tabular data.
Use these scores to guide prompt engineering efforts (or hyperparameter-tuning of the synthetic data generator) in order to generate a good synthetic dataset.

#### Sample 10: Catch data entry mistakes
With Cleanlab Studio on a tabular dataset.  You can create a toy dataset with realistic-looking types of data entry mistakes for the purposes of this blogpost.

#### Sample 11: Find issues in customer dataset
Use Cleanlab Studio to auto-detect issues in a tabular dataset from business application.
Write what are the benefits of correcting such issues in the data.
Examples of applications:
* Insurance Industry: Cleanlab can help by automatically identifying and correcting ambiguities in customer data, such as unclear addresses or incorrect policy details. This ensures that risk assessments are based on accurate and reliable data, reducing the likelihood of costly claims due to data errors.
* Customer records: Cleanlab can help by analyzing customer interaction data, identifying duplicated or inconsistent customer records, and improving labeling for customer preferences.
* Cleanlab can assist in identifying outliers and anomalies in transaction data. By flagging unusual patterns and cleaning the data, it helps improve the accuracy of fraud detection algorithms. For instance, Cleanlab can automatically detect suspicious transactions with unusually large amounts or unusual locations.
* Demographic data in Loan Prediction: Cleanlab can identify and correct discrepancies in income levels, ensuring that customers receive offers that match their financial profiles.
* Cleanlab can automatically identify and rectify anomalies or inconsistencies in financial statements

### 3. Data
Description about the topic

#### Sample 1: Use Cleanlab Studio with data stored in Databricks
#### Sample 2: Compare using Cleanlab Studio with traditional data quality tools
#### Sample 3: Compare using Cleanlab Studio with other Data-Centric AI platforms
#### Sample 4: Find issues in a document tagging dataset
#### Sample 5: Find issues in a medical imaging dataset
#### Sample 6: Find issues in a content catalog dataset
#### Sample 7: Find issues in a manufacturing Quality-Control dataset
#### Sample 8: Find issues in agriculture dataset
#### Sample 9: Find issues in a non-English text dataset
#### Sample 10: Optimize synthetic dataset

### 4. Machine Learning
Description about the topic

#### Sample 1: Deploy ML model for tabular data
Show how quickly one can turn messy raw data into an accurate deployed ML Model for a structured/tabular dataset (multi-class classification task).
https://help.cleanlab.ai/tutorials/inference_api/

Evaluate the accuracy of the deployed ML model and show it is more accurate than other ML models from tools like Vertex AI (Google Cloud). 

Show how auto-cleaning the dataset (Clean Top K) button boosts the accuracy of the deployed model.

Ideal datasets will come from business domains like: customer churn prediction, fraud detection, …

<img width="844" alt="Deploy ML model for tabular data" src="https://github.com/konfhubtech/DataStories/assets/64151948/82d0c163-7817-4cc8-ac82-5eee911ad565">


#### Sample 2: Use Cleanlab Studio to boost ML accuracy
Idea is to show some common ML pipeline & tech stack that takes in raw data, trains model, evaluates it on test data.
Then show how the training & test datasets can be cleaned with Cleanlab Studio. After that, feed the improved training data into the same ML pipeline and show the resulting model is better (no change in any of the modeling code).  This is the power of Data-Centric AI.

<img width="435" alt="Use Cleanlab Studio to boost ML accuracy" src="https://github.com/konfhubtech/DataStories/assets/64151948/99343c54-0b5a-4a55-b01e-aa402ce6f338">

### 5. Business Intelligence
Description about the topic

#### Sample 1: Use Cleanlab Studio with Tableau
Show how to use Cleanlab Studio with Tableau.
Your blog could look something like this:
**Current workflow:**
raw data -> Tableau -> conclusion of data analysis
**Better workflow:**
raw data -> Tableau -> Cleanlab Studio -> exported better data ->  Tableau  -> better conclusion from data analysis
I.e. goal is show how the auto-corrected dataset from Cleanlab Studio can be used as a drop-in replacement for the orginal dataset, to get better results without any change in your existing data analysis pipeline.
Consider focusing on a specific data analysis question eg: “What fraction of customer service requests in category XYZ are about the keyword: ABC”
And then show the % you calculate from the raw dataset is significantly different than the % you calculate from the dataset auto-corrected w Cleanlab Studio.

![Use Cleanlab Studio with Tableau](https://github.com/konfhubtech/DataStories/assets/64151948/36e06393-9e4c-4ea9-a91d-88b179639144)

#### Sample 2: Use Cleanab Studio with PowerBI
Show how to use Cleanlab Studio with Power BI (or other similar analytics tool).
Your blog could look something like this:
**Current workflow:**
raw data -> Power BI -> conclusion of data analysis
**Better workflow:**
raw data -> Power BI -> Cleanlab Studio -> exported better data ->  Power BI  -> better conclusion from data analysis
I.e. goal is show how the auto-corrected dataset from Cleanlab Studio can be used as a drop-in replacement for the original dataset, to get better results without any change in your existing data analysis pipeline.
Consider focusing on a specific data analysis question eg: “What fraction of customer service requests in category XYZ are about the keyword: ABC”
And then show the % you calculate from the raw dataset is significantly different than the % you calculate from the dataset auto-corrected w Cleanlab Studio.

### 6. Cleanlab Studio
Description about the topic

#### Sample 1: Use Cleanlab Studio to boost ML accuracy
#### Sample 2: Use Cleanlab Studio with Tableau
#### Sample 3: Use Cleanab Studio with PowerBI
#### Sample 4: Use Cleanlab Studio with data stored in Databricks
#### Sample 5: Compare using Cleanlab Studio with traditional data quality tools
#### Sample 6: Compare using Cleanlab Studio with other Data-Centric AI platforms
#### Sample 7: Find issues in a document tagging dataset
#### Sample 8: Find issues in a medical imaging dataset
#### Sample 9: Find issues in a content catalog dataset
#### Sample 10: Find issues in a manufacturing Quality-Control dataset
#### Sample 11: Find issues in agriculture dataset
#### Sample 12: Find issues in a non-English text dataset
#### Sample 13: Optimize synthetic dataset
