## Authorship Proﬁling:

Authorship analysis deals with the classification of texts into classes based on the stylistic choices of their authors. Beyond the author identification and author verification tasks where the style of individual authors is examined, author profiling distinguishes between classes of authors studying their sociology aspect, that is, how language is shared by people. This helps in identifying profiling aspects such as gender, age, native language, or personality type. Author profiling is a problem of growing importance in applications in forensics, security, and marketing. In this project, we try to predict the gender of a tweet’s author: whether the author is a male or a female.

### Prerequisites:

1.	Python version: 3.7

2.	NLTK (Natural Language Toolkit)

3.	Sklearn or Scikit-learn

Before running the jupyter notebook code, it is important to place the input files (train_labels.csv and test.csv) and data folder for each author ID in the same folder as the code file.

### Installing:

1. The first and the most important step is to have python installed. 

2. Then installing nltk with the following command:
!pip install nltk

3. Installing sklearn:
!pip install sklearn

4. A message should be displayed indicating that it is installed successfully.

5. To check whether it is completed, one can run following commands (but not limited to):
from nltk.tokenize import RegexpTokenizer 
and 
from sklearn.feature_extraction.text import TfidfVectorizer

These commands should be run without any error.

### Input Files:

1. train_labels.csv: It contains 3,100 twitter author IDs and their gender labels and acts as the training data. 

2. test.csv: testing ids and testing gender labels are available. It contains the twitter posts from 500 authors. 

3. data.zip: 3,600 twitter texts for those authors, which acts as the training and testing data.

### Output File:

Only 1 output file pred_labels.csv containing 500 author IDs and their predicted gender labels in ‘male’ or ‘female’ with first column header as ‘id’ which is the author ID and second column header as ‘gender’. 

### Running the tests:

1. After opening the jupyter notebook ‘Group3_ass2.ipynb’ one can run the code by clicking on ‘Kernel’ and selecting ‘Restart and run all’. 

2. The code will read the input file train_labels.csv and extract ids and then extract the file corresponding to each ID from the ‘data’ folder. Similarly, for the IDs present in the test.csv. 

3. In order to ensure reproducibility of results, np.random.seed() is set. 

4. In the end, the accuracy of the model on 100% test data can be seen and the predicted gender labels for each author ID are saved to a csv file with appropriate headers.

### Built With:

•	Pandas – 1.0.4
•	Python 3.7 -  Project built
•	NLTK
•	Scikit learn

### Versioning:

I have used Google Drive File Streaming for versioning. 

### Authors:

•	Ruchira Rajendra Shidhaye


