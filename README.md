# **COVID-19 Forecasting & Data Analysis for Indian States**

## **Introduction**
COVID-19 is an infectious disease caused by the Coronavirus, biologically known as **Severe Acute Respiratory Syndrome Coronavirus 2 (SARS-CoV-2)**. The disease was first identified in **Wuhan, China, in December 2019** and has since spread worldwide. As of the time of this analysis, there were over **10 million confirmed cases** globally, resulting in **502,984 deaths**, according to Google.

This project focuses on analyzing and forecasting the COVID-19 situation in India. The study aims to:
- Identify the **most affected regions** in India.
- Examine **trends in confirmed cases, recoveries, and deaths**.
- Utilise **data visualization techniques** to understand the outbreak's progression.
- Provide **insights and forecasts** using statistical and machine learning approaches.

## **Dataset**
The project is based on **two datasets**, which contain:
 1. Day-wise records of COVID-19 cases across different Indian states.
 2. Feature columns such as confirmed cases, deaths, and recoveries.

> The datasets were preprocessed and analyzed to extract meaningful insights.

## **Technologies & Libraries Used**
The project was implemented using Python and various data science libraries:

| Library | Purpose |
|---------|---------|
| **Pandas** | Data manipulation and analysis |
| **Matplotlib** | Static, animated, and interactive visualisations |
| **Numpy** | Support for large, multi-dimensional arrays and matrices |
| **Seaborn** | Statistical data visualisation |
| **Plotly & Plotly Express** | Interactive plotting and graphing |
| **Folium** | Visualisation of geospatial data using interactive maps |
| **Scikit-learn (sklearn.metrics)** | Performance measurement for classification models |
| **Warnings** | Handling warning messages |
| **%matplotlib inline** | Magic function for inline plotting in Jupyter Notebook |

## **Project Workflow**
1. **Data Collection & Cleaning**
   - Loaded datasets and handled missing values.
   - Converted data types and ensured consistency.
2. **Exploratory Data Analysis (EDA)**
   - Used Matplotlib, Seaborn, and Plotly to visualise trends.
   - Created time-series graphs, heatmaps, and choropleth maps to highlight affected regions.
3. **Forecasting & Predictions**
   - Applied statistical models for COVID-19 case prediction.
   - Evaluated model performance using sklearn.metrics.
4. **Visualization & Insights**
   - Generated interactive dashboards to present findings.
   - Mapped high-risk zones using Folium.

## **Visualisation Samples**
    Here are some key visualizations from the analysis:
### 1. **COVID-19 Case Trends**

### 2. **Heatmap of Affected Regions**

### 3. **Forecasted Growth Curve**

    (For more visualizations, check the Jupyter Notebook in the repository.)

## **How to Run the Project**
**Prerequisites**

Ensure you have Python and Jupyter Notebook installed. You can install required dependencies using:
`pip install pandas numpy matplotlib seaborn plotly folium scikit-learn`

**Steps to Run**
 1. Clone the repository:
    > git clone https://github.com/yourusername/covid19-forecast-india.git
 2. Navigate to the project directory:
    > cd covid19-forecast-india
 3. Open the Jupyter Notebook:
    > jupyter notebook
 4. Run the notebook step-by-step to see the analysis and visualisations.

## **Project Files**
- datasets/ → Contains COVID-19 data files.
- covid19_forecasting.ipynb → Jupyter Notebook with full analysis.
- README.md → Project documentation.

## **Future Improvements**
- Integrating machine learning models for better forecasting.
- Expanding the dataset to include global COVID-19 trends.
- Deploying an interactive web dashboard for real-time updates.

If you find this project useful, please ⭐ star the repository! 😊

    


