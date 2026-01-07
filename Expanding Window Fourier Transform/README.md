# Expanding Window Fourier Transform

This repository contains scripts, notes, and data for calculating Fourier spectra using the approach described in the Supplementary Information.
---

# 1. Overview

This repository contains the analysis pipeline used for RNAseq Analysis.  
It includes:

1. Expanding Window Fourier Transform.ipynb — Python notebook for Fourier analysis


---

# 2. Requirements

You need:

- Python coding environment

The script accepts a Pandas dataframe with columns 'time','fret',and 'fov'. 'time' represents a time point, 'fret' represents the FRET ratio at that time point, and 'fov' can represent a single field of view or a segmented cell, e.g. the output from the Single Cell Tracking Pipeline

Code is provided with a Brownian noise sine function as a demo example. Otherwise, point the path to the desired data set at line

#df = pd.read_csv('fret.csv')

Example output is shown in the script.
  
---

# 3. Installation

Code provided is not an executable and does not require installation. Load and execute code in Python coding environment.
 
---


# 4. Running Python code

Load Expanding Window Fourier Transform.ipynb into your Python coding environment to execute code.