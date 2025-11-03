
# 📊 Facebook User Engagement Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on Facebook user engagement data to uncover patterns, trends, and relationships among metrics such as likes, comments, shares, and post types.
It helps understand what drives higher engagement on Facebook content.

---

## 🧠 Project Overview

Social media engagement is a key indicator of audience interaction and content performance.
This project analyzes a Facebook user engagement dataset to identify the factors that influence engagement and how different types of content perform across metrics.

The EDA focuses on:

* Understanding distribution and trends in engagement metrics.
* Identifying correlations between variables.
* Detecting outliers and unusual engagement behaviors.
* Deriving insights that can help optimize social media strategies.

---

## 🗂️ Dataset Description

The dataset (e.g., `facebook_user_engagement.csv`) contains Facebook post-level information such as:

| Column                                    | Description                                           |
| ----------------------------------------- | ----------------------------------------------------- |
| **Post_ID**                               | Unique identifier for each post                       |
| **Type**                                  | Post type (Photo, Status, Video, Link)                |
| **Category**                              | Category of post (e.g., Entertainment, News, Product) |
| **Page_Total_Likes**                      | Total likes on the page at time of posting            |
| **Post_Month / Post_Weekday / Post_Hour** | Time-related metadata                                 |
| **Paid**                                  | Whether the post was sponsored (1 = Yes, 0 = No)      |
| **Lifetime_Post_Total_Reach**             | Number of people reached                              |
| **Lifetime_Post_Total_Impressions**       | Total number of times the post was seen               |
| **Lifetime_Engaged_Users**                | Users who engaged with the post                       |
| **Lifetime_Post_Consumers**               | Users who clicked on post content                     |
| **Comment / Like / Share**                | Engagement metrics                                    |

*(Columns may vary slightly depending on dataset version.)*

---

## ⚙️ Technologies & Libraries

* **Language:** Python 
* **Libraries Used:**

  * `pandas` – data manipulation
  * `numpy` – numerical operations
  * `matplotlib` & `seaborn` – data visualization
  * `plotly` – interactive charts (optional)

---

## 🔍 EDA Process

### 1️⃣ Data Cleaning

* Handle missing values and data inconsistencies.
* Remove duplicates and incorrect data points.

### 2️⃣ Data Understanding

* Inspect structure using `.info()` and `.describe()`.
* Check data types and statistical summaries.

### 3️⃣ Univariate Analysis

* Distribution of likes, comments, and shares.
* Most common post types and posting times.

### 4️⃣ Bivariate & Multivariate Analysis

* Correlation between reach, impressions, and engagement.
* Engagement comparison across post types and categories.
* Time-based analysis (day vs. engagement).

### 5️⃣ Outlier Detection

* Boxplots and IQR method to detect unusually high or low engagement posts.

### 6️⃣ Insights Visualization

* Bar plots, pie charts, histograms, and heatmaps to visualize relationships.

---

## 📈 Key Insights

* **Photo posts** tend to get the highest engagement.
* **Sponsored (Paid) posts** generally reach more users but don’t always have the highest engagement.
* Engagement is **highest during weekdays**, especially around **evening posting hours**.
* There’s a **strong positive correlation** between impressions and engagement metrics.
* **Outlier posts** often indicate viral content or marketing campaigns.

