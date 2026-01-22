# Smart Job Matching Automation using n8n

## Description
This project automates job matching by analyzing user profiles and resumes,
comparing them with job requirements stored in Google Sheets, and sending
notifications only for eligible jobs using n8n.

## Features
- User registration with interest, salary, job type, and status
- Resume PDF text extraction
- Job eligibility matching using IF logic
- Automated email notifications for suitable jobs
- Google Sheets as database

## Tech Stack
- n8n
- Google Sheets
- Gmail API
- Gemini AI (Resume summarization)

## Workflow Logic
1. User submits form
2. Resume is extracted and summarized
3. User data updated in Google Sheets
4. Job data read from Jobs sheet
5. Eligibility conditions applied
6. Notification sent if matched

## How to Use
1. Import the workflow JSON into n8n
2. Configure Google Sheets and Gmail credentials
3. Update sheet IDs and column names
4. Execute the workflow

## Output
Eligible users receive job notifications via email.
