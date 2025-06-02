# State Analysis Automation (Google Colab Project)

This project replicates the OUTPUT tab from the "Analysis of States" Google Sheet using Python in Google Colab.  
It automates the process of merging, cleaning, and transforming state-level data from US Census and Redfin sources, and generates a CSV output that matches the required format.  
Bonus: sample visualizations are included.

## Files Included

- `state_analysis_colab.ipynb` — Main Google Colab notebook containing all code and outputs.
- `output.csv` — Final processed dataset matching the required OUTPUT structure.
- (Optional) Plot image files if included (e.g., `income_vs_price.png`).

## How to Run

1. **Open the notebook** in [Google Colab](https://colab.research.google.com/).
2. **Upload the following datasets** when prompted:
    - `CENSUS_MHI_STATE.csv`
    - `CENSUS_POPULATION_STATE.tsv`
    - `KEYS.csv`
    - `REDFIN_MEDIAN_SALE_PRICE.csv`
3. **Run all cells** in order.  
   The notebook will:
   - Read and process the data
   - Merge and clean datasets
   - Perform calculations and ranking
   - Output `output.csv`
   - (Optionally) Create and save sample plots

4. **Download the `output.csv` file** (and plot images, if desired) from the Colab environment.

## Requirements

- Python 3.x
- pandas
- matplotlib

*(All requirements are pre-installed in Google Colab)*

## Notes

- The notebook is self-contained and documented for clarity.
- Instructions for data upload and output download are included in the notebook cells.
- The workflow follows the assignment instructions step by step.

## Author

Maryann Atakpa


