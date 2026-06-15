# SpaceX-Falcon-9-First-Stage-Landing-Prediction-analysis.
Understanding the Space Launch Industry Landscape
# 🚀 SpaceX Launch Analytics Dashboard

An interactive data analytics project that explores SpaceX launch records using **Python, Folium, and Plotly Dash**.  
The project includes exploratory data analysis, geospatial visualization, and an interactive dashboard to analyze launch success trends in real time.

---

## 📊 Project Overview

This project analyzes SpaceX rocket launch data to uncover insights such as:

- Launch success rates across different sites  
- Relationship between payload mass and mission outcome  
- Booster version performance trends  
- Geographical distribution of launch sites  
- Proximity of launch sites to coastlines, cities, and infrastructure  

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on SpaceX launch data  
- Visualize launch sites using **Folium interactive maps**  
- Compute distances between launch sites and nearby landmarks  
- Build an interactive dashboard using **Plotly Dash**  
- Enable real-time filtering using dropdowns and sliders  

---

## 🛠️ Technologies Used

- Python 3.11  
- Pandas  
- NumPy  
- Folium  
- Plotly Express  
- Dash  
- Geopy  

---

## 📁 Project Structure


spacex-dash-app.py # Main Dash application
spacex_launch_geo.csv # Dataset with launch site coordinates
README.md # Project documentation


---

## 📌 Features

### 🌍 Folium Map Visualization
- Launch sites plotted on interactive maps  
- Circle markers and labels for each site  
- Distance calculations to coastline and nearby points  
- Polyline connections between launch sites and reference locations  

### 📊 Interactive Dashboard (Dash)
- Dropdown menu for selecting launch sites  
- Pie chart showing success vs failure rates  
- Payload range slider for filtering missions  
- Scatter plot showing payload vs success outcome  
- Booster version analysis using color encoding  

---

## 📈 Key Insights

- **KSC LC-39A** has the highest launch success rate  
- Launch sites are strategically located near coastlines  
- Medium payload ranges (≈3000–6000 kg) show higher success rates  
- Newer boosters (FT and B5) perform significantly better  
- Sites are far from cities but close to transport infrastructure  

---

## ▶️ How to Run the Project

### 1. Install dependencies
```bash
pip install pandas folium dash plotly geopy
2. Run the application
python spacex-dash-app.py
3. Open in browser
http://127.0.0.1:8051/
📸 Dashboard Preview



Pie chart (launch success vs failure)
Scatter plot (payload vs success)
Interactive filters (dropdown + slider)
📌 Example Questions Answered
Which site has the highest number of successful launches?
Which site has the highest success rate?
What payload range has the best performance?
Which booster versions are most reliable?
How does geography affect launch success?
🚀 Future Improvements
Add machine learning model for launch success prediction
Deploy dashboard on cloud (Render / AWS / Heroku)
Integrate live SpaceX API data
Improve geospatial analysis with heatmaps
👤 Author

Tari Atikpa
Data Science & AI Enthusiast
Machine Learning • Data Visualization • AI Systems

📜 License

This project is part of IBM Data Science / Coursera hands-on labs and is intended for educational purposes.
