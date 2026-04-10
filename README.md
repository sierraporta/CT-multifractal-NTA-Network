# CT-multifractal-NTA-Network
Rolling MF-DFA and Natural Time Analysis of cosmic ray intensity
across 16 NMDB stations (2010–2025).

## Structure
- `NB1_DataGenerator.ipynb` — computes all metrics, saves to `Tables_datas/`
- `NB2_AnalysisFigures.ipynb` — loads from `Tables_datas/`, reproduces all figures

## Data
Daily CR intensity from [NMDB](https://www.nmdb.eu). 
Input file: `daily_mean_NMDBallstations_missing_lessthan5_2010-2025.csv`

## Requirements
`numpy`, `pandas`, `matplotlib`, `scipy`, `fathon`, `scienceplots`

## Reference
Sierra-Porta & Varotsos (2025), in preparation.
