# statistical-inferences
Evaluate Boston housing data set  using statistical inferences
Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/saurav-joshi/statistical-inferences.git
  
  cd statistical-inferences
  For Linux:

	conda env create -f requirements/statistical-inferences-linux.yml
	source activate statistical-inferences
        source deactivate statistical-inferences
For Windows:

	conda env create -f requirements/statistical-inferences-windows.yml
	activate statistical-inferences
	deactivate statistical-inferences


For Mac/OSX:

	conda env create -f requirements/statistical-inferences-mac.yml
        source activate statistical-inferences
	source deactivate statistical-inferences

Note for R Kernel installations: 

R kernel installation my require an additional step. If R kernel is not installed via env file run the following command. 

1. Activate statistical-inferences environment --- choose the command from above based on the OS
2. execute following command:

       conda install -c r r-irkernel
	
Open the notebook and follow the instructions.

	jupyter notebook boston_housing.ipynb

Anaconda quick tutorial:

        1. Download Anaconda from https://www.continuum.io/downloads depending on the browser. 
	2. Python comes in two flavours Python3 and Python2, download the 3.X.X installer. 
	3. Execute the commands mentioned above to activate and deactivate the enviornment
	
	4. To check all the active Anaconda enviornments execute
	    conda info --envs
	5. To check the package version installed in an enviornment execute
	    conda list <package-name>
	6. To check availability of a package run
	     conda search <package-name>
	
