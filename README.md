
# HR Process Automation Using UiPath

An HR automation project designed to streamline recruitment workflows, from resume collection and candidate screening to interview scheduling and onboarding. The solution uses UiPath to automate repetitive tasks, organize candidate information, and improve recruitment workflow efficiency.

## Overview

The project focuses on automating key stages of the recruitment lifecycle using robotic process automation (RPA), document processing, and workflow integrations.

## Key Features

### 1. Resume Collection
- Automatically retrieves incoming job application emails.
- Downloads attached resumes into the designated `Resumes/` directory.

### 2. Automated Resume Screening
- Extracts candidate details, including name, email, skills, degree, and experience.
- Uses regular expressions (Regex), OCR, and NLP-based scoring to evaluate candidate suitability.
- Generates a ranked candidate report at `Output/CandidateScores.xlsx`.

### 3. Interview Scheduling
- Sends interview invitations to shortlisted candidates through Outlook.
- Allows HR to review and finalize interview time slots in the Outlook Calendar.

### 4. Employee Selection and ID Card Generation
- Generates employee ID cards for selected candidates using UiPath document automation.
- Stores generated ID cards in the `Output/IDCards/` directory.

### 5. ERP Data Upload
- Updates candidate and employee details, including name, role, joining date, and employee ID, in the organization's ERP system.
- Supports UI-based or API-based data entry for centralized recordkeeping.

## Technology Stack

| Technology | Purpose |
|---|---|
| UiPath Studio | RPA workflow development and orchestration |
| UiPath Mail Activities | Email retrieval and resume attachment handling |
| Regex and OCR | Resume text extraction and structured data parsing |
| NLP-based Scoring | Candidate suitability evaluation |
| Excel Automation | Candidate ranking and recruitment reports |
| Microsoft Outlook | Interview invitations and calendar coordination |
| Document Generation | Employee ID card creation |
| ERP Integration | Candidate and employee data updates through UI or APIs |

## Output Files

| Process Stage | Output | Description |
|---|---|---|
| Resume Screening | `Output/CandidateScores.xlsx` | Ranked list of candidates and their scores |
| Interview Scheduling | `InterviewInvites.log` | Status of interview invitations |
| ID Card Generation | `Output/IDCards/` | Generated employee ID card PDFs |
| ERP Upload | `UploadLog.xlsx` | Records of ERP upload operations |

## Future Enhancements

- **AI-Assisted Interviews:** Explore virtual interview assistants for communication and sentiment analysis.
- **Adaptive Candidate Screening:** Investigate machine learning techniques to improve candidate evaluation.
- **Credential Verification:** Explore blockchain-based verification of candidate credentials.
- **Candidate Engagement Chatbots:** Introduce conversational assistants for personalized candidate communication.

## Project Goals

- Reduce repetitive manual work in recruitment.
- Improve consistency in resume screening and candidate data handling.
- Organize recruitment outputs for easier review.
- Explore automation opportunities across HR processes.

## Disclaimer

This project is intended for learning and demonstration purposes. Actual functionality depends on the implemented UiPath workflows, configured integrations, and required system access.
