# NLP
This repository contains the assignments and project done as part of enhancing the learning experience in the [CS6370-Natural Language Processing Course](https://www.cse.iitm.ac.in/course_details.php?arg=MjI=) offered in Indian Institute of Technology Madras by [Prof. Sutanu Chakraborti](https://www.cse.iitm.ac.in/~sutanuc/).

## Folder Structure ##
```
NLP
│-- README.md    
│   
└───Course_Project
   │-- NLP_Course_project_ppt.pdf
   │-- Project_Statement.pdf
   |-- Report.pdf
   │
   └───Code
   |   │-- cranfield
   |   │-- NLP_final_project.ipynb
   |   └-- NLP_final_project_custom_search_application.ipynb 
   |  
   └───Hypothesis testing data
   |   │-- BM25.csv
   |   │-- LSA+BM25.csv
   |   |-- LSA+QE.csv
   |   |-- LSA.csv
   |   └-- Tfidf.csv
   |
   └───Project Proposal
       |-- Architecture_of_Proposed_Approach.png
       └-- CS20S012_CS20S016_Project_Proposal.pdf      
```

## Set up and Installation:##
To download the repository: 

`git clone https://github.com/ArupDas15/NLP.git`

We have used colab environment to develop the code and we made ipython notebooks for easy running. Please upload the ipython notebooks to Google Colab to run these notebooks.


The two notebooks present in the project are:


NLP_final_project.ipynb: 


[This notebook](https://github.com/ArupDas15/NLP/blob/master/Course_Project/Code/NLP_final_project.ipynb) contains the entire code for the project which creates various models and evaluates them using the metrics mentioned in the report.

NLP_final_project_custom_search_application.ipynb:

[This notebook](https://github.com/ArupDas15/NLP/blob/master/Course_Project/Code/NLP_final_project_custom_search_application.ipynb) contains the code for creating the custom search application to search for a query. It will take approximately 2 minutes to run this code.


# **NOTE** : 

Upload [cranfield dataset zip file](https://github.com/ArupDas15/NLP/tree/master/Course_Project/Code/cranfield) into your colab by clicking upload the file symbol present in the left panel prior to executing any other code cell. Change the path of the crandfield dataset zip file with your path instead of our google drive path.</br>
For example: `!unzip /content/cranfield.zip`
