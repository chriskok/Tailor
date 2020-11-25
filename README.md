# Tailor
Using Python and Machine Learning to quickly and effectively tailor resumes/cover letters based on the specific job descriptions you're applying to.

## Usage
1. Upload a cover letter into the /input folder
2. Run: `python cover_letter.py`

## Input Data
To train the models, I downloaded and extracted the following datasets from kaggle and named them as mentioned below in the /data folder (script to be written to do this automatically)
- [nyc_data](https://www.kaggle.com/new-york-city/new-york-city-current-job-postings?select=nyc-jobs.csv) 
- [job_rec_data](https://www.kaggle.com/kandij/job-recommendation-datasets) 

## TODO
- allow a file (probably CSV) of companys/titles/any other exchangables to be used (for more efficient replacement of multiple cover letters)
- automatically gather own data (job descriptions) from websites or online databases that are relevant to the job title
  - if we get this data, we can also recommend other jobs that fit your resume the best
- allow python kwargs for template file names so that people don't have to rename their files specifically to the specifications here
- allow user input of job descriptions, utilize NLP to understand the job descs and sort the content paragraphs based on relevancy (this will be the same basic premise for resumes as well)
- write script to automatically download input data for training models 
