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

1.  **Clone the Repository:**
    ```sh
    git clone https://github.com/your-username/nigeria-research-productivity.git
    cd nigeria-research-productivity
    ```
2.  **Dependencies:** Ensure you have the required libraries installed. You can install them using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Folder schema:** Set your working directory to “10y-nigeria-research-prodcutivity-” and create data, src subfolders. Create subfolders for data as shown below.

5.  **Run the notebooks in the src subfolder:**
      * Start with `A_Data_Collection.ipynb`, follow the files in alphabetical to process the raw data.
      * Finally, run `C_Main_Analysis.ipynb` to execute the analysis and generate the visualizations.

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
