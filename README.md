# Email Categorizer
This project was made to categorize our emails. It categorizes your emails into six categories namely "Business",
"Document Editing or Checking", "Employment Arrangements", "Logistic Arrangements", "Personal but in professional context"
and "Purely Personal". These categories were chosen as basic categories of email by the UCB. The dataset used to train
the program is the 'Enron' email dataset, thanks to UCB. We used Naive Baye's, Logistic Regression, Linear SVM and Multinomial
Naive Baye's classifiers to train the program and classify the emails. The program takes into account only the body of
the emails to classify them and none other parameters such as subject, sender, date etc. Run the main_program.py to start
the program. The program isn't complete yet and minor adjustments are to be done. Finally one last con, the program will
not work for emails in the MIME format but will only work for emails which have pure text in the body.

## Getting Started:
These instructions will get you the project up and running on your local machine for development and testing purposes.

### Prerequisites
What things you need to run the program.
* Python 3.0 or higher.
* nltk, scikit-learn, email, imaplib modules installed. If you have not able to install nltk/scikit-learn using conventional methods like pip, download etc., installing anaconda is recommended.

## Built With:
* Anaconda 3 (Python 3.6)

## Authors:
Koyalkar Pravin Kishore - pravinkishore[One][Nine][Nine][Seven]Atgmail.com <br />
Chandrahas Reddy Mandapati - chandur626[Six][Two][Six]Atgmail.com

## Acknowledgments
* University of California, Berkeley (UCB) for its Enron Emails Dataset.
* Harrison Kinsley for his tutorial on nltk - [NLTK with Python 3 for Natural Language Processing](https://www.youtube.com/watch?v=FLZvOKSCkxY&list=PLQVvvaa0QuDf2JswnfiGkliBInZnIC4HL)
