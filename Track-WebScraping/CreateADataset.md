<h1 align="center">
    Workshop - Create a Dataset
</h1>

<p align="center">
    <img width="250" height="250" src="https://cdn4.iconfinder.com/data/icons/emoji-2-5/64/_robot_emoticons_smiley-512.png">
</p>
<br>

<h3 align="center">
    The objective of this workshop is to explore how to create a dataset from different website.
</h3>
<br><br>

## **What is a dataset?**

A dataset is a collection of data. Most commonly a dataset corresponds to a single database table, where every column of the table represents a particular variable, and each row corresponds to a given record of the dataset in question.

## **What is a dataset used for?**

A dataset is used to train a machine learning model. The model, in turn, is used to make predictions based on new data. In supervised learning, a dataset is used to train the model and then the model is applied to a new dataset with the same variables but without the target.

<br><br>

# **Objectif of this workshop**

In this workshop, we are going to create a dataset of your choice and try to make some interpretation of this one.
<br><br>

# **Get started**

## **1- Think about your idea**

The first step to do is to find an idea of dataset you want to create.

Here are some ideas:
- A movie dataset
- A sport statistics dataset
- A netflix movies dataset

Some questions to ask yourself:
- What is the goal of my dataset?
- What is the data I need to collect?
- What is the website I can use to collect my data?
- Does the website I want to use is blocking me?

Once you have your idea, you can continue to the next step.

<br>

## **2- Check how to extract**

The objectif of this step is to check how you can extract your data from the website you want to use.

Some questions to ask yourself:
- What is the structure of the website?
- What task do I need to do to extract my data? (Scraping, crawling, Scraping dynamic, api, ...)
- How can I extract my data? (BeautifulSoup, Selenium, Scrapy, ...)
- How will I get my data? (XPath, CSS selector, Regex, ...)
- How can I save my data? (CSV, JSON, ...)

> CSV is the most common format to save your data in a dataset, I suggest you to use this one.

<br>

## **3- Create your dataset**

Now that you have all the information you need, you can start to create your dataset. You can implement all the code you need.

> A ipynb file could be a good idea to take your time to study how to extract your data without launch a request every time you want to test your code.

<br>

## **4- Interpret your dataset**

Once you have your dataset, you can start to interpret it. Try to treat read your dataset with pandas and try to make some statistics.

```python
import pandas as pd

df = pd.read_csv('my_dataset.csv')

# Do some statistics
# Exemple:
# - In the case of a movie dataset, you can try to find the most popular movie, the most popular actor, the most popular director, etc etc
# - In the case of a sport statistics dataset, you can try to find the most popular player, the most popular team, etc etc
```

> Pandas is a python library to manipulate dataset.

<br>

## **5- Share your dataset**

Now that you have your dataset, you are free to share it with the community. You can share it on multiple website like: Kaggle, Github, etc etc

> Kaggle is a website where you can find a lot of dataset and also share your own dataset.

<br>

# **To go further**

Now that you have the basics to create a dataset, here some ideas to improve your skills:
- Create a dataset with a dynamic website (more difficult than a static website)
- Create a model to predict something with your dataset

Otherwise, you can try to do the same exercice but using other technique than WebScraping:
- Use an API
- Mobile scraping
- Image scraping
- Video scraping
- Audio scraping
- etc etc
