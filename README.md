# TIL6022 Project Group 10: Rail Sabotage and Road Traffic on the A1

This project investigates whether the railway disruptions on the Amersfoort–Apeldoorn–Deventer corridor on 15 September 2026 led to measurable changes in traffic intensity and average speed on the parallel A1 motorway. Traffic on the disruption day is compared with a baseline of regular Tuesdays using NDW Dexter open data. The severity of the railway disruptions is quantified using open data from Rijden de Treinen.

## Contents

- `project_proposal.ipynb`: Project notebook (proposal stage)
- `project_proposal.html`: HTML export of the proposal notebook
- `final_project_group_10.ipynb`: Final project report
- `final_project_group_10.html`: HTML export of the final report
- `3_Visualization_traffic_intensity_and_speed.ipynb`: Analysis and visualization of traffic intensity and average speed
- `Analysis_traindisruption.ipynb`: Analysis and visualization of railway disruptions

## How to Run

The analysis was developed in Python using pandas, NumPy, Matplotlib and Seaborn. To reproduce the results, download the required datasets, place them in the appropriate `data` and `data_dexter` folders, and run the provided Jupyter notebooks.

## Data

The original datasets of Rijdendetreinen.nl are not included in this repository because several files exceed GitHub's file size limit.

Required datasets:

### NDW Dexter Open Data (included in repository)
https://dexter.ndw.nu/opendata/overview

### Rijden de Treinen Open Data (excluded from repository)
https://www.rijdendetreinen.nl/open-data/treinarchief#downloads

Download the train service datasets for:
- August 2026 (`services-2026-08.csv`)
- September 2026 (`services-2026-09.csv`)
- October 2026 (`services-2026-10.csv`)

Place the downloaded files in the `data` folder before running the railway disruption analysis notebooks.

