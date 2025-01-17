From Data to ML and NN Models
I have chosen a dataset from https://catalog.data.gov/dataset/clean-air-markets-allowances-querywizard data.gov, specifically from the https://campd.epa.gov/data/bulk-data-files Clean Air 
Markets Program Data Application (CAMPD). This application, accessible at CAMPD, allows 
users to view and download Clean Air Markets data hourly, monthly and yearly. 
EPA's Clean Air Markets Division (CAMD) oversees several market-based regulatory programs 
designed to improve air quality and protect ecosystems. Notable programs include EPA's Acid 
Rain Program and the Cross-State Air Pollution Rule (CSAPR) Programs, which aim to reduce 
emissions of sulfur dioxide (SO2) and nitrogen oxides (NOx), compounds that negatively impact 
air quality, the environment, and public health. 
From this application, I have downloaded the emissions hourly dataset for the year 2023. which 
includes various features related to emissions, such as SO2 Mass, Heat Input, NOx Mass, CO2 
Mass, and operational parameters like Gross Load and Operating Time. The target variable for 
the analysis is the NOx Rate (lbs/mmBtu).

The goal of this analysis is to predict the NOx Rate (lbs/mmBtu), which is the rate of nitrogen 
oxides (NOx) emissions per unit of heat input for industrial facilities. Nitrogen oxides are 
important pollutants that contribute to issues related to the environment such as smog and acid 
rain, making it crucial to understand and predict their emission rates accurately.

This problem falls under the category of supervised regression. In supervised learning, we have a 
dataset with input features and a corresponding target variable, and the task is to learn a mapping 
from inputs to the target.
Supervised Learning: We have labeled data where the target variable (NOx Rate) is known for 
each observation.
Regression Task: As the target variable, that is NOx Rate (lbs/mmBtu), is continuous and 
numerical, this makes this a regression problem

Part 3 :
The OCTMNIST is based on a prior dataset of 109,309 valid optical coherence tomography 
(OCT) images for retinal diseases. Each example is a 28x28 image, associated with a label 
from 4 classes.

About files :
rakshit2_assignment0_part_1 is the jupyter notebook file for emissions-hourly-2023-wa dataset 
rakshit2_assignment0_part_3 is the jupyter notebook file for OCTMNIST classification dataset
rakshit2_assignment0_bonus folder contains the deployment of part_1 where it contains a datasets and a demo video of how to run the code jupyter notebook file of the code and pickle file for the deployement.
Model Deployment is done using a STREAMLIT deployment tool make sure after exporting all the files are in the same folder and open it in a vs code 
The commands to run the deployment file is python -m streamlit run rakshit2_assignment0_deploy.py and then open localhost:8501 
