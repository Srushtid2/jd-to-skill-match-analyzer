# JD-to-Skill Match Analyzer

An AI-powered resume analysis workflow built with **n8n and Google Gemini**. It compares a candidate's resume with a job description and generates a structured report highlighting matching skills, missing skills, an estimated match score, and a recruiter-style summary.

## Features

- Upload a resume in PDF format.
- Upload a job description in PDF format.
- Extract text from both documents.
- Use Google Gemini to analyze the candidate's skills against the job requirements.
- Generate a match score, verdict, matched skills, skill gaps, and a summary.
- Display the results in a formatted report.

## Tech Stack

- n8n — workflow automation
- Google Gemini — LLM-based analysis
- PDF text extraction
- JavaScript — result formatting

## Workflow

1. Upload the resume and job description.
2. Extract text from both PDFs.
3. Send the extracted content to Google Gemini.
4. Generate structured matching results.
5. Display the results in a formatted report.

## Setup

1. Install or access an n8n instance.
2. Import `resume-vs-jd-scorer.json` into n8n.
3. Configure your own Google Gemini API credentials in n8n.
4. Review the model configuration and test the workflow with sample PDFs.
5. Activate or run the workflow according to your n8n setup.

## Limitations

- The match score is an AI-generated estimate, not a validated ATS score or a guarantee of shortlisting.
- Results depend on the quality of the extracted PDF text and the model's analysis.
- Review the output before using it for career decisions.
- Avoid uploading confidential resumes or personal information without appropriate privacy safeguards.

## Future Improvements

- Add evidence supporting each matched or missing skill.
- Improve structured-output validation and error handling.
- Add test cases to evaluate consistency and accuracy.
- Improve output security and document-processing reliability.

## Author

**Srushti Dharmadhikari**

GitHub: https://github.com/Srushtid2
