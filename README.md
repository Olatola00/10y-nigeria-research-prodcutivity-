### Nigeria Research Productivity Analysis

This repository contains the data and code for a Master's thesis on Nigeria's research productivity. The project analyzes scholarly publication trends and collaboration dynamics from 2014 to 2023, using a dataset compiled from the Scopus database. The contents are designed to be fully transparent and reproducible.

-----

### Repository Contents

  * **`data/`**: This directory is structured to maintain data integrity and reproducibility.
      * `raw/`: Contains the original, unprocessed CSV files downloaded from Scopus.
      * `processed/`: Holds the cleaned and transformed dataset used for the analysis.
      * `country-file/`: Holds the cleaned and transformed dataset used for the analysis.
  * **`notebooks/`**: This folder contains the Jupyter notebooks used for the entire research process.
      * `Msc Proj Final Collection&Cleaning.ipynb`: Details the data acquisition, merging, and cleaning steps. It serves as a transparent pipeline for preparing the raw data for analysis.
      * `Msc proj - Analysis.ipynb`: Contains the core analysis and visualizations, including publication trends, disciplinary distribution, and an exploration of authorship patterns.
  * `LICENSE.md`: The full text of the Creative Commons license for the dataset.
  * `CITATION.cff`: A file with machine-readable citation information for this repository.
  * `README.md`: The project overview and guide you are reading now.

-----

### How to Reproduce the Analysis

This project is designed to be fully reproducible.

1.  **Clone the Repository:**
    ```sh
    git clone https://github.com/your-username/nigeria-research-productivity.git
    cd nigeria-research-productivity
    ```
2.  **Dependencies:** Ensure you have the required libraries installed. You can install them using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebooks:**
      * Start with `Msc Proj Final Collection&Cleaning.ipynb` to process the raw data.
      * Then, run `Msc proj - Analysis.ipynb` to execute the analysis and generate the visualizations.

-----

### The Thesis

The research presented here is the foundation for the Master's thesis:

*"A Quantitative Analysis of Scholarly Productivity in Nigeria: A Scopus-Based Study on Publication Trends and the Applicability of Lotka's Law"*
by Oladotun Oguntola
Department of Data and Information Science, University of Ibadan, Nigeria
[Year]

**DOI:** [Insert DOI of your thesis here]

-----

### The Dataset

The **"Nigeria Research Productivity from 2014-2023"** dataset is a key output of this project. It is permanently archived on Zenodo for long-term preservation and citation.

**DOI:** [Insert DOI of your Zenodo dataset here]

-----

### License

The code in this repository is distributed under the MIT License.
The dataset is licensed under a **[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

-----

### Citation

If you use this dataset or code in your research, please cite the work as described in the `CITATION.cff` file.
