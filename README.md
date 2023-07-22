# Dkebert-Aviation-Accidents
## Summary
This project is an analysis of the [National Transportation Safety Board Aviation Accident Dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) performed with the goal of creating data-based recommendations for shareholders in an aviation startup. I aim to provide shareholders with a list of recommended aircraft that have a track record of low fatality rates in crashes, lower injury totals in poor weather conditions, and that have a low liklihood of being destroyed or needing major repairs in the event of a crash. My analysis found that the Boeing 777 was the overall safest investment for shareholders, with the Bombardier Challenger 600 series of learjets close behind. I recommend shareholders purchase a mixture of these two aircraft to grab a larger marketshare.
## Cleaning
This project cleans the dataset by:
-Removing duplicates
-Dropping rows where it is not appropriate to fill them
-Filling missing entries with statistical mean or median where expedient
-Filling missing entries with normalized random values where possible
-Filtering out all aircraft with less than two engines and ten incidents on record
## Analysis
I analyzed the data by:
-Grouping by make and model
-Comparing summary statistics of fatality, injury, and passenger totals
-Narrowing the focus of the dataset to just the safest aircraft as determined by total injury to total passenger ratio
-Analyzing total number of injuries in IMC and VMC weather conditions
-Analyzing total number of incidents which resulted in one of three categories of damage to the aircraft.
My analysis found the Boeing 777 to be the overall safest aircraft in the dataset.
## Reference
This repository makes reference to a [repository from flatiron school](https://github.com/learn-co-curriculum/dsc-dealing-missing-data-lab/tree/solution) where I first saw the idea of assigning random values to placeholders according to the normal distribution. The dataset can be found on Kaggle, as linked above. The notebook also contains several images which are cited inline.
## Navigation
The code of this project is contained within the jupyter notebook index file in the repository. The dataset is contained within the data folder. 
## Tableau dashboard and presentation
https://public.tableau.com/app/profile/david.kebert/viz/DkebertAviationAccidentsProjectDashboard/Dashboard1?publish=yes
https://docs.google.com/presentation/d/16-D6zM87T-OG1aw6xCb70riCVJ3jM2VU2sfM9oBQUgk/edit?usp=sharing