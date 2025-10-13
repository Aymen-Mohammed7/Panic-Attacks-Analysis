# Panic Attacks Awareness Analysis

This case study presents an analysis on **Panic Attack** cases using demographic, clinical, and lifestyle data to uncover insights that support awareness campaigns through an interactive Power BI dashboards.

---

## Business Task

**Develop an interactive Power BI report** that helps a non-governmental organization (NGO) raise awareness about panic attacks and their contributing factors.  
The goal is to identify patterns across demographics, clinical conditions, and lifestyle choices to guide public health initiatives and improve understanding of mental well-being.

---

## Tools Used

- **Snowflake:** As the data storage and connection
- **Power Query:** For data ingestion, cleaning, and transformation
- **Power BI:** For building DAX measures & tables and developing interactive dashboards
- **Git & GitHub:** For version control and project documentation

---

## Project Structure

| Folder        | Description                                      |
|---------------|--------------------------------------------------|
| `powerbi/`    | Power BI `.pbix` file and dashboard screenshots  |
| `data/`       | Data files used in the analysis                  |
| `README.md`   | Project documentation and findings               |
| `LICENSE`     | MIT License file                                 |

---

## Data Source

- **Dataset Type:** Synthetic dataset simulating real-world panic attack data 
- **Purpose:** For analytical and educational uses
- **Connection:** Dataset uploaded to **Snowflake** and connected to **Power BI**

---

## Data Cleaning & Transformation

- Corrected column data types to ensure accuracy
- Checked for nulls and errors
- Added custom and conditional columns to group and categorize data for clearer analysis
- Replaced certain values to improve data clarity and understanding
- Created key metrics and tables using DAX expressions to power the visuals

---

## Dashboards & Visualization

The Power BI report is presented through **three main dashboards**, each designed to deliver an interactive and insightful exploration of the panic attack dataset:

### 1. Overview Dashboard
This dashboard provides a high-level summary of the panic attack cases.

**Key Visuals & Metrics:**
 - **KPI Cards:** Total Cases, Severe Cases, Treatment Gap, Most Common Trigger, and Average Panic Score
 - **Cases by Trigger Reason:** Stress, Social Anxiety, Caffeine, Phobia, and PTSD are the primary known triggers
 - **Cases by Age Group:** Shows the distribution of cases across Youth (18-24), Adults (25-35), Middle-aged (36-50), and Seniors (50+)
 - **Case Distribution:** Visualizes the breakdown of cases by gender and severity level (Low, Moderate, Severe)

**Dashboard Preview:**

![Overview Dashboard Screenshot](powerbi/overview-dashboard.png)

### 2. Clinical Insights Dashboard
This dashboard focuses on the clinical aspects of the panic attack cases, including symptoms and medical history.

**Key Visuals & Metrics:**
 - **KPI Cards:** Priority Cases, Multi Symptoms Cases, Average Heart Rate, Average Panic Duration, and Average Panic Frequency
 - **Symptom Frequency:** Displays the most common symptoms, such as Sweating, Shortness of Breath, and Dizziness
 - **Panic Symptoms by Severity:** A Sankey diagram showing the flow from medical history to symptom to severity level
 - **Treatment Adoption:** Compares the adoption rates of Therapy vs. Medication
 - **Cases by Medical History:** Breaks down cases based on pre-existing conditions like Anxiety, Depression, and PTSD

**Dashboard Preview:**

![Clinical Insights Dashboard Screenshot](powerbi/clinical-insights-dashboard.png)

### 3. Lifestyle Impact Dashboard
This dashboard explores the relationship between lifestyle factors and panic attack severity.

**Key Visuals & Metrics:**
 - **KPI Cards:** Highlights counts of individuals with high caffeine intake, low sleep, low exercise, high alcohol consumption, and smokers
 - **Panic Severity by Sleep Hours:** Shows a correlation between average sleep hours and the severity of panic attacks
 - **Panic Score by Alcohol Consumption:** Visualizes how the average panic score varies with alcohol intake
 - **Caffeine Intake vs. Panic Score:** A scatter plot showing the relationship between caffeine consumption and panic scores, segmented by trigger
 - **Panic Score by Exercise Frequency:** Illustrates how often individuals exercise correlates with their panic score

**Dashboard Preview:**

![Lifestyle Impact Dashboard Screenshot](powerbi/lifestyle-impact-dashboard.png)

### 4. Filters Panel
Added to each page for interactive data exploration, and personalized insights.

*Power BI file:* [Panic Attack Analysis](powerbi) or [Download from Google Drive](https://drive.google.com/file/d/1FRow2m7r3SgTR59zlJtXMYJ6HnDsM3h1/view?usp=sharing)

---

## Key Insights for Campaign Strategy

- **Overview Dashboard:**
  - 479 people with severe panic scores (≥7/10) and that is nearly 1 in 3 people
  - 17% of cases have unknown triggers - highlighting the critical need for awareness
  - 243 individuals with severe panic scores are not receiving therapy
  - 403 of total cases are middle-aged people (36-50 years) and they represents 33%

- **Clinical Insights Dashboard:**
  - 134 individuals with severe panic scores are neither receiving therapy nor medication
  - 697 cases have multiple symptoms (≥3/5) 70% experience sweating, 62% shortness of breath
  - 595 people not reciving therapy and 700 not taking medication
  - 41% of cases have anxiety as medical history (492 cases)

- **Lifestyle Impact Dashboard:**
  - 325 smokers (27% of population)
  - 474 individuals have a low sleep frequency (< 6 hours)
  - People with severe panic score consume alcohol more than the average (>4.42 times/week)
  - 413 cases take high caffeine amounts (>3 cups/day)
  - 368 people have a low exercise frequency (<2 times/week)

---

## License

This project is licensed under the [MIT License](LICENSE)

---

## Author

**Aymen Mohammed** — Data Analyst passionate about using data to tell stories and drive business decisions.

 [![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=about.me&logoColor=white&style=flat)](https://aymenmohammed.netlify.app/)
 [![Linkedin](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayman-muammer)
 [![GitHub](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white&style=flat)](https://github.com/Aymen-Mohammed7)
