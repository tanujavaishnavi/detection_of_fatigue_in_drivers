# DETECTION OF FATIGUE IN DRIVER'S
Detection Of Fatigue In Drivers is a project which detects the Drivers Drowsiness if it finds the Driver to be sleepy it produces an alarm beep to wake up the driver. InceptionV3 Pretrained Model is used to detect the drowsiness in Drivers.

### DATASET :
we used MRLEyes Dataset. cleaned and prepared it according to our project.The cleaned dataset is kept in preparedData folder.can be used directly without downloading MRL Eyes dataset.

### RUN THE PROJECT :
1. Get all the data from the GitHub, Open Command prompt or any other Terminal and run the command :    
&nbsp;  \$git clone https://github.com/tanujavaishnavi/detection_of_fatigue_in_drivers.git
2. Open Anaconda Prompt run the command :
&nbsp;  \$jupyter notebook
3. Open the cloned repo in the Jupyter notebook click on dataset preparation.ipynb.\
      1. Run cells in the order change paths to your local paths where ever needed.\
      2. At this point our dataset will be prepared. Running "dataset preparation.ipynb" can be skipped as the dataset is already prepared.\
4. click on ModelTraining.ipynb.\
      1. Run cells in the order change paths to your local paths where ever needed.\
      2. model.h5 will be downloaded in Models folder. Running "ModelTraining.ipynb" can be skiped as there is our trained model in Models Folder can be used directly.\
5. click on detection.ipynb.\
      1. Run cells in the order.\
      2. Camera will be opened, model starts detecting the persons state whether sleepy or not.\

Model will stop detecting when it encounters keyboard Interupt.
