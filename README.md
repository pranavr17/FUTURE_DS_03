🎓 College Event Feedback Analysis – Internship Project

📊 Overview

This project focuses on analyzing student feedback data collected from college events to uncover trends in satisfaction, identify improvement areas, and visualize insights effectively. Using survey responses (Google Forms data), the project applies data analytics and sentiment analysis techniques to derive actionable insights.


---

🧠 Objectives

Clean and preprocess raw survey data for analysis

Perform sentiment analysis on student comments

Identify event satisfaction trends

Generate meaningful data visualizations (bar charts, pie charts, word cloud)

Provide recommendations for future event improvements



---

🧰 Tools & Libraries

Tool	Purpose

Google Colab	Development environment
pandas	Data manipulation and cleaning
TextBlob / VADER	Sentiment analysis
seaborn	Data visualization
matplotlib	Charting and plots
WordCloud	Visualizing comment frequency
Google Forms (CSV/Excel)	Source of survey data



---

⚙️ Steps Performed

1. Data Upload & Exploration

Imported the feedback dataset (college_event_feedback_2.xlsx)

Displayed initial structure and summary statistics



2. Data Cleaning

Handled missing values and invalid ratings

Converted ratings to numeric type

Removed irrelevant or empty entries



3. Visualization of Event Ratings

Created bar charts showing rating distribution



4. Sentiment Analysis

Used TextBlob to calculate polarity scores

Classified comments as Positive, Negative, or Neutral



5. Sentiment Distribution Visualization

Displayed a pie chart summarizing sentiment types



6. Word Cloud Generation

Highlighted frequently mentioned words in feedback comments



7. Summary Insights

Calculated average ratings per event

Counted sentiment categories for overall perception





---

📈 Key Insights

Quantified levels of satisfaction across various college events

Identified common keywords from positive and negative feedback

Highlighted events with higher engagement and appreciation



---

💡 Skills Gained

Data Cleaning and Transformation

Sentiment Analysis (NLP)

Exploratory Data Analysis (EDA)

Data Visualization and Storytelling

Python Programming in Google Colab



---

📂 Project Structure

College_Event_Feedback_Analysis/
│
├── college_event_feedback_2.xlsx      # Dataset (Google Forms responses)
├── google_collab_college_event.ipynb  # Main analysis notebook
├── README.md                          # Project documentation
└── outputs/                           # Charts and visualizations (optional)


---

🚀 How to Run

1. Open the notebook in Google Colab


2. Upload college_event_feedback_2.xlsx when prompted


3. Run all cells sequentially


4. View charts, sentiment results, and insights generated automatically




---

🏁 Conclusion

This project demonstrates how data-driven analysis can enhance understanding of student event satisfaction. By leveraging natural language processing and visualization tools, institutions can make informed decisions to improve student engagement and event quality.
