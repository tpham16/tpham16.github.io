---
title: "FIFA 21 Players Dataset Data Cleaning & Transformation"
excerpt: "Analyzed the FIFA 2021 player dataset with a focus on data cleaning, transformation, and exploratory data analysis (EDA). This extensive dataset provided in-depth information about football players, encompassing attributes, ratings, positions, and personal details. Through EDA, I delved into player attributes and positions, uncovering valuable insights, including the identification of highly valuable but underpaid players. [View Code on GitHub](https://github.com/tpham16/FIFA-21-Players) \n\n[![Social Media Engagement Dashboard](/images/fifa21.png){: style='display: block; margin: 0 auto; border: 2px solid black;' width='75%'}](https://github.com/tpham16/FIFA-21-Players)"
collection: portfolio
---

⚽**FIFA21 Data Cleaning & Transformation** 

FIFA21 is a popular video game that simulates soccer matches. Often, data collected from this game might be messy, containing missing values and various formating issues. As an enthusiastic soccer fan, I put together this project to practice data cleaning and data exploring for analysis using Python and Pandas. 

🛠️**Tools**
* Python 

📊**The FIFA21 Dataset**

I found the FIFA21 Dataset on [Kaggle](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring/data). The dataset contains 17,000+ players featuring in FIFA21, each with more than 70 attributes. 

💡**Highlights** 
* England had the highest amount of players, making up 8.98% of all players. 
* Spain had the most players in the Top 100. 
* Identified highly valuable, underpaid players by comparing player overall performance and wages. 

✏️**Data Wrangling**
* Removed rows with missing values
* Converted height and weight columns to appropriate data types
* Cleaned and transformed the value, wage, and release clause columns into columns of integeters
* Removed the unnecessary newlien characters
* Separated the Team and Contract columns
* Converted 'star' characters to numeric data
* Converted attribute stats to an average of the sum 

