&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![BloodPaTH_logo - Copie](https://github.com/user-attachments/assets/cbd2b607-cd24-4818-9c9e-aa5d7485901d)

# *BloodPaTH* : Bloodborne Pathogens Transmission in Hospitals   

## Installation

After downloading the BloodPaTH package (BloodPaTH_1.0.tar.gz) please start by installing it in your R environment using the following command line (you will need the 'tools' package to process):
 > tools::Rcmd("INSTALL BloodPaTH_1.0.tar.gz")

## How does it work ?  

... Coming soon ...

**NB**: This package is in alpha version and is still under development. A Shiny app is currently being developped. 

## Application

You will find an application of the model in the "model_application_example.R" file. 

To run the code you will need to download the "Data example" folder, in which you will find synthetic data :
- *List_Transition_Matrices.rds* : An RDS file containng a list of 2 transition matrices between wards of size 29x29
- *List_Proc_Prob_Matrices.rds* : An RDS file containng a list of 2 matrices of probabilites of undergoing a set of procedures while being hospitalized in each of the ward (size : 28x10)
- *association_devices_procedures.csv* : A CSV file summarising the association between devices and procedures (1 : a given device is used during a given procedure, 0 : a given device is not used during a given procedure)
- *risk_dist.csv* : A CSV file detailing the parameters of the distribution of the risk of getting infected for each type of procedure 

**NB:** You will have to change the path when loading the data within you R session. 

You will find in the "Functions_plot.R" file the functions allowing visualization of the output. 

If you have any question, please reach the author Paul Henriot at the following email adress : paul.henriot@protonmail.com

