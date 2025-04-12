Submission

Upload a notebook in two formats, .py and .ipynb. Both are required for grading. Name it MidtermProject_YourLastName_YourFirstName.ipynb. 

Make sure to run all code cells and leave the outputs under them.
Overview

    This assignment is individual.
    You will create a notebook that demonstrates the knowledge you have accumulated and retained during the first 8 weeks of this course. This will be mostly related to table manipulation using numpy and the datascience modules and drawing graphs using matplotlib.
    You may use Google Colab, Visual Studio Code or Jupyter Notebooks to create the notebook. Regardless of what platform you use, you will save the notebook as .ipynb
    You will choose a data set of your interest. The suggested resources are listed on the Dataset Survey (requires a separate submission.)

Requirements
Introduction

    Create a text cell at the beginning of the newly created notebook with the following information:
        Midterm Project
        Name: <your name>

    Create a text cell to explain the dataset you are using. Make sure to include:
        The link to the source
        What it is about
        What motivated you to use it
        What questions you are trying to answer

Setup

    If using Google Colab, there are two ways to access your data:
        Mount Google Drive and use a path to locate the data, e.g., in ../content/MyDrive. Do this if your file is stored on the drive.
        Upload the file directly. Do this if your file stored on your local computer.
    Add the cell to import the datascience, numpy, matplotlib modules:
    from datascience import *
    import numpy as np
    import matplotlib.pyplot as plt
    %matplotlib inline
    You don't need to import 'otter' as there is no auto-grading capability here.

Dataset

    Create a code cell to read the data you are using and display the first 10 rows.
    Using one or more of methods from datascience.table 

    Links to an external site., narrow down the columns that are relevant to your project. Explain why you selected those columns. If you are using all of them because your table is pretty concise, you can choose other methods such as to rename certain column labels to make them more readable.

Research

    Create seven (7) questions that you are trying to answer from analyzing this data. For each question, you will need:
        A text cell describing the question.
        One of more code cells that you will use to achieve your goal of answering the question
    Here is a list of methods that you are expected to use in this section:
        Table methods: select(), where(), sort(), group()
            pivot() can be an alternative to group() if it makes more sense in your project
    Create three different visualizations using scatter(), plot(), hist()

        Each visualization should show different information.
        Explain why it makes sense to use that particular visualization to show that information, and include the types of data you are graphing. There should be a good justification for the visualization

Conclusion

    End with a conclusion explaining your findings. Be thorough and specific.
        e.g., What was your reaction to the answers to your questions? Did they surprise you, intrigue you, disappoint you? If so, WHY?
        e.g., Did you find any associations in your data? If so, what do they mean? 
    How was applying your new skills to your own dataset? 
    Make sure to run all code cells and leave the outputs under them.
