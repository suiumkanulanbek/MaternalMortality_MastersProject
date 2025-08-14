# MaternalMortality\_MastersProject

This repository contains the data analysis, visualizations, and reporting materials for my Columbia Journalism School master’s project on maternal mortality in the United States, with a focus on mental health–related deaths.

## Project Overview

The project investigates the high and often overlooked rates of pregnancy-related deaths due to mental health conditions in the U.S., including postpartum depression, substance use disorder, and other mental health complications. While maternal mortality has been widely reported on, deaths tied to mental health remain underexplored in mainstream coverage.

My reporting combines in-depth interviews with affected families, healthcare providers, and researchers, alongside analysis of publicly available datasets.

## Methodology

* **CDC Maternal Mortality Review Committees (MMRC)**:
  Primary dataset for causes, timing, and preventability of maternal deaths.

* **March of Dimes Maternity Care Deserts Data**:
  Accessed via the March of Dimes API; merged with U.S. Census Bureau data using GeoJSON and pandas to map counties with limited or no access to maternity care.

* **Maternity Vulnerability Index (Surgo Ventures)**:
  Accessed via API to identify counties at greater risk for poor maternal health outcomes.

* **ERASE-MM Community Vital Signs Project**:
  Partnered with the CDC; provided data on uninsured women and access to mental health care, shared by Professor Michael Kramer.

* **Additional Sources**:

  * U.S. Health Resources and Services Administration (HRSA)
  * American Board of Family Medicine
  * American Association of Birth Centers
  * Centers for Medicare and Medicaid Services (CMS)
  * National Center for Health Statistics
  * American Hospital Association

Data cleaning and analysis were done in **Python** using **pandas**, and visualizations were created with **matplotlib**, **GeoPandas**, and refined in **Adobe Illustrator**.

## Visualizations

The repository includes:

* Maps showing maternity care deserts
* Charts on timing of maternal deaths in relation to pregnancy
* Bar and pie charts on causes of maternal mortality
* State-level comparisons of access to care and uninsured rates

## Human Stories

The project also incorporates personal narratives gathered through direct outreach and research on **GoFundMe**, where many families raise money for healthcare expenses. These stories bring a human dimension to the systemic issues uncovered in the data.

## License

This project is for journalistic purposes. Please credit appropriately if reusing materials.
