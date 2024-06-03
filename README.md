# Masterproject

This project consisted of a benchmark study which compares several radiologists in detecting clinically significant prostate cancer. The analysis 
further consists of an AI-Assistance tool, that automatically segments lesions and allows to compare state-of-the-art manual with AI-Assisted lesion segmentation. The data analysis
was performed in the jupyther Notebook files. 

The following environment file was used:
environment.yml

General_calculations.ipynb: Performance metrics calculations, Heatmap plots.

volume_of_lesions.ipynb: lesion volume calculation and plotting.

DSC_lesions.ipynb: Dice score was calculated between all lesions of a patient. These results were not used in the final analysis but the pooled overlap analysis was done instead.

Combined_lesions_segmentations.ipynb: Code that pooles all lesions of a case. E.g. all lesions of patient 1 seen by reader 1 manually are put into a single Nifti file. 

Int_over_union.ipynb : File that calculates the intersection over union, Dice score, F2 score for the pooled lesions made by combined_lesions_segmentations.ipynb

Plots.ipynb: Plotting and analysis of results from Int_over_union.ipynb

