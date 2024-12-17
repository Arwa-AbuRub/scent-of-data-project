# **Data Science Project: The Scent of Data**

### **Introduction**
This project demonstrates proficiency in data science techniques by conducting a novel analysis of a dataset related to perfumes and user ratings. The dataset contains metadata about perfumes, including scent composition, user ratings, and other attributes, allowing for in-depth exploration and predictive modeling.

The goal of this project is to uncover patterns in the dataset and build a model that predicts user ratings based on factors such as scent composition, release year, and brand. This analysis will apply data cleaning, visualization, statistical modeling, and machine learning techniques.

---

### **Project Objectives**
1. **Analyze** the factors influencing perfume ratings.
2. **Visualize** patterns and relationships between variables.
3. **Predict** user ratings using a regression model.
4. **Provide Insights** for future improvements in product design and user engagement.

---

### **Dataset**
The dataset used in this project contains 13 variables and over 5,000 observations. It includes the following key features:
- **Rating_Value**: The average user rating (outcome variable).
- **Rating_Count**: The number of user ratings.
- **Release_Year**: The year the perfume was launched.
- **Main_Accords**, **Top_Notes**, **Middle_Notes**, **Base_Notes**: Information about the perfume's scent composition.
- **Brand** and **Perfumers**: Metadata about the perfume's creators.

---

### **Project Components**
This project is divided into three main components:

1. **Proposal**:
   - Outlines the general plan for the project.
   - Serves as a blueprint for the analysis and modeling approach.
   - Ensures the project is feasible and aligned with the goals of the course.

2. **Presentation**:
   - Mid-stream presentation of the work.
   - Includes feedback from professors, invited guests, and classmates.
   - Helps refine the final report and improve the overall analysis.

3. **Report**:
   - The final deliverable that documents the analysis in its entirety.
   - Includes data exploration, methodology, results, and discussion.

---

### **Tools and Techniques**
The project utilizes the following tools and libraries:
- **R Programming**: For data manipulation, visualization, and modeling.
- **tidyverse**: For data wrangling and visualization.
- **ggplot2**: For creating high-quality plots.
- **naniar**: For handling and visualizing missing data.
- **broom**: For tidying model outputs.
- **patchwork**: For combining plots into complex layouts.

---

### **Expected Outcomes**
1. A cleaned and well-documented dataset ready for analysis.
2. Exploratory Data Analysis (EDA) that highlights key patterns and relationships.
3. A regression model that predicts perfume ratings based on scent composition and metadata.
4. Visualizations and tables summarizing the findings.
5. Insights into how perfume brands can optimize their products to appeal to users.

---

### **How to Run the Project**
1. Clone this repository:
   ```bash
   git clone https://github.com/Arwa-AbuRub/scent-of-data.git
   cd scent-of-data-project
   ```
2. Open the R Markdown file (`DatascienceArwa.Rmd`) in RStudio.
3. Install required R packages:
   ```r
   install.packages(c("tidyverse", "janitor", "ggplot2", "naniar", "broom",  "xaringan", "kableExtra", "patchwork"))
   ```
4. Run the R Markdown file to reproduce the analysis and results.
5. Open the file  `presentation.Rmd`.
6. Run the presentation file

---

### **Contributors**
- **Arwa Abu rub**
- **Marh almutairi**
- **Layan Albar**

---

### **Acknowledgments**
This project was developed as part of a Data Science course CS3072. Special thanks to the professor, Dr Zain and classmates for their feedback and support.

---

### **License**
This project is licensed under the MIT License. Feel free to use or modify it for educational purposes.
