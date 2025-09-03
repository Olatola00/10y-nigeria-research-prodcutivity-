### Nigeria Research Productivity Analysis

This repository contains the data and code for a Master's thesis on Nigeria's research productivity. The project analyzes scholarly publication trends and collaboration dynamics from 2014 to 2023, using a dataset compiled from the Scopus database. The contents are designed to be fully transparent and reproducible.

-----

### Repository Contents
* **`dashboard/`**: This folder contains the html file that presents an interactive dashboard base on the dataset.
* **`src/`**: This folder contains the Jupyter notebooks used for the entire research process.
      * `A_Data_Collection.ipynb`: Details the data acquisition steps and search queries used in Scopus.
      * `B1_Country_Extraction.ipynb`: Details the data cleaning and data transformation steps involved in preparing the countries data.
      * `B2_Institution_Extraction.ipynb`: Details data cleaning and data transformation steps involved in preparing the institutions data.
      * `B3_OECD_Discipiline_Categorization.ipynb`: Details the data transformation steps and the methodology for categorizing all the subjects areas in to only six disciplines per the OECD's 2015 Franscati Manual.
      * `C_Main_Analysis.ipynb`: Contains the core analysis and visualizations, including publication trends, disciplinary distribution, and an exploration of authorship patterns.
  * `LICENSE.md`: The full text of the Creative Commons license for the dataset.
  * `CITATION.cff`: A file with machine-readable citation information for this repository.
  * `README.md`: The project overview and guide you are reading now.

-----

### How to Reproduce the Analysis

**Important Note:** Due to the large size of the main datasets, the raw and processed data files are **not included** in this GitHub repository. The notebooks are designed to run in a Google Colab environment and assume the necessary data files are accessible within your Google Drive.

1.  **Clone the Repository:**
    ```sh
    git clone [https://github.com/your-username/10y-nigeria-research-prodcutivity-.git](https://github.com/your-username/10y-nigeria-research-prodcutivity-.git)
    cd 10y-nigeria-research-prodcutivity-
    ```
2.  **Dependencies:** Ensure you have the required libraries installed. You can install them using pip within your Colab environment:
    ```sh
    !pip install pandas numpy matplotlib seaborn
    ```
3.  **Prepare Your Data & Google Drive:**
    * You will need to acquire the raw Scopus data based on the queries described in `A_Data_Collection.ipynb`.
    * It is assumed that your data will be organized as follows in your Google Drive: `My Drive/Colab Notebooks/data/raw/` and `My Drive/Colab Notebooks/data/processed/`.
    * **Folder Schema Illustration:**
          ```sh
          My Drive/
          └── 10y-nigeria-research-prodcutivity-/  <-- This is your cloned repo folder
              ├── src/
              │   ├── A_Data_Collection.ipynb
              │   ├── B1_Country_Extraction.ipynb
              │   ├── B2_Institution_Extraction.ipynb
              │   ├── B3_OECD_Discipline_Categorization.ipynb
              │   └── C_Main_Analysis.ipynb
              ├── dashboard/
              │   └── index.html
              ├── data/  <-- You will create and manage this folder within Colab/Drive
              │   ├── scopus_exports/  <-- Your raw Scopus CSVs go here
              │   │   ├── export_by_year/
              │   │   └── export_by_subject/
              │   ├── scopus-country-region/
              │   ├── nigerian_institutions/
              │   └── processed/  <-- Cleaned data will be saved here by the notebooks
              ├── CITATION.cff
              ├── LICENSE.md
              └── README.md
          ```          
4.  **Run the Notebooks in Google Colab:**
    * Open the notebooks
    * Start with `A_Data_Collection.ipynb`.
    * Follow the files alphabetically (`B1_Country_Extraction.ipynb`, `B2_Institution_Extraction.ipynb`, `B3_OECD_Discipline_Categorization.ipynb`) to perform the data cleaning and transformation.
    * Finally, run `C_Main_Analysis.ipynb` to execute the analysis and generate the visualizations.

-----

### Dashboard

The interactive dashboard, located in the `dashboard/` folder, provides a user-friendly visualization of the key findings from the thesis.

**How to View the Dashboard:**

* **Directly:** Open the `index.html` file in the `dashboard/` folder directly in your web browser.
* **Via GitHub Pages:** You can deploy this static HTML application using GitHub Pages. Go to your repository settings on GitHub, navigate to "Pages," select the `main` branch, and choose the `/dashboard` folder as the source.
  
-----

### Citation

If you use this code in your research, please cite the work as described in the `CITATION.cff` file.
Oguntola o. (2025). Nigeria's Research Productivity : 2025 Thesis Final Code (1.0.0) [Python]. Zenodo. https://doi.org

### The Thesis

Oguntola, O. (2025). Trends in Research Productivity and Collaboration in Nigeria [Zenodo]. https://doi.org/10.5281/zenodo.16928471

-----

### The Dataset

Oguntola, O. (2025). Nigeria Research Production from 2014-2023 by institution by discipline by collaborating countries (v 1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.16928959

-----

### License

The code in this repository is distributed under the MIT License.
The dataset is licensed under a **[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

-----
