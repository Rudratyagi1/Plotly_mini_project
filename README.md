

## Overview
It is a Streamlit-based application designed for visualizing data across different states and districts in India. Users can explore a dataset of various parameters, compare data between different states or the entire country, and view visualizations on an interactive map.

## Features
- Select and visualize data for specific states or "Overall India."
- Choose primary and secondary parameters for the visualization.
- Generate an interactive map visualization using Plotly's scatter mapbox.
- View information based on location, with map markers sized and colored according to selected parameters.

## Installation

### Prerequisites
Make sure you have Python installed. This project requires Python 3.6 or higher.

1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2. Navigate into the project directory:
    ```bash
    cd <project_directory>
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Usage
1. Place the `india.csv` data file in the project directory.
2. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
3. Access the app in your browser at `http://localhost:8501`.

## Data File
- The application expects a CSV file (`india.csv`) containing data on Indian states and districts.
- The file should include columns named `State`, `District`, `Latitude`, `Longitude`, and other parameters that can be used for visualization.

## Example Usage
- Select a state or "Overall India" from the sidebar.
- Choose a primary and a secondary parameter to compare.
- Click "Plot Graph" to generate an interactive map displaying district-level data.

## Libraries Used
- [Streamlit](https://streamlit.io/) for app development.
- [NumPy](https://numpy.org/) for numerical operations.
- [Pandas](https://pandas.pydata.org/) for data manipulation.
- [Plotly](https://plotly.com/python/) for interactive map visualizations.

## License
This project is licensed under the MIT License.
