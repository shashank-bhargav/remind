##  Phrase detection for Reminder-Extraction

 In this project i attempt to solve a small problem in the domain of natural language chunking and tagging basically a model has been trained to chunk the phrases in a body of text which are indicating the presence of remainder 

## 1) Result on eval_data.txt, which will be used to evaluate the performance of your approach 
I dont have access to test's truth file but on manually looking at the results it looks fairly good.

## 2)  Well commented code
Code is inside the jupyter notebook(remind_extract.ipynb) and attach in the zip file

## 3) Models (save the trained models)
pickle files are there in the training data 


## 4) Steps to run the code
open the notebook in colab and run the code with shift + enter as all codes are in the notebook. 
please ensure that notebook is opened in python 2  as the notebook is code in python 2 


## 5) Initial approach

I tried to solve out this problem solution with Rasa nlu and Rasa X But didn't end up applying the rasa framework because it is for chatbot backends and it seemed to be overkill  on this problem.


## Next approach we went for Named Entity Recognition NLU it was again not fitting well on small set of data set 

 I used a pre-trained model for extraction reminder intent & the action/slot in this model I used logistic regression and with the help of sklearn & NLTK library 

















