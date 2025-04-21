# README

## **Data Preprocessing Overview**

1. **Date Parsing and Type Checking**  
   - Converted the `Date` column from string format to datetime format for proper temporal analysis.

2. **Missing Value Handling**  
   - The dataset was checked for missing values and confirmed to be complete.

3. **Duplicate Removal**  
   - No redundant or duplicate records were found in the dataset.

4. **Weekend and Weekday Annotation**  
   - Each row was labeled as either a "Weekday" or "Weekend" to capture potential traffic patterns influenced by the day type.

5. **Annual Traffic Visualization**  
   - Visualized the total inbound and outbound passenger volumes across 15 control points for each year.

---

## **Notes**

- The dataset spans exactly **two full years**, from **January 1, 2023** to **December 31, 2024**.

---

## **Planned Analytical Tasks**

1. **Passenger Segmentation via Clustering**  
   - Cluster travelers based on population composition across control points to identify behavioral patterns or latent groups.

2. **Forecasting Inbound and Outbound Passenger Flows**  
   - Build predictive models to estimate the number of people entering and leaving Hong Kong on a daily basis.

3. **Busy Period Classification**  
   - Develop a classification model to identify "busy days" at border control points, supporting early warnings and resource planning.