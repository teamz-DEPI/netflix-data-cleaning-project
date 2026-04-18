# 🎬 Netflix Data Cleaning Project

### Missing Values, Duplicates, Formatting & Data Preparation using Python

---

# Instructor
**Dina Ezzat**

---

# 👥 Project Team

| Name          | Role          |
| ------------- | ------------- |
| Mohamed Omar  | Data Analysis |
| Kerols Raafat | Data Analysis |
| Joseph Milad  | Data Analysis |
| Yahya Ebrahim | Data Analysis |
| Ahmed Reda    | Data Analysis |
| Ahmed Elsayed | Data Analysis |

---

# 📌 Project Idea

This project focuses on cleaning and preparing a **Netflix dataset** using **Python** and **Pandas** to make the data ready for analysis and visualization.

The main goal is to detect hidden data quality issues, handle missing values, remove duplicate records, standardize text formatting, and convert important columns into more useful data types for analysis.

---

# 📌 Project Description

This project works on a **Netflix titles dataset** that contains information about movies and TV shows available on the platform.

The dataset includes details such as:

* Show ID
* Content type
* Title
* Director
* Country
* Date added
* Release year
* Rating
* Duration
* Listed categories

Although the dataset looked clean at first, a deeper inspection revealed several data quality problems that needed to be fixed before any proper analysis could be done.

The main objective of this project is to apply **data cleaning techniques** to improve the dataset quality and prepare it for future **EDA, visualization, and dashboard creation**.

---

# Problems Found in the Dataset

During the inspection process, several issues were discovered:

* Hidden missing values stored as text such as `Not Given` and `Unknown`
* A missing value in the `title` column
* Duplicate rows when excluding `show_id`
* Inconsistent spacing in text columns
* `date_added` stored as text instead of datetime
* `release_year` needed type validation
* `duration` contained mixed formats such as `90 min` and `1 Season`

These problems could affect the accuracy of analysis and needed to be handled carefully.

---

# Data Cleaning Process

The dataset was cleaned through multiple steps:

* Replacing hidden missing values like `Not Given` and `Unknown`
* Dropping the row with missing `title`
* Filling missing values in `director` and `country`
* Removing extra spaces from text columns
* Removing duplicate rows
* Converting `date_added` into datetime format
* Converting `release_year` into numeric format
* Standardizing text formatting in columns such as `type` and `rating`
* Splitting and organizing the `duration` column into clearer forms for analysis

Through these steps, the dataset became more structured, consistent, and ready for further analysis.

---

# Project Goals

The main goals of this project are:

* Improve overall data quality
* Handle missing and inconsistent values
* Remove duplicate records
* Standardize formatting across columns
* Prepare the dataset for exploratory data analysis
* Make the dataset ready for visualization and reporting

---

# Roles & Responsibilities

* **Dina Ezzat** – Project supervision and academic guidance
* **Mohamed Omar** – Data cleaning, EDA, and documentation
* **Kerols Raafat** – Data preprocessing and visualization support
* **Joseph Milad** – Data review and reporting
* **Yahya Ebrahim** – Dataset inspection and validation
* **Ahmed Reda** – Cleaning support and formatting review
* **Ahmed Elsayed** – Notebook organization and presentation preparation

---

# ✨ Project Features

* Data cleaning using Python and Pandas
* Handling missing values
* Detecting hidden null-like values
* Removing duplicates
* Cleaning and standardizing text data
* Converting columns into proper data types
* Preparing duration-related fields for easier analysis
* Final validation of the cleaned dataset

---

# 📂 Dataset Description

The dataset contains information about **Netflix movies and TV shows**.

Each row represents **one title** available on Netflix.

## Dataset Columns Explanation

| Column | Description |
|--------|-------------|
| show_id | Unique identifier for each title |
| type | Type of content such as Movie or TV Show |
| title | Name of the movie or TV show |
| director | Director of the title |
| country | Country of production |
| date_added | Date when the title was added to Netflix |
| release_year | Year the title was released |
| rating | Content rating |
| duration | Duration of the movie or number of seasons |
| listed_in | Content categories or genres |

---

# 🛠 Tools & Technologies Used

* **Python**
* **Pandas** – data cleaning and manipulation
* **NumPy** – handling missing values and numerical operations
* **Jupyter Notebook** – development environment

These tools were used to inspect, clean, transform, and validate the dataset.

---

# 📊 Cleaning Summary

The project included the following main cleaning tasks:

* Identifying hidden missing values
* Replacing invalid placeholders with real null values
* Handling missing data in important columns
* Removing duplicate entries
* Standardizing text columns
* Converting dates and numeric fields
* Preparing duration columns for cleaner analysis

At the end of the cleaning process, the dataset became significantly more reliable and ready for the next stage of analysis.

---

# 📂 Project Structure

```bash
Netflix-Data-Cleaning-Project
│
├── netflix1.csv
├── netflix1_cleaned.csv
├── netflix.ipynb
└── README.md
```

---

# ⚙️ Installation

Install the required Python libraries before running the project:

```bash
pip install pandas numpy jupyter
```

---

# ▶️ How to Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open the notebook file:

```bash
netflix.ipynb
```

---

# Final Output

The final output of this project is a cleaned Netflix dataset that is ready for:

* Exploratory Data Analysis (EDA)
* Data visualization
* Dashboard creation
* Further business or content analysis

---

# Conclusion

Data cleaning is an essential step in any data project. In this project, the Netflix dataset was carefully cleaned and prepared by handling hidden missing values, duplicates, formatting issues, and data type inconsistencies.

This process improves the reliability of the dataset and creates a strong foundation for any future analysis.
