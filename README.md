# Email-Sentiment-Analysis-Enron-Dataset-
Project for Natural Language Processing course. Sentiment Analysis of former Enron employees via their emails from the Enron dataset.

Running instructions:
1) Install Anaconda version 2 or 3 (which comes with corresponding python version)
2) Install the NLTK library (numpy and pandas should come with anaconda, if not then install the same as well).
3) Install the textblob package via the following instructions:
                                                              (i) Open command terminal
                                                              (ii) Enter the command 'conda install -c conda-forge textblob'
4) Downoad the Enron dataset from https://www.cs.cmu.edu/~./enron/  (more than 1 GB in size) and extract the maildir folder to the directory in which the .ipynb file is saved.
5) Change the name of the maildir folder from 'maildir' to 'enron'
6) Open the file 'NLP_Project.ipynb' using jupyter notebook and start running each of the cells one by one.
7) When asked to input the user name, input one of the 150 users' names from inside the maildir/enron folder.
8) Continue running the cells to get the various types of analysis results from the input user's sent mail.
