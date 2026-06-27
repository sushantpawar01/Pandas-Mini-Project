# Pandas-Mini-Project
# Anime Dataset Feature Extraction

This mini-project demonstrates essential data cleaning and feature extraction techniques using Python and pandas. It processes a raw dataset of top-ranked anime, extracting specific metrics embedded within unformatted text columns to create a clean, analyzable dataframe.

## TechStack Used

* **Python 3**
* **pandas**
* **numpy**
* **python-dateutil**

---

## Core Operations

* **String Parsing:** Isolates numerical episode counts hidden within unformatted title strings.
* **Data Type Conversion:** Cleans and converts extracted string values into integers for numerical analysis.
* **Temporal Feature Engineering:** Extracts broadcast start and end dates from dense text blocks.
* **Duration Calculation:** Computes the total broadcast run-time in months for each anime using datetime libraries.
* **Exploratory Data Analysis (EDA):** Identifies highest-scoring shows, maximum episode counts, and the longest-running series.

---

## Dataset Structure

The project relies on an `anime.csv` file containing the following initial format:

| Column | Description |
| :--- | :--- |
| **Rank** | The overall ranking of the series. |
| **Title** | A concatenated string containing the title, format, episodes, dates, and members. |
| **Score** | The overall rating out of 10. |

By the end of the notebook, the dataset is expanded to include dedicated **Episodes**, **Total Time**, and **Months** columns.

---

## Setup and Execution

1.  Clone this repository to your local machine.
2.  Install the required dependencies via your terminal: `pip install pandas numpy python-dateutil`
3.  Ensure your `anime.csv` dataset is placed in the same directory as the notebook.
4.  Launch Jupyter Notebook or JupyterLab and open `FeatureExtraction.ipynb`.
5.  Execute the cells sequentially to view the step-by-step data transformations.
