
# Data archive layout

- README.md

- data_raw/
  - NRCS_data_PRCP_inc_SnowAdj.csv
  - NRCS_data_PRCP_inc.csv
  - NRCS_metadata.csv
  - UCWRR_DEM_800m.tif
  - UCWRR_shapefile/
    - HUC2_14.shp (and accompanying files)
  - Additional_Stations/
    - 0484-20**WY.csv
    - 0761-20**WY.csv
    - 0909-20**WY.csv
    - 0951-20**WY.csv
    - 2192-20**WY.csv
  
  
- data_processed/
  - NRCS_dates_2008_2017.csv
  - Metadata_processed.csv
  - Baseline_runs/
      - Baseline_run_random_seed400.csv
      - Baseline_run_random_seed401.csv
      - ...
      - Baseline_run_random_seed414.csv
  - Sequential_runs/
      - Scenario1_CompareNSE.csv
      - Scenario1_Seq_Complete_df.csv
      - ...
      - Scenario4_CompareNSE.csv
      - Scenario4_Seq_Complete_df.csv
  
  
- scripts/
  - Process_raw_data.ipynb
  - Baseline_experiments.ipynb
  - Sequential_experiments.ipynb

