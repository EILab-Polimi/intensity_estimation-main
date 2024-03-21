# Setup
1.	Install Anaconda Navigator following the instructions from: https://docs.anaconda.com/free/anaconda/install/
2.	From the Navigator, open a terminal and run the following: `conda env create -n ENVNAME --file ENV.yml`
3.	Download the cropped GridSat-B1 data from: https://doi.org/10.5281/zenodo.10849376
4.	Unzip the GridSat-B1 data inside the folder intensity_estimation-main/data/

# Training and testing
Both training and testing are done by the train_and_test.py script, which accepts a series of arguments from terminal (e.g., the type of model to train).
