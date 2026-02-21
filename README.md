# students-social-media-addiction-eda-python

# Student Social Media Addiction Analysis: A Global EDA Perspective

## Project Overview

In the digital age, social media has become an inseparable part of student life. While it offers connectivity, its excessive use is often linked to academic decline and mental health challenges. This project performs a deep-dive **Exploratory Data Analysis (EDA)** on a dataset of 700+ students globally to identify patterns of addiction, its impact on academic performance, and its correlation with mental well-being.

As the **Data and Business Analyst** for this project, my objective was to transform raw behavioral data into actionable insights that can help educational institutions and mental health professionals understand the "digital footprint" of the modern student.


## Business Problem & Objectives

The primary goal of this analysis is to evaluate how social media consumption habits translate into real-world consequences for students.

### Key Research Questions:

1. **Behavioral Segmentation:** Which platforms dominate student usage, and how do usage hours vary by gender and academic level?
2. **Performance Correlation:** Is there a statistically significant link between daily usage hours and a decline in academic performance?
3. **Wellness Impact:** How does "Addiction Score" correlate with sleep quality and overall mental health scores?
4. **Social Dynamics:** Do relationship statuses or family conflicts influence social media dependency?

---

## Dataset Description

The dataset used in this project is a cleaned version of the "Student Social Media Addiction" dataset sourced from **Kaggle**. It contains **705 records** across **13 features**.

| Feature | Description |
| --- | --- |
| `Student_ID` | Unique identifier for each student participant. |
| `Age` | Age of the student (Range: 18 - 24). |
| `Gender` | Gender identity (Male/Female). |
| `Academic_Level` | Level of study (Undergraduate, Graduate, High School). |
| `Country` | Geographic location (110 unique countries represented). |
| `Avg_Daily_Usage_Hours` | Mean hours spent on social media daily. |
| `Most_Used_Platform` | Primary platform (Instagram, TikTok, YouTube, etc.). |
| `Affects_Academic_Performance` | Self-reported impact on grades (Yes/No). |
| `Sleep_Hours_Per_Night` | Average sleep duration. |
| `Mental_Health_Score` | Subjective well-being score (Scale: 1-10). |
| `Relationship_Status` | Single, In Relationship, or Complicated. |
| `Conflicts_Over_Social_Media` | Frequency of social/family conflicts (Scale: 0-5). |
| `Addicted_Score` | Derived addiction metric (Scale: 1-10). |

---

##  Tech Stack & Methodology

### Technologies Used:

* **Language:** Python 3.x
* **Libraries:** Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib/Seaborn (Visualization), SciPy (Statistical Testing).
* **Environment:** Jupyter Notebook / VS Code.

### Analysis Workflow:

1. **Data Validation:** Checking for null values, data types, and ensuring consistency in categorical labels.
2. **Univariate Analysis:** Distributing usage hours, age groups, and platform popularity.
3. **Bivariate/Multivariate Analysis:** Analyzing the relationship between `Addicted_Score` vs. `Mental_Health_Score` and `Sleep_Hours`.
4. **Statistical Profiling:** Grouping data by `Academic_Level` and `Gender` to find significant variances in behavior.

---

## Key Insights (Sample Results)

* **Platform Dominance:** Instagram and TikTok are the most frequently used platforms, showing the highest correlation with high "Addicted Scores."
* **The "Academic Gap":** Students reporting a negative impact on performance spend an average of **2.5 hours more** per day on social media compared to those who don't.
* **Mental Health Inverse Relationship:** A clear trend shows that as daily usage exceeds 5 hours, the `Mental_Health_Score` drops by an average of 15-20%.
* **Sleep Deprivation:** High addiction scores are directly proportional to a decrease in sleep (averaging < 6 hours per night).

---

## How to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/your-username/students-social-media-addiction-eda-python.git

```


2. **Install Dependencies:**
```bash
pip install pandas numpy matplotlib seaborn

```


3. **Run the Analysis:** Open the `EDA_Student_Addiction.ipynb` notebook and run all cells.

---

##  Conclusion & Recommendations

Based on the analysis, it is recommended that:

* **Universities** should implement "Digital Wellness" workshops for undergraduates, as they represent the highest risk demographic.
* **Students** should utilize "App Timers" to maintain usage under the 4-hour threshold where mental health scores remain stable.

---

##  Author

**Nandini Verma**

* **Role:** Data and Business Analyst

---

*License: This project is licensed under the MIT License - see the LICENSE file for details.*
