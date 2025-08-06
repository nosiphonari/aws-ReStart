# Analyzing Netflix Catalog Trends with Amazon QuickSight📊

## Introduction

This project showcases how I used Amazon QuickSight, AWS's business intelligence and analytics service, to explore and visualize trends in Netflix's content catalog. It was a hands-on exercise in turning raw data into visual insights to support data-driven storytelling.

![Architecture](Images/architecture.png)

## What is Amazon QuickSight?
Amazon QuickSight is a scalable, serverless, machine learning-powered BI service built for the cloud. It enables users to create interactive dashboards and visualizations from various data sources quickly and with minimal setup.

## Project Overview

### 1. Setting Up S3 and Uploading Data
- **Dataset**: I used a dataset of Netflix’s catalog, which includes information about movies, TV shows, genres, release years, etc.
- **S3 Bucket**: I uploaded the dataset and a `manifest.json` file to an S3 bucket. The `manifest.json` file was crucial as it helped QuickSight locate and interpret the data correctly.

![Bucket Objects](Images/bucket.png) 

### 2. Creating an Amazon QuickSight Account
- Setting up a QuickSight account was straightforward, taking only a couple of minutes.
- I enabled QuickSight's access to the S3 bucket, allowing it to read the data stored in my S3 bucket.

![Quicksight](Images/quicksight.png) 

### 3. Connecting S3 to QuickSight
- **Dataset Connection**: I connected my S3 bucket to QuickSight by creating a new dataset, selecting S3 as the data source, and entering the S3 URL for the `manifest.json` file.
- The `manifest.json` file acted as a guide for QuickSight, ensuring accurate data interpretation and visualization.

![Connecting S3 to QuickSight](Images/s3tomanifest.png) 

### 4. Creating Visualizations
- **Visualization Process**: I started by dragging relevant fields into QuickSight's AutoGraph space to create my first visualizations.
- One of my initial visualizations depicted a breakdown of movies versus TV shows by release year.

![Creating Visualizations](Images/viz.png)

### 5. Using Filters for Specific Insights
- **Filters**: Filters allowed me to focus on specific subsets of data. For instance, I filtered out movies and TV shows released before 2015, honing in on more recent trends.
- This filtering process helped me create a more targeted visualization focusing on the most recent content.

![Using Filters](Images/filtering.png) 

### 6. Finalizing the Dashboard
- **Dashboard Setup**: I polished my visualizations by editing titles to ensure clarity and purpose.

![Finalizing the Dashboard](Images/dash.png)  

## Key Takeaways

1. **Ease of Use**: QuickSight is user-friendly and simplifies the data visualization process.
2. **S3 Integration**: Connecting S3 to QuickSight was straightforward with the help of a `manifest.json` file.
3. **Visualization Flexibility**: QuickSight offers flexible tools for creating a wide range of visualizations.
4. **Real-Time Insights**: This project has inspired me to explore real-time data visualization further.

## Conclusion 🚀

This project was an excellent opportunity to familiarize myself with Amazon QuickSight. The entire process, from setting up S3 and QuickSight to creating meaningful visualizations, took around 2 hours. Moving forward, I aim to deepen my understanding of data visualization, especially in the context of real-time data and storytelling.
