# Netflix Movies and Shows Analysis

This project analyzes the Netflix Movies and Shows dataset to gain insights into the types of content available on the platform. The analysis focuses on key questions related to the distribution of content types, popular genres, content growth trends, and average duration.

---

## **Objective**

The goal of this project is to answer the following questions based on the dataset:

1. What is the distribution of movies versus TV shows on Netflix?
2. What are the most common genres of content?
3. How has the addition of new content changed over the years?
4. What is the average duration of movies compared to TV show episodes?

---

## **Dataset**

The dataset used for the analysis is provided in the `/data` folder. It contains columns such as:

- **Type**: Movie or TV Show
- **Genre**: Content genre(s)
- **Date Added**: When the title was added to Netflix
- **Duration**: Runtime for movies and number of seasons for TV shows
- **Other Metadata**: Title, Director, Cast, Country, Release Year, etc.

---

## **Files in the Repository**

1. **`Netflix_Analysis.ipynb`**:  
   A Jupyter Notebook containing the Python code used to clean, process, and analyze the dataset. This includes visualizations and answers to the analysis questions.

2. **`Netflix_Report.pdf`**:  
   A professional report summarizing the findings of the analysis, including visualizations for key insights.

---

## **Key Findings**

### **1. Distribution of Movies vs TV Shows**

- **Movies**: 6131 (69.62%)
- **TV Shows**: 2676 (30.38%)

Movies dominate the Netflix catalog, but TV Shows make up a significant portion, reflecting Netflix’s focus on binge-worthy series.

### **2. Most Common Genres**

- **Top 3 Genres**:
  - International Movies: 2752 titles
  - Dramas: 2427 titles
  - Comedies: 1674 titles

Netflix’s content is diverse, with a strong emphasis on international and dramatic content.

### **3. Content Growth Over the Years**

- **Growth Accelerated in 2015**:  
  Content additions peaked in **2019**:
  - **Movies**: Over 1400 titles added
  - **TV Shows**: Approximately 600 titles added

Post-2019, content additions declined, possibly reflecting a strategic shift or external constraints.

### **4. Average Duration**

- **Movies**: Average duration is **99.58 minutes**.
- **TV Shows**: Average duration is **1.76 seasons**.

The shorter duration of TV shows aligns with modern binge-watching trends.

---

## **How to Recreate the Analysis**

To reproduce the analysis, check out this **[Google Colab Notebook](https://colab.research.google.com/drive/12X6dcjxCcfXFlt5vng66xqYvPSf_ZVSS?usp=sharing)**. It contains the full code and comments.

---

## **Tools and Libraries Used**

### **Python Libraries**:

- `pandas`: For data manipulation and analysis.
- `matplotlib.pyplot`: For creating static visualizations.
- `seaborn`: For enhanced and aesthetically pleasing visualizations.
- `datasist`: For quick exploratory data analysis.
- `collections.Counter`: For counting occurrences of genres and other categorical variables.

---

## **Contributors**

Joseph Davies

- Email: Josephtobi53@gmail.com
- GitHub: Josephtobi
