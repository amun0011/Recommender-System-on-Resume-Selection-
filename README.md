# Recommender-System-on-Resume-Selection-
This project is aimed to recommend top 500 resumes for a particular job profile. The job profiles from the website have required skills which are compared with the skills from all the resumes from the resume inventory and top 500 of such matches are recommended for a particular job profile so that right candidates can be easily shortlisted.
#### Developer Name: Arunava Munshi
#### Developed On: Python 3 and Jupyter notebook
#### Libraries used: 
* String (for String Processng)
* nltk - natural language toolkit (tokenizer, lemmatizer, stopwords, collocations and probabilities)
* re (for regular expression, included in Anaconda Python 2.7) 
* itertools (for iterations)
* collections (for Collocations)

### Project Briefing
The purpose of this project is to demonstrate how wrangled data from different sources can be used to help the organizations to make informed decisions. In this project, the system recommends the top 10 resumes that are the best fit for the first 500 job advertisements in 'raw_data.dat' their “required qualifications” section. The resume files are given in 'resume_dataset.txt', from which resumes are picked and recommended for suitable job profiles.

#### Input Files: 
raw_data.dat and resume_dataset.txt
#### Output files: 
Recommender_System.ipynb and Recommended_Resume.txt which contains the recommended resumes for the first 500 job advertisements. The txt file contains 500 lines and each line of the txt file has the following format: Job_advertisment_id: first_ranked_resume_id, second_ranked_resume_id, …., tenth_ranked_resume_id 
