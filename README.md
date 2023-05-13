# TWITTER SENTIMENT ANALYSIS USING NATURAL LANGUAGE PROCESSING
## OBJECTIVE
<p>Analyse twitter data or tweets made by users during a certain period of time using NLP.</p>
<p>Classify the tweets made either in positive category or negative category.</p>

## Importing Modules And Dataset
<p>The csv module enables us to read each of the row in the file using a comma as a delimiter. We first open the file in read only mode and then assign the delimiter. Finally use a for loop to read each row from the csv file.</p>

<li><b>Reading Testing Data</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/6b7bc585-5298-41ef-80a0-40ff61e69f02)

<li><b>Reading Validation Data</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/163cc1ae-c19e-41d7-aa46-01414847bca4)

## VISULAIZING THE DATA
<p>Data visualization is the discipline of trying to understand data by placing it in a visual context so that patterns, trends, and correlations that might not otherwise be detected can be exposed.</p>

<li><b>All Words Positive</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/0de4e10f-a4bc-4fb8-ad28-cd3e216a974e)

<li><b>All Words Negative</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/715d4fd5-4962-4c7d-bb64-aa30a0cc6fd3)

## Plotting Bar Plots To Visualize Data

<li><b>Positive words Plot</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/8450990a-9fbe-4f4e-9be5-514992b1d6c6)

<li><b>Negative words Plot</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/a13be53c-88bc-4c69-92db-588d7caefe1a) 

## Applying ML (Logistic Regression).

<p>We will use popular Machine Learning prediction technique, Logistic Regression here as logistic regression is referred as the go to algorithm for binary classification.</p>

<li><b>Fitting and predicting by TF-IDF:</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/e66ac9be-11c2-4b78-b7e0-67fb2b9ccea2)
![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/946784ae-8efe-431d-b2f7-ea7c9c420618)

<li><b>Fitting and predicting by Bag-Of-Words:</b></li>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/04895340-bf66-4f3d-8ac1-8de1e88d1289)
![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/3f1895d9-9d60-4060-9ea6-da217e45620d)

## Comparing F1 Score (Evaluation Metric)
<p>Here it is clearly visible that TF-IDF (Term Frequency – Inverse Document Frequency is the better technique for feature selection than Bag of Words.</p>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/96ca4b39-1eed-4553-a609-4c55333e0a1a)


## Predicting types of tweet.
<p>Here, we have predicted the type of value a tweet possesses using logistic regression. The label column identifies the type of tweet made as either “Positive” or “Negative”.</p>

![image](https://github.com/VidushiRastogi15/Twitter-Sentiment-Analysis-using-NLP/assets/118375146/58a4ed21-a718-47db-979c-98a22f8da605)















