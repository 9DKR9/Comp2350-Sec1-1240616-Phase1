# Automatic vs. Manual Cars

## Student Information
- **Name:** Saleh Zahran
- **Student ID:** 1240616

## Selected Topic and Dataset
- **Topic:** Automatic and manual cars over time.
- **Dataset:** `cars.csv`, containing 56,244 car records and 12 columns.
- **Main columns:** `year` and `transmission`.
- **Transmission types:** `auto` (automatic) and `mechanics` (manual).
- **Dataset source:** [Data Science Projects — asabbah44](https://github.com/asabbah44/Data-Science-Projects.git)

## Project Description
This project studies how the share of automatic cars changes across manufacturing years in the selected dataset. It compares automatic and manual cars to explore patterns over time.

## Project Objective
The growth rate of automatic cars over time.

The analysis will use manufacturing year to calculate the percentage of automatic cars in each year and its year-to-year relative change within the dataset.

## Repository Structure
- `README.md`: Project information and instructions.
- `data/cars.csv`: Selected dataset.
- `notebooks/phase1.ipynb`: Project notebook.
- `requirements.txt`: Required Python packages.
- `.gitignore`: Files and folders excluded from Git.

## How to Run the Notebook
1. Download or clone the repository.
2. Open a terminal in the project folder and create a Python environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install the required packages:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `notebooks/phase1.ipynb`, select the environment's Python kernel, and run the cells from top to bottom.
