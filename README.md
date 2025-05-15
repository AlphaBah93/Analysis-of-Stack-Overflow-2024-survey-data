# 🧠 Stack Overflow 2024 Survey Data Analysis

This project aims to explore and visualize the results of the 2024 Stack Overflow Developer Survey, highlighting major trends in the software development world. Through descriptive and visual analysis, it showcases developer profiles, technology adoption (AI, databases, etc.), and key insights about experience, geography, and preferences in the developer community.

---

## 📌 Objective

To identify and understand the main trends within the global developer community based on responses from over 65,000 participants in the Stack Overflow 2024 survey. The analysis covers developer roles, AI adoption, preferred tools, geographic and experience distribution, and more.

---

## 🛠️ Technologies Used

- **Language**: Python  
- **IDE**: Visual Studio Code  
- **Libraries**:
  - `pandas`: data manipulation
  - `numpy`: numerical processing
  - `matplotlib`, `seaborn`: data visualization

---

## 🧪 Methodology

1. **Load the data** from the CSV file  
2. **Clean the data**: remove duplicates, handle missing values (replacing with mean, median, or most frequent value depending on the column type)  
3. **Preprocess**: convert, group, and normalize relevant data  
4. **Exploratory data analysis**: group and analyze by category (age, experience, country, etc.)  
5. **Visualize**: create clear, relevant visualizations  
6. **Synthesize**: build a storytelling report based on key findings

---

## 🗂️ Project Structure

The project is organized as follows:

📁 StackOverflow_2024_Analysis/
│
├── 📁 Capture
│ ├── 📁 All → All generated visualizations
│ └── 📁 In Report → Graphs used in the final report
│
├── 📁 dataset
│ ├── 2024 Developer Survey.PDF → Official survey questionnaire
│ ├── survey_results_public.zip → Raw data
│ └── survey_results_schema.csv → Column schema and descriptions
│
├── 📁 Rapport
│ └── Rapport_StackOverflow2024.pdf → PDF report with key visualizations and insights
│
├── 📄 Python.ipynb → Full Python script (data cleaning, analysis, and visualization)
└── 📄 README.md → Project documentation
