# 570BERT
1) How to run the experiments:
There are three main experiments that I ran to test my BERT model. They are pretty simple to get running, especially because the code is in a juypter notebook. After commenting out some cells and modifying the path to file, simply run all the cells to get the output in the last cell of the notebook. 

To train BERT on sentences that you would like to write yourself, uncomment the "text" definition in the 5th cell. This cell has a comment "to use whatever text you want" at the top. To use your own sentences, just make sure to add a newline character at the end of each sentence. 

To train BERT on sentences from a json file found at this link: https://huggingface.co/datasets/khalidalt/HuffPost/blob/main/News_Category_Dataset_v2.json, comment out the code in cells four and five, and modify the path to the .json file to match where it can be found on your computer. 

To train BERT on sentences from a text file included in the GitHub repository liked here: https://github.com/pasperry6/570BERT, comment out the code in cell five, and modify the path to the .txt file to match where it can be found on your computer. You can use any text file as a trainer in this way. The larger the text file, the better the training, in general. The origingal BERT uses a corpus of ~800M words. 

2) 
a) Files that have been copied from other repositories with references to these repositories:  
The original notebook can be found at this link: https://colab.research.google.com/drive/13FjI_uXaw8JJGjzjVX3qKSLyW9p3b6OV?usp=sharing
And the blog from where the code is associated is here: https://neptune.ai/blog/how-to-code-bert-using-pytorch-tutorial

b) Which code files have been modified and how they have been modified
The whole notebook has been modified in the following ways: 
1. The whole data setup for the datasets is my own code (cells 1-4)
2. Parsing the data had to be modified to accomidate different datasets (cell 6)
3. 
4. The last cell has been completely modified to display the information that I want, and it calculates accuracy over the whole dataset. 

c) Which code files are the student's original code:
None. Since there is just one file, and it is completely modified from the original.

3) A description of the datasets I used and where I obtained them:

.json file "dataset":
Description: A list of news article headlines and a short description accompanying them.
The .json file dataset was obtained through another repository that I was originally planning on using here is the link: https://huggingface.co/datasets/khalidalt/HuffPost/blob/main/News_Category_Dataset_v2.json

.txt file "dataset":
Description: A compilation of Sherlock Holmes short stories
Obtained: I compiled this dataset myself by copying and pasting stories from this website: https://sherlock-holm.es/ascii/

