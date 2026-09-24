## Quarto notebook for data analysis of Quant-it DNA concentration data

This repository contains a Quarto document with wet lab protocol and R scripts to analyze data obtained from an Omega FLUOstar Omega (BMC Biotech) plate reader, and Quant-it dsDNA High Sensitivity kit (ThermoFisher).

## Downloading the repository

- If you have access to a terminal, and git is installed on your computer, clone the repository using `git clone git@github.com:marccamb/quantit_dna_concentration_protocol.git` in a terminal
- If you don't have a terminal or do not use git, click on the "< > Code" button, and download and exctract the ZIP repository.

## Data preparation

Make sure that:

- All your data files are in the data directory
- Create one folder per date of measurement, so that the plate with standards and those measured at the same time are in the same plate.
- Each file contain in its name plate1 with the number of the plate and no space
- The plates containing standard samples contain standard in the the fluorescence file name in addition to the plate number.

**Example:**

- `231204_standard_plate1.csv` for a plate containing both standards and samples
- `231204_plate2.csv` for a plate that contains only samples

## Example

The repository contains an example dataset 