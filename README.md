# Parsing-raw-text-files
Extract the given text files (Resumes) and transform the data to the XML and JSON format using regex in python.

1. Parsing_raw_text_files.ipynb: 
In this task, we need to go through each line in the file checking for the pattern defined by the regular expression for each key. Once the key is identifid the value part is extracted and saved to a temporary python Dictionary. While extracting the value part we need to make sure that the multi-lined values are read completely. 'completeString()' performs the multi-line reading, in this funtion identifying a key we will be performing multiple read till the next key is encountered. The function 'check(line)' will help us to check for the next key. For some attributes line job qualification and job_reponsibilites, there will be a list of values, whcih has to be extracted separately and stored as a list, completeList() function enables us to perform this functionality.

2. Text_preprocessing.ipynb: 
In this task, we are given a dataset of around 250 CVs of students,from which we need to generate a sparse representation of the resumes by using the given regular expression for tokenization and vocablary generation. We also need to generate a sparse matrix to keep a track of all  the words in the vocabulary in each resume.


