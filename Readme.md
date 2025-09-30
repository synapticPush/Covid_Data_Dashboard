# COVID-19 Global Data Dashboard 📊

An interactive data visualization project presenting a global COVID-19 dataset. This dashboard was developed using Streamlit for the user interface and layout, with visualizations powered by Seaborn, Matplotlib, Plotly, and Folium for charts and mapping.

---

## Project Overview

This project was developed as a final assignment to showcase skills in data handling and visualization. It transforms raw COVID-19 data into a dynamic and easily understandable dashboard, providing users with powerful tools to explore key metrics, regional trends, and geographic spread.

---

## Project Structure

- **`app.py`**: The core Streamlit application file. It loads the `country_wise_latest.csv` dataset, handles data cleaning, and renders all the interactive components, plots, and the Folium map.
- **`country_wise_latest.csv`**: The primary dataset used for the project, containing country-level COVID-19 statistics.
- **`COVID19_Data_Viz_Assignment_01.ipynb`**: The Jupyter Notebook used for initial exploratory data analysis and to develop the Python script that generates the Streamlit app.
- **`assets/`**: A directory containing all the screenshots and supporting images used in this README.
- **`collab_preview.pdf`**: A PDF preview of the Jupyter Notebook, demonstrating the initial data exploration and development process.

---

## Live Dashboard & Notebook Links

- **Live Dashboard**: https://0xarchit-covid-dashboard.streamlit.app
- **Jupyter Notebook**: https://colab.research.google.com/drive/1eIEiwLE9tYK3zamSqN_xjee_nIBlVY38?usp=sharing

---

## Key Features

- **Global Metrics**: At-a-glance overview of global Confirmed cases, Deaths, Recovered cases, and the Case Fatality Rate.
- **Intuitive Filters**: The sidebar offers comprehensive controls to filter the data by country, WHO region, vaccination status, and various numeric ranges for case counts.
- **Data Export**: Easily download the filtered dataset as a CSV file for further analysis.
- **Interactive Visualizations**:
  - **Overview**: Key Performance Indicator (KPI) metrics and a paginated, sortable data table.
  - **Seaborn & Matplotlib**: Static plots illustrating regional trends, correlations between data points, and data distributions.
  - **Plotly**: Highly interactive charts including line, scatter, treemap, and funnel charts for deep-dive analysis.
  - **Folium Map**: A dynamic world choropleth map that visualizes confirmed cases by country. It includes interactive tools like search, tooltips, multiple basemaps, a minimap, and measurement controls.
- **Insights**: The dashboard automatically generates highlights, such as countries with the highest case fatality rates, top recovery rates, and fastest weekly growth.

---

## Getting Started

To run this project on your local machine, follow these simple steps:

1.  **Clone the repository** (if applicable) or ensure you have all the project files.
2.  **Install dependencies**:
    ```powershell
    pip install streamlit pandas numpy seaborn matplotlib plotly folium pycountry
    ```
3.  **Run the application**:
    Navigate to the project directory in your terminal and execute the following command:
    ```powershell
    streamlit run app.py
    ```
4.  A local URL will be provided. Open this URL in your browser to view the dashboard.

---

## Troubleshooting

- **Map Rendering**: The Folium map requires an active internet connection to download the necessary GeoJSON data. If you encounter an "Map data unavailable" error, check your network connection or firewall settings.
- **Country Names**: An internal mapping table is used to handle various country name formats. While this covers common variations, some specific names might not be recognized by the mapping service.

---

## Credits

This project was built with the invaluable support of the following libraries:

- **Streamlit**: For creating the web application.
- **Pandas** & **NumPy**: For efficient data manipulation and numerical operations.
- **Seaborn** & **Matplotlib**: For generating statistical and comparative plots.
- **Plotly**: For producing interactive and professional-grade charts.
- **Folium**: For creating the stunning geospatial visualizations.

---

_This project is a testament to my skills in data visualization and web application development. I hope you find it informative and easy to use._
