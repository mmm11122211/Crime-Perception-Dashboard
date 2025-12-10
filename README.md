# Crime Perception vs. Reality Dashboard

## Dashboard Overview
*An interactive analysis revealing the disconnect between media narratives and safety data.*

## 📄 Project Overview
This project investigates the gap between public perception of crime and actual FBI crime statistics over the last 20 years.

**Key Findings:**
* **The Perception Gap:** While 60% of Americans believe crime is rising, FBI data shows a downward trend over 20 years.
* **Demographic Disparities:** Hispanic populations are underrepresented in crime statistics (7%) compared to their population share (19%).

## 🛠️ Tools Used
* **Power BI (Power Query / M Language):**
  * Used `Table.Combine` to merge 5 separate offender ethnicity datasets into a master table.
  * Applied `Text.BeforeDelimiter` to parse inconsistent date formats.
  * Transformed data types (`Int64.Type`) for accurate statistical analysis.
  * *See `data_transformation_logic.m` for the full ETL code.*
* **Figma:** Designed the dashboard layout, background, and typography hierarchy.

## 📂 File Structure
* `data_transformation_logic.txt`: [**View the Power Query code**](./data_transformation_logic.txt) used to clean and transform the raw data.
* `crime_data_cleaned.csv`: [**View the clean dataset**](./crime_data_cleaned.csv) used to generate the visualizations.
* `Crime_Analysis_Report.pdf`: [**Read the full research paper**](./Crime_Analysis_Report.pdf) detailing the methodology, extended findings, and demographic context.
* `Dashboard_Full_Export.pdf`: [**Download the high-res dashboard**](./Dashboard_Full_Export.pdf) to see all visual details.
* `screenshots/`: Folder containing quick-view images for this README.
