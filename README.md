# Automated Resume Relevance Scoring (n8n)

## Objective
Automated system to evaluate resume relevance against a job description using rule-based logic (no AI).

## Workflow Overview
- Google Drive Trigger (resume upload)
- PDF text extraction
- Candidate data extraction (name, email, phone)
- Skill matching against job description
- Relevance score calculation
- Google Sheets auto-update

## Tech Stack
- n8n
- Google Drive
- Google Sheets
- JavaScript (regex + keyword matching)

## Output
- Candidate Name
- Email
- Phone
- Resume Link
- Relevance Score
- Explanation

## Notes
- No AI used
- Fully automated & continuously running

