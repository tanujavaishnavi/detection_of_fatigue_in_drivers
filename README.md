# DETECTION OF FATIGUE IN DRIVER'S
Detection Of Fatigue In Drivers is a project which detects the Drivers sleepiness if it finds the Driver to be sleepy it produces an alarm beep to wake up the driver. InceptionV3 Pretrained Model is used to detect the drowsiness in Drivers.

### DATASET :
we used MRLEyes Dataset. cleaned and prepared it according to our project.The cleaned dataset is kept in preparedData folder.can be used directly without downloading MRL Eyes dataset.

### RUN THE PROJECT :
Get all the data from the GitHub, Open Command prompt or any other Terminal and run the command :    
&nbsp;  \$git clone https://github.com/tanujavaishnavi/detection_of_fatigue_in_drivers.git
Open Anaconda Prompt run the command :
&nbsp;  \$jupyter notebook
Open the cloned repo in the Jupyter notebook click on dataset preparation.ipynb.
Run cells in the order change paths to your local paths where ever needed.
At this point our dataset will be prepared.Running "dataset preparation.ipynb" can be skipped as the dataset is already prepared.
click on ModelTraining.ipynb.
Run cells in the order change paths to your local paths where ever needed.
model.h5 will be downloaded in Models folder. Running "ModelTraining.ipynb" can be skiped as there is our trained model in Models Folder can be used directly.
click on detection.ipynb.
Run cells in the order.
Camera will be opened, model starts detecting the persons state whether sleepy or not.
