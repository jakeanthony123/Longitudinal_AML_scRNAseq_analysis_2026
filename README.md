# AML single-cell RNA-seq analysis
Reanalysis of a public scRNA-seq dataset of acute myeloid leukaemia (AML), with samples from diagnosis (DX), remission (REM) and relapse (REL). Analysis starts from raw Cell Ranger output, although the authors also provide their processed data.

## Data
This project analyses publically available data from this study:
https://www.cell.com/cancer-cell/fulltext/S1535-6108(23)00364-1

The GEO accession number is GSE235063.

Download the data and store in a directory named Raw_data.

## Analysis
What each notebook does:
- '00_convert_raw_to_h5ad.ipynb' converts the raw files into AnnData

## Setup
conda env create -f environment.yml
conda activate sc2026

## Status
Work in progress.

## Notes
