Integration of a DataBase communication interface.
Based on a set of .csv files that gathered data about the Linkedin Job Posting from 2022 to 2024.

## Description of the content of the tables

### job_postings.csv
job_id: The job ID as defined by LinkedIn (https://www.linkedin.com/jobs/view/ job_id )
company_id: Identifier for the company associated with the job posting (maps to companies.csv)
title: Job title.
description: Job description.
max_salary: Maximum salary
med_salary: Median salary
min_salary: Minimum salary
pay_period: Pay period for salary (Hourly, Monthly, Yearly)
formatted_work_type: Type of work (Fulltime, Parttime, Contract)
location: Job location
applies: Number of applications that have been submitted
original_listed_time: Original time the job was listed
remote_allowed: Whether job permits remote work
views: Number of times the job posting has been viewed
job_posting_url: URL to the job posting on a platform
application_url: URL where applications can be submitted
application_type: Type of application process (offsite, complex/simple onsite)
expiry: Expiration date or time for the job listing
closed_time: Time to close job listing
formatted_experience_level: Job experience level (entry, associate, executive, etc)
skills_desc: Description detailing required skills for job
listed_time: Time when the job was listed
posting_domain: Domain of the website with application
sponsored: Whether the job listing is sponsored or promoted.
work_type: Type of work associated with the job
currency: Currency in which the salary is provided.
compensation_type: Type of compensation for the job.
‎

### job_details/benefits.csv
job_id: The job ID
type: Type of benefit provided (401K, Medical Insurance, etc)
inferred: Whether the benefit was explicitly tagged or inferred through text by LinkedIn
‎

### company_details/companies.csv
company_id: The company ID as defined by LinkedIn
name: Company name
description: Company description
company_size: Company grouping based on number of employees (0 Smallest - 7 Largest)
country: Country of company headquarters.
state: State of company headquarters.
city: City of company headquarters.
zip_code: ZIP code of company's headquarters.
address: Address of company's headquarters
url: Link to company's LinkedIn page
‎

### company_details/employee_counts.csv
company_id: The company ID
employee_count: Number of employees at company
follower_count: Number of company followers on LinkedIn
time_recorded: Unix time of data collection


Full data and info about the method to collect them are available here: [Linkedin Job Postings](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)
