# Dkebert-Aviation-Accidents
## Summary
This repository is an analysis of the [National Transportation Safety Board Aviation Accident Dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) performed with the goal of creating data-based recommendations for shareholders in an aviation startup. I aim to provide shareholders with a list of recommended aircraft that have a track record of low fatality rates in crashes, lower injury totals in poor weather conditions, and that have a low liklihood of being destroyed or needing major repairs in the event of a crash. My analysis found that Bombardier CL-600 was the overall safest investment for shareholders according to my methodology. 
## Cleaning
The Dataset contains a large portion of duplicated records, which this repository removes. This repository also attempts to fill in placeholder and missing values with random values according to the existing distribution of the data to avoid large effects on summary statistics. It also attempts to remove columns of tabular data that are not relevant to the analysis whenever possible. 
## Analysis
The Data was analyzed by grouping the data according to make and model, then comparing key summary statistics of columns that are relevant to the study. The methodology of my analysis was to recommend the planes that have the lowest mean number of fatalities and total injuries that have above ten records to ensure a sufficient sample size. Once I had made that determination, I pruned the dataset down to the aircraft I found had the lowest number of total injuries, then made new groupings and pivot tables to show their performance in poor weather conditions and to determine how likely they are to be destroyed in the event of a crash. My analysis found the Boeing 777 to be the overall safest aircraft in the dataset.
## Reference
This repository makes reference to a [repository from flatiron school](https://github.com/learn-co-curriculum/dsc-dealing-missing-data-lab/tree/solution) where I first saw the idea of assigning random values to placeholders according to the normal distribution. The dataset can be found on Kaggle, as linked above.
## Navigation
The code of this project is contained within the jupyter notebook index file in the repository. The dataset is contained within the data folder. 
## Tableau dashboard and presentation
https://public.tableau.com/app/profile/david.kebert/viz/DkebertAviationAccidentsProject/Dashboard1?publish=yes
https://docs.google.com/presentation/d/16-D6zM87T-OG1aw6xCb70riCVJ3jM2VU2sfM9oBQUgk/edit?usp=sharing