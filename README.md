# Chemistry Thesis Code

## Introduction

This repository contains the code for my Chemistry Thesis. The code is written in a Google Colab notebook (ChemistryThesisCode.ipynb). To run the notebook successfully, please follow the instructions below.

## Getting Started

1. Clone the Repository
   ```bash
   git clone https://github.com/hg8055/Chemistry-Thesis.git
```

2. Upload Dataset to Google Drive
   - Upload the dataset.xlsx file to your Google Drive.

3. Open Colab Notebook
   - Open the ChemistryThesisCode.ipynb notebook using Google Colab.

4. Mount Google Drive
   - Run the following code in the Colab notebook to mount your Google Drive:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

5. Set the Dataset Path
   - Locate the cell with the pd.read_excel command and update the file path to the dataset:
     ```python
     # Update the file path
     df=pd.read_excel(r'Add Path to the Dataset from the drive')
     ```

## Running the Notebook

Run the entire Colab notebook after setting the dataset path.

## Additional Notes

- Make sure you have the necessary libraries installed by running the installation cells in the notebook.
- Adjust any other parameters or settings according to your requirements.

## Files

- ChemistryThesisCode.ipynb: The main Colab notebook containing the code for the Chemistry Thesis.
- dataset.xlsx: The dataset required for running the code.
