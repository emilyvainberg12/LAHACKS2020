# LAhacks
Patient Matching Challenge

Group Members
- Pranav Grover
- Omer Sasson 
- Emily Vainberg 
- Amy Seo
- Edmund Zhi

   ## Set up instructions
Our code for this challenge was written in Python. For others to set up our project to use on new data, there are a few steps that must be taken. The first step is to take our code found in Github, and copy it into a new Python Text Editor. The only thing that needs to be changed is the CSV file we pull the data from. This is in line 9 of our code in the main.py file. 

   ## Proof of Concept Steps
1. We took the data from the Patient Matching excel given and 

2. Used Jaro-Winkler similarity to compare data which we were able to do by making all data types strings (First Name, Street Address, Zip Code, etc.) This is a mathematical theorem that compares values and finds the similarity based on length, the position of the letters and numbers, and total characters used. 

3. To enhance accuracy we changed the actual table, for example Male == M and Female == F to reduce differences in similarity when there was an input error instead of a difference in data. We did this with possible street abbreviations and state abbreviatiosn to make sure any descrepencies in the way data was entered could be minimized. 

4. To create accurate group ID’s we created a dictionary with keys set by the GroupID’s and the values set to lists of the PatientID’s

Devpost Link: https://devpost.com/software/patient-identifier

