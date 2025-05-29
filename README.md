📊 Student Performance Analysis
This project analyzes student academic performance using clustering, regression, and classification techniques in R. It aims to identify patterns in student scores, predict total marks, and classify students as pass or fail.

📁 Dataset
The dataset results.csv includes student scores in the following subjects:

Hindi

English

Science

Maths

History

Geography

Total Marks

Results (Pass/Fail)

🛠️ Tools & Libraries Used
R Programming

Libraries:

ggplot2 – Data Visualization

dplyr – Data Manipulation

caret – Machine Learning

cluster – Clustering

factoextra – Cluster Visualization

e1071 – Classification support

📌 Features
Descriptive Statistics: Summary and standard deviation of scores.

Correlation Matrix: Understanding relationships among subjects.

K-Means Clustering: Grouping students based on scoring patterns.

Regression Analysis: Predicting total marks using individual subject scores.

Classification Model: Predicting Pass/Fail results using logistic regression.

Evaluation Metrics: Confusion matrix for classification accuracy.

📷 Visualizations
Cluster plots using fviz_cluster()

Correlation heatmap

Predicted vs Actual Total score analysis

📈 Model Summary
Regression Model: Linear regression predicting total marks.

Classification Model: Logistic regression predicting pass/fail outcome.

Clustering: 3 clusters created to categorize performance levels.

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/student-performance-analysis.git
Open the R script in RStudio or any R environment.

Make sure to update the file path to your dataset in the code.

Run the script line-by-line to analyze and visualize the data.

📄 Output
Predicted total marks added to dataset

Student clusters labeled and visualized

Confusion matrix for classification results

🧠 Insights
Subjects with higher correlation contribute significantly to overall performance.

Clustering reveals clear distinctions between low, average, and high performers.

Logistic regression allows proactive identification of students at academic risk.

📬 Contact
For any queries or suggestions, feel free to contact [Your Name] – [your-email@example.com]
Or raise an issue on this repository.
