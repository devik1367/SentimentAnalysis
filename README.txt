CSC791: Natural Language Processing
P1-Final Assignment
Devi Krishnan (dhkrishn)

==========================================================================================

There are the following files in the directory:
1. Models: Baselines - tfidf.py, word2vec.py; Proposed model - bert.py
2. Output files: testing_output_tfidf.csv, testing_output_word2vec.csv, testing_output_bert.csv
3. Data: P1_training.xlsx, P1_testing.xlsx (I downloaded them as excel files and read them in with pandas.read_excel)

==========================================================================================

Python version:
I used Python 3.8.3. 

==========================================================================================

Libraries used:
I used pip3 to install packages. To install pip3, type the following into the command line/terminal:
sudo apt install python3-pip

Please make sure the following libraries are installed:
Pandas, NLTK, SpaCy, Scikit-learn, sentence_transformers.
You can install the above required packages and dependencies by typing the following into the command line/terminal:
pip3 install pandas nltk spacy sklearn sentence-transformers xlrd

==========================================================================================

Instructions to run:
-Download and unzip the file.

-Make sure the above mentioned libraries are installed.

-Before running the code for the first time, type the following lines one by one into the command line/terminal:
python3
import nltk
nltk.download('punkt')
exit()

Next, type the following command into the CLI (this downloads the model I used for implementing SpaCy word2vec):
python3 -m spacy download en_core_web_sm

-To run the baseline models, make sure you are in the directory containing the model files and then type the following command into the command line/terminal:
python3 word2vec.py
-OR-
python3 tfidf.py

-To run the proposed model, type the following into the command line/terminal:
python3 bert.py
==========================================================================================

