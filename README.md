# statistical-inferences
Evaluate Boston housing data set  using statistical inferences
Clone the repository and navigate to the downloaded folder.

    git clone https://github.com/babhijit/statistical-inferences.git


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

Open the notebook and follow the instructions.

	jupyter notebook boston_housing.ipynb

Anaconda quick tutorial:

    1. Download Anaconda from https://www.continuum.io/downloads depending on the browser.
	2. Python comes in two flavours Python3 and Python2, download the 3.X.X installer.
    3. After installing ananconda run the following commands in the given order:
       * conda update conda
       * conda update --all
	4. Execute the commands mentioned above to activate and deactivate the enviornment

	5.  To check all the active Anaconda enviornments execute
             conda info --envs
	6.  To check the package version installed in an enviornment execute
             conda list <package-name>
    7.  To check availability of a package run
	         conda search <package-name>
    8.  To add a new channel in conda:
             conda config --add channels <channel-name>
    9.  To remove a channel in conda:
             conda config --remove channels <channel-name>
             [OR] edit ~/.condarc
    10. Delete an existing cond environemnt:
             conda-env remove --name <env name>
