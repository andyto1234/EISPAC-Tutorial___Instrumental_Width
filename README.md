# EIS Instrumental Width

A Python implementation and analysis of the EIS instrumental width function, comparing results with IDL reference data.

## Overview

This tutorial demonstrates how to:
- Read and analyze EIS instrumental width data from IDL SAV files
- Implement the `eis_slit_width` function in Python
- Compare Python and IDL results

## Key Features

- Loads instrumental width data computed by IDL's `eis_slit_width` function
- Implements the function in Python based on EIS Software Note #7
- Supports both 1" (slit_ind=0) and 2" (slit_ind=2) slits
- Uses 4-degree polynomial fitting for width variation across the CCD

## Usage

Open `main_instrumental_width.ipynb` in Jupyter Notebook/Lab and follow the step-by-step cells.

## Data

The tutorial includes `eis_width.sav` containing pre-computed instrumental width data from IDL.

## Reference

- EIS Software Note #7: Instrumental Width Documentation
- Original IDL function: `eis_slit_width.pro` by Peter Young