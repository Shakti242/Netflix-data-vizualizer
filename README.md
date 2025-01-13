# Visualize Data with QuickSight

## Project Overview
**Created by:** Shakti Patel  

### What is Amazon QuickSight?
Amazon QuickSight is a cloud-based BI tool from AWS used for creating interactive dashboards and visualizations. It integrates with various data sources, leverages ML for insights, scales serverlessly, and supports embedded analytics for applications, enabling data-driven decision-making.

---

## How I Used Amazon QuickSight
- **Dataset:** Netflix data stored in S3.
- **Visualizations Created:**
  - Release trends.
  - Genre breakdowns.
  - Comparison of Movies vs. TV Shows.

[![Final Visualization](https://github.com/Shakti242/Netflix-data-vizualizer/blob/main/Images/%20final.png)


- **Interactive Dashboard:** Built to showcase insights and explore patterns effectively.

---

## Project Steps

### 1. Upload Project Files to S3
![S3 Setup](https://github.com/Shakti242/Netflix-data-vizualizer/blob/main/Images/Datasetfile.png)
- Stored the dataset and `manifest.json` in an S3 bucket.
- Edited the `manifest.json` file to update the S3 URI of the dataset, ensuring correct references.

### 2. Create a QuickSight Account
- Created a free QuickSight account.
- Setup took only a minute.
- (https://github.com/Shakti242/Netflix-data-vizualizer/blob/main/Images/Quicksighrt%20dashboard.png)

### 3. Connect Dataset to QuickSight
- Linked S3 bucket to QuickSight through Datasets.
- `manifest.json` file served as a map, describing data locations and structure.

### 4. First Visualization
![Movies vs TV Shows Visualization](images/movies-vs-tvshows.png)
- **Chart Created:** Movies vs. TV Shows by Release Year.
- **Process:** Added Release Year to the Y-axis and grouped by Type (Movies or TV Shows).

### 5. Use of Filters
- Excluded data for releases before 2015.
- Focused on three specific genres released post-2015.

![Filtered Data Visualization](images/filtered-data.png)

### 6. Setting up a Dashboard
![Dashboard Example](images/dashboard-example.png)
- Rearranged visuals for better presentation.
- Exported the dashboard as a PDF for sharing.

---

## Key Takeaways
This project demonstrated the power of Amazon QuickSight for creating insightful visualizations. It also emphasized the importance of data cleaning in generating accurate analytics.
