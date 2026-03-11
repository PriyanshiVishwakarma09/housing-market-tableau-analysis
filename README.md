# Visualizing Housing Market Trends: An Analysis of Sale Prices and Features using Tableau

## 📌 Project Overview
In this project for ABC Company, the goal is to address challenges in understanding the factors that influence house prices and sales trends. By analyzing comprehensive housing data—including total sales by years since renovation, house age distribution by the number of bathrooms, bedrooms, and floors, and the impact of renovations on house age—the company aims to uncover key insights. 

Utilizing **Tableau** for this analysis, the objective is to visualize and interpret patterns in the housing market to inform strategic decisions, optimize pricing strategies, and enhance overall market competitiveness.

**Target Audience/Stakeholders:** Real estate analysts, marketing teams, and company executives.

---

## 🛠️ Technical Architecture & Skills
* **Skills & Technologies:** Data Analysis, Data Visualization, Tableau (Business Intelligence Software), Dashboarding, Flask (Web Framework).
* **Workflow:** 1. **Data Source:** Google Drive / Database 
  2. **Processing & Visualization:** Tableau
  3. **Web Integration:** Flask (embedding the Tableau dashboard into a web UI for end-users)

---

## 📊 Key Scenarios & Visualizations

### Scenario 1: Overall Data Overview
This visualization presents a summary of the dataset, showing the count of transformed housing data records, the average sales price, and the total basement area in square feet. It provides a quick snapshot of the dataset's scale and key metrics, giving stakeholders a foundational understanding of the data being analyzed.

### Scenario 2: Total Sales by Years Since Renovation
This histogram illustrates the distribution of total sales based on the number of years since a house was renovated. The bars represent different sales price bins, highlighting how recently renovated houses correlate with varying price ranges. This scenario helps stakeholders understand the impact of renovations on house prices and identify trends in buyer preferences for renovated homes.

### Scenario 3: Distribution of House Age by Renovation Status
This pie chart shows the distribution of houses based on their age and renovation status. Each segment represents a different age group, offering insight into how house age is spread across the dataset and the proportion of renovated versus non-renovated houses. This visualization assists in assessing the age characteristics of the housing inventory and the prevalence of renovations.

### Scenario 4: House Age Distribution by Number of Bathrooms, Bedrooms, and Floors
This grouped bar chart displays the distribution of house ages categorized by the number of bathrooms, bedrooms, and floors. It shows how houses of different ages are distributed according to these attributes, offering a detailed view of how house features vary with age. This scenario helps stakeholders identify patterns in housing characteristics and preferences related to house features over time.

---

## 👥 Team Members & Contributions

The project was divided into key epics and tasks, distributed among the team members as follows:

* **Priyanshi Vishwakarma (Team Lead)**
  * **Data Collection:** Collected and loaded the dataset from the database.
  * **Data Preparation:** Handled data cleaning.
  * **Data Visualization:** Created the initial set of unique visualizations.
  * **Web Integration:** Handled the publishing phase.
  * **Documentation:** Created the step-by-step project development procedure and documentation.

* **Puspendar Chauhan (Member)**
  * **Dashboarding:** Designed and implemented a responsive dashboard.
  * **Storyboard:** Created the data storytelling framework and designed the storyboard.

* **Priyanshu Kumar (Member)**
  * **Performance Testing:** Monitored the amount of data loaded.
  * **Performance Testing:** Analyzed and optimized the number of visualizations and graphs used.

* **Priyanshu Tewatiya (Member)**
  * **Performance Testing:** Tested and optimized the utilization of data filters.
  * **Web Integration:** Embedded the Tableau dashboard and storyboard into the web UI using Flask.
  * **Demonstration:** Recorded the end-to-end explanation video for the final project solution.

---

## 🚀 Step-by-Step Development Procedure

This project was executed in a structured, agile workflow, broken down into the following key phases:

### Phase 1: Data Collection & Preparation
1. **Data Sourcing:** Gathered raw housing market data containing metrics such as sale prices, renovation years, and property features (bedrooms, bathrooms, floors, etc.).
2. **Database Extraction:** Safely loaded the dataset from the central repository/database into the analytics environment.
3. **Data Cleaning:** Processed the raw data to handle missing values, format inconsistencies, and outliers, ensuring high data quality for accurate Tableau visualizations.

### Phase 2: Data Visualization & Dashboard Design
1. **Visualization Creation:** Connected Tableau to the cleaned dataset and generated a series of unique, scenario-specific visualizations (histograms, pie charts, grouped bar charts) targeting key business questions.
2. **Dashboard Assembly:** Combined the individual visualizations into a cohesive, interactive Tableau dashboard.
3. **Responsive Design:** Ensured the dashboard layout was responsive and intuitive for various screen sizes, prioritizing user experience for non-technical stakeholders.

### Phase 3: Storyboarding
1. **Narrative Flow:** Designed a storyboard in Tableau to guide stakeholders through the insights logically—starting from a high-level overview down to specific granular features (like renovations vs. age).
2. **Insight Highlighting:** Added annotations and context to the storyboard to clearly communicate the impact of renovations and property features on market value.

### Phase 4: Performance Testing & Optimization
1. **Data Load Monitoring:** Tested the amount of data being loaded into Tableau to ensure dashboard responsiveness wasn't compromised by massive datasets.
2. **Filter Optimization:** Refined data filters to ensure real-time querying and interactions within the dashboard executed smoothly without lag.
3. **Visual Audit:** Evaluated the total number of visualizations and calculation fields, optimizing them to prevent rendering delays.

### Phase 5: Web Integration (Flask)
1. **Publishing:** Published the final Tableau dashboard and storyboard to Tableau Server/Tableau Public to generate embed codes.
2. **Flask Application:** Set up a lightweight Python Flask web application to serve as the front-end interface for the stakeholders.
3. **UI Embedding:** Embedded the Tableau dashboard and storyboard directly into the Flask UI, allowing seamless access without requiring users to log into Tableau directly.

### Phase 6: Project Demonstration & Documentation
1. **Documentation:** Compiled this comprehensive README and a detailed step-by-step guide of the methodology.
2. **Video Walkthrough:** Recorded an end-to-end explanation video demonstrating the final solution, dashboard interactivity, and web UI integration for client handover.
