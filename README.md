# ADOT Traffic Data Repository

This repository contains traffic volume data originally provided by the Arizona Department of Transportation (ADOT), available at:  
[https://azdot.gov/planning/data-and-information/traffic-monitoring](https://azdot.gov/planning/data-and-information/traffic-monitoring)

## Repository Structure

- **`raw_datafiles/`**  
  Contains all original documents manually downloaded from the ADOT website. You may also download these files directly from the ADOT website using the link above.

- **`ADOT_Filtered_Data/`**  
  Includes the filtered and cleaned traffic data required for this project. The data corresponds to locations surrounding long-term ecological research (LTER) study sites.

- **`ADOT.ipynb`**  
  A Jupyter Notebook containing the Python code used for data extraction and filtering using the `pandas` library.

- **`ADOT-pandas.pdf`**  
  A PDF version of the notebook for convenient offline viewing and sharing.

## How to Use

1. Review the `raw_datafiles/` folder for original datasets or download new files from the ADOT website.
2. Open `ADOT.ipynb` to modify paths, site IDs and column names as needed.
3. Run the notebook to extract and filter traffic data for your specific use case.

