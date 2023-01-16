# IB-PastPaper-Sorter

This Section is for information to Developers, who further choose to utilize the MIT License and refine/edit the code

# How this works?
The program based on Python Essentially Works as a Data base to classify every question in the International Baccalaureate Diploma Programme (IBDP) Physics past papers belonging to a certain topic.
The Topic for every individual question is entered in integer form with the list given in the IB Guide, and as of now only whole number topics are supported. Sub-topics are not supported. However, Multiple topics can be entered by seperating the two with a double space..
After Entry, the software will store iinformation entered by the user in .txt format, in directory - .../PROGRAMS/1/ OR .../PROGRAMS/2/ Depending on the level of the paper.
Later, while accessing the database of papers, this software uses PyPDF2 to readt through PDFs, merge PDF files and create a seperate file filled with questions of the desired topic.


# Requirements
Having Python 3.8 or greater.
Having the virtual environment setup.
