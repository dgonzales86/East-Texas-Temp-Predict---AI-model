# East-Texas-Temp-Predict---AI-model

User Guide
East Texas Temp Predict Installation Instructions — Windows 10 and above, x86_64 architecture.

1.) Installation of Miniconda, A Lightweight Conda Package Manager.
 
a.)	Open the command prompt by pressing the Windows key and r. As shown below, enter cmd and click OK. 
 
b.)	When the command prompt loads, enter or paste the following commands one at a time and press enter after each line:

curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o miniconda.exe
start /wait "" miniconda.exe /S
del miniconda.exe

2.) Activate Conda Environment and Install Necessary Libraries.

	a.) Activate conda environment:
	
	When the Miniconda installation is finished, close the current command prompt.

	Click the “Start” button on the taskbar or press the “Windows” key on your keyboard.

	In the search bar, look for “Anaconda Prompt (miniconda3)” and select this application.

	When Anaconda Prompt launches, type or paste the following commands without quotations 	and press enter:

	“conda env list”

	This will display the directory of your current conda environment. The directory will look 		like the following:

	C:\Your\Directory\miniconda3

	Copy this directory by highlighting and pressing “Ctrl” and “c” simultaneously.

	Navigate to the copied directory using the cd command. “cd C:\Your\Directory\miniconda3”. 	You can paste the directory by pressing “Ctrl” and “v”. This will navigate to the current conda 	environment.

	Next, activate the conda environment using the following command:
	“conda activate C:\Your\Directory\miniconda3”.

	b.) Install packages and libraries.
	Install necessary packages and libraries by pasting the following commands one at a time. If 	prompted to proceed, enter y for yes to continue:
	

	conda install jupyter notebook
	conda install pandas
	conda install numpy
	conda install matplotlib
	conda install seaborn
	conda install scikit-learn

3.) Open Jupyter Notebook, Upload Application Files, and Run Application
	
a.)	Open Jupyter Notebook by typing “jupyter notebook” and pressing enter. Do not include quotations.
b.)	Once Jupyter Notebook has loaded, click the upload button on the top right of the page. Upload the files "CS-Data-modified.csv", and "East Texas Temp Predict.ipynb" in the ETTP folder. You must click Upload again on the Jupyter Notebook main page.


c.)	After uploading these files, East Texas Temp Predict should appear on your Jupyter Notebook main page. Open East Texas Temp Predict by clicking the link inside of your notebook.
	
	 

4.) Using East Texas Temp Predict
	
a.)	Now that your Jupyter Notebook is open click the ‘cell’ option at the top and then select ‘run all’.

 

b.)	Once All the cells have completed processing, you will have an interactive user interface to predict the low temperature based on the selection of month, day, projected high temperature, and whether rainfall is present.
 
