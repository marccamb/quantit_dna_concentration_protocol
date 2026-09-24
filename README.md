# Quarto notebook for data analysis of Quant-it DNA concentration data

This repository contains a Quarto document with wet lab protocol and R scripts to analyze data obtained from an Omega FLUOstar Omega (BMC Biotech) plate reader, and Quant-it dsDNA High Sensitivity kit (ThermoFisher).

### 1. Downloading the repository

- If you have access to a terminal, and git is installed on your computer, clone the repository using `git clone git@github.com:marccamb/quantit_dna_concentration_protocol.git`
- If you don't have a terminal or do not use git, click on the "< > Code" button, then download and exctract the ZIP repository.

### 2. Data preparation

- All your data files are in the `data` directory
    - Create one folder per date of measurement, so that the plate with standards and those measured at the same time are in the same folder.
- Each file contains in its name `plate1` with the number of the plate and no space
- The plates containing standards contain `standard` in the the fluorescence file name in addition to the plate number.
    - Example:
        - `231204_standard_plate1.csv` for a plate containing both standards and samples
        - `231204_plate2.csv` for a plate that contains only samples

### 3. Editing the Quarto document

Simply open the `estimate_DNA_concentration_Quantit.qmd` file and follow the instructions. When your data is ready and the code is running, render the Quarto document (usually with ctrl+shift+K, but can depend on your IDE).

### Example

The repository contains an example dataset. You can open `estimate_DNA_concentration_Quantit.qmd` and render it to produce an HTML output with the example data. 

### Note on working directory

Since we are using relative paths, don't forget to check your working directory! If you use RStudio instead of Positron, it might be worth creating an Rproject to avoid having to think about it. 