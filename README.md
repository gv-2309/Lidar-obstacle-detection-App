# LIDAR Obstacle Detection App

A visual web app built using **Streamlit** that processes LIDAR point cloud data from CSV files, identifies obstacles, clusters them, and categorizes them into danger zones based on proximity.



## Features

- Upload your own LIDAR CSV file **or** choose from 6 built-in test cases.
- Detects obstacles within a **10-meter radius** from origin (0,0,0).
- Categorizes obstacle points into:
  - High Danger: Distance < 3m
  - Medium Danger: Distance 3–6m
  - Low Danger: Distance 6–10m
- Automatically clusters nearby points (using DBSCAN).
- Visualizes everything on a 2D scatter plot with labels and danger zones.
- Built with Python, Pandas, Matplotlib, and Scikit-learn.

---

## Input Format

CSV file with no headers in this format:

---

## Hosted App:
Visit the live app here:
https://lidar-obstacle-detection-app.streamlit.app/

---

## Team Credits
Developed by Team-Mind_Mesh

Developers: Amrutha D, Vishnu V

College: REVA University, Bangalore







