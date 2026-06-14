# Yeast Replication Origin Simulation

## Overview
This notebook performs the simulation and analysis of replication origin positions across yeast chromosomes. Using genomic data, it generates random origin positions proportional to chromosome lengths, filters confirmed replication origins, calculates their midpoints and sizes, and compares observed and simulated data distributions through visualizations.

## Features
- Reads yeast replication origin and chromosome length data  
- Generates random replication origin positions per chromosome  
- Filters confirmed replication origins and computes region statistics  
- Simulates random origin points within confirmed regions  
- Visualizes distributions of both observed and simulated origins  

## Tech Stack
- Python  
- Jupyter Notebook / Google Colab  
- pandas  
- numpy  
- matplotlib  
- seaborn  

## How to Use
1. Clone or download this repository.  
2. Upload the notebook to Google Colab or open it in Jupyter Notebook.  
3. Ensure `cerevisiae-data.csv` and `chromosome_length.csv` are available in the working directory.  
4. Run the notebook cells sequentially to reproduce the analyses and visualizations.  

## Status
This notebook is organized and documented for clear presentation on GitHub.