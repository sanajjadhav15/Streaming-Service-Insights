# 🎬 Streaming Service Insights

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly">
</div>

<div align="center">
  <h3>📊 Interactive Data Analytics Dashboard for Netflix Content Trends</h3>
  <p><em>Exploring streaming content patterns through comprehensive data visualization and analysis</em></p>
</div>

---

## 🚀 Overview

**Streaming Service Insights** is an interactive web-based analytics dashboard that explores the public Netflix titles dataset to surface content trends. Built with Python and Streamlit, this project demonstrates end-to-end data analysis capabilities—from data cleaning and exploration to creating compelling visualizations that tell the story behind streaming trends.

The dashboard covers content distribution, release patterns, genre frequency, duration patterns and country-wise contribution, making the data easy to explore through interactive visualizations.

## ✨ Features

### 🎯 Core Analytics
- **Content Type Filter**: Filter the dashboard by Movies or TV Shows
- **Interactive Visualizations**: Hover effects, zoom capabilities, and responsive charts
- **Multi-dimensional Analysis**: Time-series, categorical, and geographical insights
- **Modern UI/UX**: Clean, professional interface with intuitive navigation

### 📈 Key Insights Delivered
- Content distribution patterns and growth trends
- Genre frequency across titles
- Release year trends
- Global content contribution analysis
- Duration and format preferences

## 📊 Dashboard Sections

### 1. 📊 **Content Type Analysis**
- **Donut Charts**: Visual breakdown of Movies vs TV Shows distribution
- **Key Metrics**: Percentage splits and total content counts
- **Interactive Elements**: Click-to-filter functionality

### 2. 📅 **Content Over Time**
- **Time Series Analysis**: Monthly, yearly, and decade-wise content releases
- **Trend Identification**: Growth patterns and seasonal variations
- **Visual Formats**: Line charts and bar graphs for temporal insights

### 3. 🎭 **Genre Intelligence**
- **Top Genres**: Frequency analysis and rankings by number of titles
- **Category Insights**: Genre performance across different content types

### 4. ⏳ **Duration Analysis**
- **Movie Duration**: Average runtime analysis by genre
- **TV Show Seasons**: Episode count and series length patterns
- **Comparative Analysis**: Duration trends across categories

### 5. ⏱️ **Duration Distribution**
- **Runtime Patterns**: Histogram visualizations of content duration
- **Statistical Analysis**: Mean, median, and distribution insights
- **Format Comparison**: Movie vs TV show duration patterns

### 6. 🌍 **Country-Wise Contribution**
- **Production Analysis**: Bar charts of content by country
- **Geographic Visualization**: Interactive choropleth maps
- **Global Insights**: International content distribution patterns

## 📁 Dataset Information

**Source**: Public Kaggle dataset *Netflix Movies and TV Shows* (title catalogue), stored here as `data/netflix_cleaned.csv`.
<!-- TODO: add the exact Kaggle URL you downloaded the dataset from -->

**Size**: 8,807 titles, 16 columns. Titles were added to Netflix between January 2008 and September 2021.

**Key Attributes**:
- **Content Metadata**: Title, type, release year, duration
- **Classification**: Genre tags, country, rating
- **Temporal Data**: Date added and release year
- **Derived columns**: Numeric duration and unit, release decade, month added

**Cleaning**: Missing director, cast and country values are labelled "Unknown". Duration is split into a number and a unit (minutes or seasons), and release decade and month added are derived.

**Limitations**:
- The data is a **catalogue of titles only**. It contains **no user-level data** such as viewers, watch time, ratings by users or retention, so the dashboard describes content, not audience behaviour.
- Genres and countries are multi-valued: a title can appear under several genres or countries, so counts add up to more than the number of titles.
- The dataset ends in September 2021, so 2021 is a partial year.

## 🔎 Key Findings

Computed from `netflix_cleaned.csv`:
- **Movies make up 69.6% of titles** (6,131 movies vs 2,676 TV shows).
- **Release volume peaked in 2018** with 1,147 titles. In 2021 (a partial year) TV shows outnumber movies, 315 to 277.
- **Most frequent genre tags:** International Movies (2,752 titles) and Dramas (2,427) for movies; International TV Shows (1,351) for TV.
- **United States contributes the most titles (3,689),** followed by India (1,046) and the United Kingdom (804). 831 titles have no country listed.
- **Median movie runtime is 98 minutes,** and **67.0% of TV shows have only one season.**

## 🛠️ Tech Stack

### **Backend & Analysis**
- **Python 3.8+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing support

### **Visualization & Frontend**
- **Streamlit**: Web application framework
- **Plotly**: Interactive visualization library
- **Plotly Express**: Simplified plotting interface

### **Development Tools**
- **Jupyter Notebook**: Data exploration and prototyping
- **VS Code**: Primary development environment
- **Git**: Version control and collaboration

### **Deployment**
- **Streamlit Cloud**: Web deployment platform
- **Requirements.txt**: Dependency management

## 🚦 How to Run Locally

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
```

### Installation Steps

1. **Clone the Repository**
```bash
git clone https://github.com/sanajjadhav15/Streaming-Service-Insights.git
cd Streaming-Service-Insights
```

2. **Create Virtual Environment** (Recommended)
```bash
python -m venv venv
venv\Scripts\activate      # Windows
# source venv/bin/activate  # macOS / Linux
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the Application**
```bash
streamlit run app/app.py
```

5. **Access Dashboard**
Open your browser and navigate to `http://localhost:8501`

### Required Dependencies
```txt
streamlit>=1.28.0
pandas>=1.5.0
plotly>=5.15.0
numpy>=1.24.0
```

## 🌐 Live Demo

🔗 **[View Live Dashboard](https://streaming-service-insights.streamlit.app/)**

*Try the interactive dashboard with the content type filter and interactive charts*

## 🎯 Project Highlights

- **Interactive Design**: User-friendly interface with responsive layouts
- **Evidence-Based**: Findings above are computed directly from the dataset
- **Reproducible**: Dependencies listed in `requirements.txt`, exploration notebooks included in `notebooks/`
- **Deployed**: Live on Streamlit Cloud

## 👨‍💻 Author

**[Sanaj Jadhav]**
- 📧 Email: sanajjadhav77@gmail.com
- 💼 LinkedIn: [linkedin.com/in/sanaj-jadhav/](https://www.linkedin.com/in/sanaj-jadhav/)
- 🐱 GitHub: [@sanajjadhav15](https://github.com/sanajjadhav15)

---

<div align="center">
  <p><strong>⭐ If you found this project helpful, please consider giving it a star!</strong></p>
  <p><em>Built with ❤️ for data enthusiasts and streaming service analysts</em></p>
</div>
