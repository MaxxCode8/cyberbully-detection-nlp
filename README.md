# Cyberbully Detection 🙊🗣💬
my first nlp project!
---
### [Kaggle Dataset](https://www.kaggle.com/datasets/saurabhshahane/cyberbullying-dataset) 
🧾Description: This dataset is a collection of datasets from different sources related to the automatic detection of cyberbullying. 
The data is from different social media platforms like Kaggle, Twitter, Wikipedia Talk pages, and YouTube. The data contains text and is labeled as bullying or not.
The data contains different types of cyberbullying like hate speech, aggression, insults, and toxicity. You have been provided with the twitter_parsed tweets dataset,
wherein you have to classify whether the tweet is toxic or not.

🧭 **Problem Statement:** You are provided with **twitter_parsed_tweets**: you have to perform a step-by-step NLP approach to identify the toxicity of the tweet, and classify the tweet in a binary value. 

The target variable is **oh-label** and the evaluation metric is **F1-score**.

---

#### Although the Task was to determine whether a tweet is a bully or not, I used a slightly different approach for detection...
If you look at the dataset, we have also `annotations` available for each tweet!
![image](https://github.com/MaxxCode8/cyberbully-detection-nlp/assets/105921273/e763e010-0cbf-4544-89e4-70b74f2b0f9d)

*To NOT lose this valuable insight into the tweet, I modified the task at hand.* 

### Modified task: TO DETECT WHETHER THE TWEET IS A `Sexist` or `Racist` or `Normal` " ( The problem became Multi-Class Classification ) "

Necessary changes in `loss function` etc were made ...

### Got an F1-score of 0.7 ⭐⭐⭐

### Confusion Matrix : 
![image](https://github.com/MaxxCode8/cyberbully-detection-nlp/assets/105921273/a34b7930-6739-4c2a-a9f5-9733982f83cb)
