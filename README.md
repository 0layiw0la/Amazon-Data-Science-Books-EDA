# Amazon-Data-Science-Books-EDA
## Objectives
<p>We perform eda on a data containing data science books on amazon names prices ratings weight etc. This was more of a for fun project that answers one question. <strong>What are the best books for data scientists on Amazon?</strong>. As someone who prefers books to courses <strong>(yes, it's odd, i know)</strong>, when i came across this dataset on kaggle i knew i had to try it out.</p>
Ok i may have answered more than one question, i couldn't resist.

## Content
* How much do books cost (effect of size on price).
* WHat are the best books for python.
* What are the books ML books.
  
# Insights
## How much do data science books cost on average?
* The average price of the books on amazon is : **$46.7**
  ![image](https://github.com/0layiw0la/Amazon-Data-Science-Books-EDA/assets/103042427/8767e737-3888-492d-9c14-f3f133a184b4)

* Most books fall below $50 in terms of price.
## How does number of pages affect book price?
* From the scatter plot we can see books with more pages have higher prices but to better visualize it we can look at the correlation matrix.
![image](https://github.com/0layiw0la/Amazon-Data-Science-Books-EDA/assets/103042427/044c7a1d-fb0a-41f2-88dc-17194d31f342)

* There is a moderately positive correlation between number of pages and book prices (0.43) i.e (The more pages a book has the higher the chances it costs more)
  ![image](https://github.com/0layiw0la/Amazon-Data-Science-Books-EDA/assets/103042427/f9730745-91ab-4306-9932-d073b0eb8214)

## What are the best books for learning python
To asses this we use the avg rating and number of reviews.
![image](https://github.com/0layiw0la/Amazon-Data-Science-Books-EDA/assets/103042427/d0745abe-9e25-4a2c-b15f-d0c07cb18c2b)

* The best book for learning python on Amazon is **Python Crash Course, 2nd Edition: A Hands-On, Project-Based Introduction to Programming** with a **4.7** star rating over **7,000+ reviews**.

* <span style="color: grey; text-decoration: italic;">A honorable mention (This is my personal opinion) would be Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython. It's great for data analysts and is the 8th best book with a 4.6-star rating and over 1,000+ reviews.</span>
* ## What are the best books for Machine Learning
* The best book for ML is **Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow**, If you learn with books you have probably heard of this one. It has a **4.8** star rating with **3,000+ reviews**.
* ![image](https://github.com/0layiw0la/Amazon-Data-Science-Books-EDA/assets/103042427/cf8bff8f-d389-4a81-a332-1afa20978c1c)

### What's the most expensive book?
* The most expensive data science related book listed on Amazon is **he Basics of Data Literacy: Helping Your Students (And You!) Make Sense of Data - PB343X** at **$287**.
It was published by National Science Teachers Association - NSTA Press (November 15, 2013), it has a 4.6 star rating but just 6 reviews so i can't take the rating too serious.
