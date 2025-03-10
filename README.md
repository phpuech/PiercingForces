# Automated Peak Detection and Smoothing for Force Curve Analysis

This script processes force curve data from tab-separated text files to detect peaks in deflection measurements over time in micropipette / piercing experiments. It applies an adaptive mean filter for signal smoothing and uses SciPy's find_peaks to identify significant deflection events. The results are visualized with Matplotlib and Seaborn, generating clear plots with labeled peaks. Additionally, processed data is saved in a structured format for further analysis.
