# Podcast Listener Behavior Analysis

##  Table of Contents

- [Introduction](#introduction)
- [Data Description](#data_description)
- [Methodology](#methodology)
- [Data Preprocessing](#data_preprocessing)
- [Descriptive Analysis](#descriptive_analysis)
- [Results and Outputs](#results_and_outputs)

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
Analytical charts are saved under [Figures File](https://github.com/SelwanHalawani/Thmanyah-Podcast-/tree/main/Figures) for key findings.
