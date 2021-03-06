# Artificial-Intelligence
AI ==> Artficial Intelligence


AI stands for artificial intelligence, where intelligence is defined as the ability to acquire and apply knowledge.
Project: Sign Language Recognition System

Install

This project requires Python 3 and the following Python libraries installed:

    NumPy
    SciPy
    scikit-learn
    pandas
    matplotlib
    jupyter
    hmmlearn

Notes:

    It is highly recommended that you install the Anaconda distribution of Python and load the environment included in the "Your conda env for AI ND" lesson.
    The most recent development version of hmmlearn, 0.2.1, contains a bugfix related to the log function, which is used in this project. In order to install this version of hmmearn, install it directly from its repo with the following command from within your activated Anaconda environment:

pip install git+https://github.com/hmmlearn/hmmlearn.git

Code

A template notebook is provided as asl_recognizer.ipynb. The notebook is a combination tutorial and submission document. Some of the codebase and some of your implementation will be external to the notebook. For submission, complete the Submission sections of each part. This will include running your implementations in code notebook cells, answering analysis questions, and passing provided unit tests provided in the codebase and called out in the notebook.
Run

In a terminal or command window, navigate to the top-level project directory AIND_recognizer/ (that contains this README) and run one of the following command:

jupyter notebook asl_recognizer.ipynb

This will open the Jupyter Notebook software and notebook in your browser which is where you will directly edit and run your code. Follow the instructions in the notebook for completing the project.
Additional Information
Provided Raw Data

The data in the asl_recognizer/data/ directory was derived from the RWTH-BOSTON-104 Database. The handpositions (hand_condensed.csv) are pulled directly from the database boston104.handpositions.rybach-forster-dreuw-2009-09-25.full.xml. The three markers are:

    0 speaker's left hand
    1 speaker's right hand
    2 speaker's nose
    X and Y values of the video frame increase left to right and top to bottom.

Take a look at the sample ASL recognizer video to see how the hand locations are tracked.

The videos are sentences with translations provided in the database.
For purposes of this project, the sentences have been pre-segmented into words based on slow motion examination of the files.
These segments are provided in the train_words.csv and test_words.csv files in the form of start and end frames (inclusive).

The videos in the corpus include recordings from three different ASL speakers. The mappings for the three speakers to video are included in the speaker.csv file.
