![POSTER_IR_Spec-Viz](https://user-images.githubusercontent.com/106185720/234980934-2c4c864b-677f-4ba6-8759-5ad6ae5efd3c.png)

# iR-BioSpecViz
This tool visualizes Infrared spectroscopy data, formats &amp; normalizes raw data for efficient biomolecular analysis, &amp; provides meaningful FTIR spectra visualizations in R.

# CSV Processing Script
This script processes multiple CSV files and performs the following operations:

- Remove the first two lines from each file
- Merge the files into one file
- Add a prefix and suffix to each line of each file
- Add a first line to each file

## Prerequisites
- Python 3.x
- Unix-like operating system (such as Linux or macOS)

## Usage
- Place the CSV files to be processed in the same directory as the script
- Run the script using a terminal or command prompt
- The processed files will be saved with the `output_` prefix

## Note
- This script uses the `os` module to run shell commands, so it may not work on Windows without modifications.
