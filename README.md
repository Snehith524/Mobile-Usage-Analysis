## 📱 Mobile Usage Behavioral Analysis

###  Exploratory Data Analysis of User Behavior Based on Mobile App Usage 

---

### 📘 **Project Overview**

In this project, I performed an exploratory data analysis (EDA) on a dataset that contains information about mobile phone usage patterns such as screen time, number of apps used, social media usage, gaming hours, and more. The goal was to uncover insights about demographics, app usage behavior, and the most-used app categories among users. This project is entirely built and visualized using **Python in Jupyter Notebook**.

---

### 🎯 **Objectives**

* Clean and prepare the dataset
* Understand user demographics (age, gender)
* Analyze total screen time, app usage hours, and category-specific app usage
* Estimate the most-used app per user
* Visualize behavioral patterns using gender and age as factors
* Simulate decisions as a student analyzing real-world data

---

### 📁 **Dataset Description**

The dataset `mobile_usage_behavioral_analysis.csv` contains the following columns:

* `User_ID`: Unique identifier for each user
* `Age`: Age of the user
* `Gender`: Gender of the user
* `Total_App_Usage_Hours`: Total usage of apps per day (in hours)
* `Daily_Screen_Time_Hours`: Total screen-on time per day
* `Number_of_Apps_Used`: Count of different apps used in a day
* `Social_Media_Usage_Hours`: Time spent on social media apps
* `Gaming_App_Usage_Hours`: Time spent on gaming apps
* `Productivity_App_Usage_Hours`: Time spent on productivity apps

---

### 🧹 **Why Cleaning Was Needed**

Before analysis, it was essential to:

* Remove **missing values** and **duplicates** to avoid biased analysis
* Convert numeric fields to appropriate data types
* Understand column meanings

I avoided imputing missing values because they could misrepresent behavioral patterns. Instead, I dropped rows with nulls for cleaner analysis.

---

### 🧠 **Approach and Thought Process**

#### Step 1: Understanding Demographics

I started by analyzing age and gender because these two factors significantly influence app usage behavior. Visualizing them helped in segmenting user behavior by gender and age group.

#### Step 2: Behavioral Features Analysis

I separated key features like:

* Screen time
* Total app usage
* Category-wise usage (Social Media, Gaming, Productivity)

This made it easier to visualize and interpret each aspect of mobile usage.

#### Step 3: Estimate Most Used App

Since the dataset didn’t have actual app names, I assumed the **most-used category** based on max usage per user and **mapped** each category to a popular app:

* Social Media → Instagram
* Gaming → PUBG
* Productivity → Google Docs

I chose this method over synthetic app names because it provides realistic interpretation while still being data-driven.

---

### 🔍 **Visualizations**

I used **Seaborn and Matplotlib** to create:

* Histograms for usage distributions
* Bar plots to compare usage by gender and age group
* Count plot for most used app category

Box plots were avoided to keep visuals simple and understandable from a non-technical user’s point of view.

---

### 🤔 **Why This Approach (and Not Others)?**

* I did not use machine learning because the aim was to **understand patterns**, not **predict behavior**
* I avoided complex clustering since data didn't include enough app-level detail
* I chose bar plots instead of box plots as they are easier to interpret for general audiences

This project is focused more on **insight generation** than modeling.

---

### 📌 **Insights and Observations**

* Users aged 21-30 had the highest screen time on average
* Social media apps were the most commonly used
* Males spent slightly more time gaming than females
* Productivity app usage was highest among older age groups

---

### 🚀 **Tools and Technologies**

* Python 🐍
* Pandas (Data manipulation)
* Matplotlib & Seaborn (Visualizations)
* Jupyter Notebook (Code + Analysis)

---


### 📚 **Future Work**

* Collect app-specific data (like Instagram, WhatsApp, etc.)
* Include time-of-day usage (morning/night)
* Add click and notification data
* Try unsupervised learning (clustering users)

---

### 🙋‍♂️ **Author Note**

This project was done as a student to explore how real-world user behavior can be interpreted using Python. Every step was taken with learning in mind — trying out multiple methods, making assumptions carefully, and keeping the audience (non-technical included) in mind.

---
