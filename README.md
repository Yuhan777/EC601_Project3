# EC601_Project3: Open Souce Project
## Phase1 
### Overview
* The goal of this project is to deploy a complex system using the given open-source library and dupilcate the result of the system. In my case, I choose to delopy the SincNet which is a neural architecture for processing raw audio samples.
### Prerequisites
* The SincNet project requires the Linux, Python 3.6/2.7, pytorch 1.0, and pysoundfile. I already have the linux and python envirnment. Then I need to install pytorch and pysoundfile. Pytorch is an open source deep learning platgorm that provides a seamless path from reaserch prototyping to production deployment. I installed it using pip install command. Pysoundfile is an audio library based on libsndfile, CFFI and NumPy. It can read and write sound files. And I install it using conda install -c conda-forge pysoundfile.

### Simulation
* Step 1: Run TIMIT data preparation.

python TIMIT_preparation.py $TIMIT_FOLDER $OUTPUT_FOLDER data_lists/TIMIT_all.scp

where $TIMIT_FOLDER is the folder of the original TIMIT corpus, $OUTPUT_FOLDER is the folder in which the normalized TIMIT will be stored, and data_lists/TIMIT_all.scp is the list of the TIMIT files used for training/test the speaker id system.

* Step 2: Run the speaker id experiment.


* Step 3: Get the result.
