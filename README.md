# Hydrogen thermal desorption rate calculation

The software enables calculation of hydrogen thermal desoprtion rate of hydrogen from the raw data files of hydrogen partial pressure measurement performed by thermal desorption spectroscopy (TDS). The raw data files can be obtained from TDS (beta) machine designed in Aalto University (https://www.youtube.com/watch?v=kphSr36HedE) or similar thechniques.

Quick guide:
1. Copy 'thermal_desorption_rate_calculation.ipynb' file to your computer.
2. Install dependencies listed in the requirements.txt file to your Python environment.
3. Open the 'thermal_desorption_rate_calculation.ipynb' file using Jupyter Notebook.
4. Specify the Input parameters in the second code block.
5. Run the code.
6. Select the raw measurement file via popup window for calculation.
7. Collect the output files (3 jpg files and one txt file).

The txt file contains three columns with temperature (K or <sup>o</sup>C, depending on input parameters settings), temperature corrected according to calibration procedure embeded into the software (K or <sup>o</sup>C, depending on input parameters settings), and hydrogen thermal desorption rate, respectively. NOTE: The temperature calibration works only for the heating rates 2, 4, 6, 8, 10, and 12 K/min. 
