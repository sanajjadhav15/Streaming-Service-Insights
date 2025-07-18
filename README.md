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

**Streaming Service Insights** is an interactive web-based analytics dashboard that transforms Netflix's vast content library into actionable insights. Built with Python and Streamlit, this project demonstrates end-to-end data analysis capabilities—from data cleaning and exploration to creating compelling visualizations that tell the story behind streaming trends.

The dashboard provides stakeholders with comprehensive insights into content distribution, release patterns, genre preferences, and global production trends, making complex data accessible through intuitive visualizations.

## ✨ Features

### 🎯 Core Analytics
- **Real-time Filtering**: Dynamic content type filtering (Movies/TV Shows)
- **Interactive Visualizations**: Hover effects, zoom capabilities, and responsive charts
- **Multi-dimensional Analysis**: Time-series, categorical, and geographical insights
- **Modern UI/UX**: Clean, professional interface with intuitive navigation

### 📈 Key Insights Delivered
- Content distribution patterns and growth trends
- Genre popularity and audience engagement metrics
- Production timelines and release strategies
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
- **Top Genres**: Frequency analysis and popularity rankings
- **Engagement Metrics**: User preference indicators
- **Category Insights**: Genre performance across different content types

### 4. 🔁 **Retention Analysis**
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

**Source**: Netflix Content Dataset (`netflix_cleaned.csv`)

**Key Attributes**:
- **Content Metadata**: Title, type, release year, duration
- **Classification**: Genre, country, rating information
- **Temporal Data**: Release dates and production timelines
- **Categorical Variables**: Content type, genre classifications

**Data Quality**: Pre-processed and cleaned dataset ensuring accuracy and consistency in analysis

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
cd streaming-service-insights
```

2. **Create Virtual Environment** (Recommended)
```bash
venv\Scripts\activate
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

*Experience the interactive dashboard with real-time filtering and dynamic visualizations*

## 🎯 Project Highlights

- **Interactive Design**: User-friendly interface with responsive layouts
- **Data-Driven Insights**: Evidence-based conclusions from comprehensive analysis
- **Professional Presentation**: Clean, modern dashboard suitable for stakeholder presentations
- **Scalable Architecture**: Modular code structure for easy maintenance and expansion
- **Performance Optimized**: Efficient data processing and visualization rendering

## 👨‍💻 Author

**[Sanaj Jadhav]**
- 📧 Email: sanajjadhav77@gmail.com
- 💼 LinkedIn: [linkedin.com/in/sanaj-jadhav/](https://www.linkedin.com/in/sanaj-jadhav/)
- 🌐 Portfolio: [sanajjadhav.me](https://www.sanajjadhav.me/)
- 🐱 GitHub: [@sanajjadhav15](https://github.com/sanajjadhav15)

---

<div align="center">
  <p><strong>⭐ If you found this project helpful, please consider giving it a star!</strong></p>
  <p><em>Built with ❤️ for data enthusiasts and streaming service analysts</em></p>
</div>