# Envrionment Priming on Rotation Task Experiment
This experiment measures the effect of envronment priming on participants' reaction times and accuracy for various rotation tasks. It is an experiment built using the [jsPsych](https://www.jspsych.org/) library. Participants will first be assigned to an urban or rural condition where they will see 3 pictures from their condition for 10 seconds after which they have to asnwer questions. The questions are aimed to immerse them in the envrionment. The second block of the experiment will contain 16 mental rotation trials where they have to select the correct rotation in comparison to a reference picture. The rotations include a 45 degree rotation and a 90 degree rotation. Reaction time and accuracy will be collected for the rotation trials. Finally, they will be asked to complete a demographic form looking at their age, sex and environment that they grew up in. 

Research Question: How does environment priming (urban vs. rural) impact reaction times and accuracy in mental rotation tasks?
Hypothesis: It is hypothesized that priming participants with an urban environment will influence their ability to perform the mental rotation tasks more effectively (either faster or more accurately).

## Files Included
- **`MainExperiment/`**: This is the parent folder inside the malaFatema folder. All of the needed files are inside this folder. 
- **`Final_Experiment_Code.html`**: This is the main experiment file. Run this file to access the experiment. 
- **`jspsych/`**: This is the downloaded jsPsych library files which were used to create the experiment.
- **`PrimingImages/`**: This folder contains the images used for the urban and rural condition. 
- **`Rotation Images/`**: This folder contains the images used for the mental rotation task. The images are names by trial, rotation angle and the whether they are correct or incorrect.

## Prerequisites before starting the experiment
You would need to have a web browser in order to run this experiment. 
- Access to the images `PrimingImages/` and `Rotation Images/` folder. 
- Make sure that the environment is quiet and that you have normal or corrected to normal vision before starting this experiment. 

## How to Run the Experiment
1. Open the `Final_Experiment_Code.html` file in a web browser.
2. Follow the on-screen instructions to complete the experiment.

## Data Collection
The experiment will save data in CSV format at the end of the experiment. It includes reaction times (in ms) for the rotation task and the accuracy percentage for each condition. Demographic information will also be recorded (age, sex, and environment of origin). CSV file will be named: experiment_data.csv.


