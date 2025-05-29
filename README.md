# Podcast Listener Behavior Analysis

##  Table of Contents

- [Introduction](#1Introduction)
- [Data Description](#Data_Description)
- [Methodology](#Methodology)
- [Data Preprocessing](#Data_Preprocessing)
- [Descriptive Analysis](#Descriptive_Analysis)
- [Results and Outputs](#Results_and_Outputs)

---

### Introduction
This project aims to perform an initial data analysis of podcast listening records, understand user behavior and preferences through statistical and descriptive methods, and provide preliminary recommendations based on the insights obtained.

### Data Description
**The analysis relies on three primary datasets:**

* **Users (users.csv):** Contains user information such as user ID, age, gender, and location.
* **Episodes (episodes.csv):** Includes details of each podcast episode, including episode ID, title, category, and duration.
* **Listens (listens.json):** A log of user listening activity, linking user IDs with episode IDs and listen times.

### Methodology
#### Data Preprocessing
* Load datasets using pandas.
* Merge users, episodes, and listens into a unified DataFrame.

#### Descriptive Analysis
* Listen Count by Category
* Average Listen Duration by Gender
* Distribution of Unique Episodes per User
* Average Listen Duration by Age Group
* Lorenz Curve of User Listen Counts

### Results and Outputs
Analytical charts are saved under notebooks/figures/ for key findings.
