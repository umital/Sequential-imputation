# Sequential-imputation

This repository documents the scripts and data used to generate the results for the following peer-reviewed publication:

Mital, U., Dwivedi, D., Brown, J. B., Faybishenko, B., Painter, S. L., and Steefel, C. I. (2020). Sequential Imputation of Missing Spatio-Temporal Precipitation Data Using Random Forests. Front. Water 2. doi: 10.3389/frwa.2020.00020.<br>
url: https://www.frontiersin.org/article/10.3389/frwa.2020.00020/full

Please refer to `Data_layout.md` to get a layout of the uploaded folders. The notebook documenting the sequential imputation algorithm can be found at `scripts/Sequential_experiments.ipynb`. The data and scripts in this repo can also be found here: https://www.osti.gov/servlets/purl/1766329/

## Project summary
In this work, I developed a new sequential imputation algorithm to gap-fill missing values in precipitation datasets. This algorithm imputes (or gap-fills) missing data at a target station by using synchronous data (or data observed at the time) from neighboring reference stations. The need for reference stations to have complete datasets implies that stations with incomplete records, even though strongly correlated with the target station, are excluded. The new algorithm addresses this limitation and enables the use of references stations that themselves have incomplete records. The algorithm increases in effectiveness when the number of stations with missing records increases. In a scenario involving imputation of 77 stations, the sequential imputation approach improved the accuracy of gap-filling in 64% of the stations.
