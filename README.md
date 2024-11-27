# Resume-Screening-App

## Context 

In today's fast-paced recruitment landscape, companies receive a huge number of applications for each job opening. Manually screening each resume is time-consuming and inefficient. To streamline this process, a resume screening app can be a valuable tool.

## Goals
Key Benefits of a Resume Screening App:
* Efficiency: Quickly filters resumes based on specific criteria, like skills and experience.
* Accuracy: Reduces the risk of overlooking qualified candidates.
* Data-Driven Insights: Provides valuable analytics on applicant pools.
* Scalability: Handles large volumes of applications with ease.

## Data Description

The dataset is obtained from kaggle (https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset).

The dataset includes over 2,400 resumes in two formats:
* Text Format: Each resume is provided as a string of text, containing the raw content without any formatting.
* PDF Format: The original PDF versions of the resumes are stored in a separate folder. The PDF files are organized into subfolders based on their respective job categories. The filename of each PDF matches the unique ID associated with that resume in the CSV file.

The CSV file provides information about each resume, including:
* ID: A unique identifier for the resume, also used as the filename for the PDF.
* Resume_str: The text-only version of the resume.
* Resume_html: The HTML structure of the resume, preserving formatting and layout information.
* Category: The specific job category for which the resume was used.

The categories in the dataset are: HR, Designer, Information-Technology, Teacher, Advocate, Business-Development, Healthcare, Fitness, Agriculture, BPO, Sales, Consultant, Digital-Media, Automobile, Chef, Finance, Apparel, Engineering, Accountant, Construction, Public-Relations, Banking, Arts, Aviation.

## Analytic Approach
The code will process the resume's content, assigning significance to each word using TF-IDF. These words will then serve as predictive features for two primary outcomes:

1. Predicted Category: A classification algorithm will analyze the relationship between each word and its corresponding category, ultimately determining the candidate's most suitable industry or job role.
2. Similarity Score: A regression algorithm will compare the input resume to historical resumes of successful and unsuccessful candidates. The similarity score, expressed as a probability, will indicate the likelihood of the candidate's success and prioritize them accordingly.

## The Inputs and Outputs of the App
* Input: A pdf file of a resume 
* Outputs: Predicted category and Similarity Score

## How to run the app
To run the app, you can either:
1. Run the code 'app.py' (make sure you have the pkl files as well) and it will generate a local URL and a public URL. The two URLs are the same, except that the public URL can be shared to others within 72 hours.

or

2. Contact me through my email (siawiracalvin@gmail.com) or whatsapp (+6288260463736) and I will send you the link to the app. 

## Limitations and Future Improvements







