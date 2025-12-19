# Heart Disease Analysis Dashboard

[![PowerBI](https://img.shields.io/badge/powerbi-%23F2C811.svg?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/desktop/) [![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)

An interactive PowerBI dashboard designed to analyze heart disease data, offering comprehensive insights into patient demographics, risk factors, and health outcomes. This project leverages data visualization techniques to facilitate informed decision-making in healthcare analytics.

## Goal

The goal of the Heart Disease Analysis Dashboard is to provide an interactive platform for analyzing heart disease data, offering comprehensive insights into patient demographics, risk factors, and health outcomes. By leveraging data visualization techniques, it aims to facilitate informed decision-making in healthcare analytics, enabling better understanding of cardiovascular health patterns and supporting preventive measures.



## Table of Contents

- [Goal](#goal)
- [Author](#author)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Screenshots](#screenshots)
- [Insights](#insights)
- [Project Impact](#project-impact)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Features

- **Interactive Visualizations**: Explore data through dynamic charts, graphs, and filters.
- **Demographic Analysis**: Compare insights across gender, age groups, and other demographics.
- **Risk Factor Assessment**: Identify key indicators such as cholesterol levels, blood pressure, and lifestyle factors.
- **Predictive Analytics**: Utilize built-in models for outcome predictions.
- **Export Capabilities**: Generate reports and share findings easily.

## Technologies Used

- **PowerBI Desktop**: Primary tool for building the interactive dashboard, creating visualizations, and performing data analysis.
- **Microsoft Excel**: Used for dataset management, storage, and initial data cleaning.
- **DAX (Data Analysis Expressions)**: Employed within PowerBI for creating calculated columns, measures, and advanced analytics.
- **Power Query**: Utilized for data transformation and connection to the Excel dataset.

## Prerequisites

- **PowerBI Desktop**: Version 2.100 or later (free download from [Microsoft PowerBI](https://powerbi.microsoft.com/desktop/)).
- **Microsoft Excel**: For viewing or editing the dataset (optional).

## Installation

1. Clone or download this repository to your local machine.
2. Ensure PowerBI Desktop is installed on your system.
3. No additional setup is required; the dashboard is self-contained.

## Usage

1. Launch PowerBI Desktop.
2. Open the `Heart disease analysis.pbix` file from the project directory.
3. Interact with the dashboard:
   - Use filters to segment data by age, gender, or other attributes.
   - Hover over visualizations for detailed tooltips.
   - Export reports as PDF or PowerPoint for presentations.
4. Refer to the included image files (`Heart Disease Female Insights.png` and `Heart Disease Male Insights.png`) for quick visual summaries.

## Dataset

The dataset (`Heart_Disease_Dataset.xlsx`) is sourced from publicly available heart disease research data. It includes the following key attributes:

- **Demographics**: Age, Gender, Ethnicity
- **Clinical Measurements**: Cholesterol levels, Blood pressure, BMI
- **Health Indicators**: Smoking status, Exercise habits, Family history
- **Outcomes**: Diagnosis results, Treatment responses

**Note**: Ensure ethical use of data; this is for educational and analytical purposes only.

## Screenshots

### Female Insights
<img src="Heart Disease Female Insights.png" alt="Heart Disease Female Insights" width="5000">
*Overview of heart disease patterns and risk factors specific to female patients.*

- Women often present with atypical symptoms such as shortness of breath, nausea, and fatigue, rather than chest pain.
- Higher emphasis on HDL ("good") cholesterol levels, as low HDL is a stronger predictor in females.
- Age-related trends show increased risk post-menopause due to hormonal changes.
- Lifestyle factors like stress and depression play a notable role in female heart disease.

### Male Insights
<img src="Heart Disease Male Insights.png" alt="Heart Disease Male Insights" width="5000">
*Comparative analysis highlighting trends and outcomes for male patients.*

- Traditional symptoms like chest pain and left arm discomfort are more common in men.
- Smoking and high LDL cholesterol are leading risk factors, with men showing higher prevalence rates.
- Occupational stress and sedentary lifestyles contribute significantly to male cardiovascular issues.
- Earlier onset compared to females, with peak incidence in middle age.

## Insights

- **Gender Disparities**: The dashboard reveals significant differences in risk factors between male and female cohorts, aiding in targeted healthcare strategies.
- **Key Risk Factors**: Elevated cholesterol and hypertension are prominent across demographics.
- **Outcome Predictions**: Interactive models provide probabilistic forecasts based on input parameters.
- **Trend Analysis**: Visualize temporal changes in disease prevalence and recovery rates.

For deeper analysis, dive into the PowerBI report's advanced features like drill-down and cross-filtering.

## Project Impact

This dashboard has significant implications across various domains:

- **Healthcare Decision-Making**: Empowers medical professionals with actionable insights for personalized patient care, early intervention, and preventive measures against heart disease.
- **Educational Value**: Acts as an interactive learning resource for students, researchers, and educators to understand complex health data patterns and statistical relationships.
- **Policy and Public Health**: Informs policymakers about demographic trends, enabling the development of gender-specific health policies, resource allocation, and public health campaigns.
- **Public Awareness**: Increases community awareness of heart disease risk factors through intuitive visualizations, promoting healthier lifestyles and proactive health management.
- **Research Advancement**: Facilitates data exploration for ongoing studies, potentially leading to new discoveries in cardiovascular health.

## Contributing

We welcome contributions to enhance this dashboard!

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Alternatively, report issues or suggest improvements via the repository's issue tracker.

## Credits

### Data Credits
**Dataset Credit**: Heart Failure Clinical Records – UCI Machine Learning Repository
**Authors**: Davide Chicco and Giuseppe Jurman
**Source**: https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records
**License**: Creative Commons Attribution 4.0 International (CC BY 4.0) – https://creativecommons.org/licenses/by/4.0/
**Citation**: Chicco, D., & Jurman, G. (2020). Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making, 20(1), 1-16.

### Image Credits
🎨 **Image Credit**: Image by Freepik – https://www.freepik.com/free-psd/3d-rendering-realistic-heart_344840361.htm

🎨 **Icon Credit**: Icon by Flaticon - Author: Sudowoodo
📌 https://www.flaticon.com/free-icon/person_13482183
📌 https://www.flaticon.com/free-icon/avatar_13482193

## Author

🏁 Created by: Aditi Sah
📧 aditisah946@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Intended for educational use; please adhere to data privacy regulations when handling sensitive health information.
