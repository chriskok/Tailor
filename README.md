# Tailor
Using Python and Machine Learning to quickly and effectively tailor resumes/cover letters based on the specific job descriptions you're applying to.

## Usage
1. Upload a cover letter into the /data folder
2. Run: `python cover_letter.py`

## TODO
- allow a file (probably CSV) of companys/titles/any other exchangables to be used (for more efficient replacement of multiple cover letters)
- allow python kwargs for template file names so that people don't have to rename their files specifically to the specifications here
- allow user input of job descriptions, utilize NLP to understand the job descs and sort the content paragraphs based on relevancy (this will be the same basic premise for resumes as well)

## Input Data
To train the models, I downloaded and extracted the following datasets from kaggle and named them as such in the /data folder
- [nyc_data](https://www.kaggle.com/new-york-city/new-york-city-current-job-postings?select=nyc-jobs.csv) 
- [job_rec_data](https://www.kaggle.com/kandij/job-recommendation-datasets) 
