# power-bi-projects
This repository contains a number of Power BI projects (currently in progress). It currently contains reports using healthcare data, but will also contain projects using sales and financial data as well.

**NOTE: To interact with the reports, you must have [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) downloaded.**

## Table of Contents
- [Patient Admissions](#patientadmissions)
- [Patient Satisfaction](#patientadmissions)

## Patient Admissions
### Overview
This report provides an overview of patient admissions to several hospitals to identify patient characteristics and potential issues in hospital capacity. Key features include the drill-through capability in the 'Admissions over Time' chart and the slicer to view different hospitals or all of them at once.

The project folder also contains a DAX calculation that finds the most frequent condition in patients, as well as the research questions considered when analyzing the data.

### Data Sources
Data was downloaded from Kaggle and saved locally:
[Healthcare Dataset](https://www.kaggle.com/datasets/eduardolicea/healthcare-dataset)


## Patient Satisfaction
### Overview
This report provides an overview of patient satisfaction at a hospital to identify common issues faced by patients. Key features include the KPIs and the 'Feedback over Time' chart, which shows how different metrics compare to one another on a temporal scale.

The project folder also contains DAX calculations that determine the average satisfaction every week (creating a new column), the most frequent complaint, and the weeks that scored the highest average satisfaction and best wait time satisfaction. The folder also contains notes on the research questions considered when analyzing the data, as well as a solution to an error encountered when transforming the data.

### Data Sources
Data was downloaded from Kaggle and saved locally:
[Patient Satisfaction - Health System Dataset](https://www.kaggle.com/datasets/gabrielsantello/patient-satisfaction-health-system-dataset)
