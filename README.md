# AI-Resume-Screener
# Candidate Screening and Admin Dashboard

This repository contains an interactive candidate screening process built using Python, ipywidgets, and Google Colab. The project is divided into two main sections:

1. **Candidate Form:**  
   Candidates enter job details and answer a set of dynamically generated screening questions. Once completed, the candidate submits the form, and the responses are stored in session memory.

2. **Admin Dashboard:**  
   Administrators can view, filter, clear, and download all submitted candidate responses. This helps in quick analysis and further processing of candidate data.

## Features

- **Interactive Candidate Form:**  
  - Enter job details (Company Name, Job Title, Job Type, Job Description).
  - Generate a set of five tailored screening questions.
  - Answer the questions and submit the form.
  - Form resets automatically after submission.

- **Admin Dashboard:**  
  - View all submitted candidate responses.
  - Filter responses based on keywords.
  - Clear all responses from session memory.
  - Download responses as a CSV file for offline analysis.

## How to Use

### For Candidates (Cell 1)
1. **Enter Job Details:**  
   - Fill in the Company Name, Job Title, Job Type (Full-time, Internship, or Freelance), and Job Description/Responsibilities.
2. **Generate Screening Questions:**  
   - Click the **"Generate Screening Questions"** button. Five tailored questions will be displayed.
3. **Answer the Questions:**  
   - Provide your answers in the corresponding text areas.
4. **Submit the Form:**  
   - Click the **"Submit Candidate Responses"** button. A success message will be displayed and the form will clear for the next input.

### For Admins (Cell 2)
1. **View & Filter Submissions:**  
   - Enter a keyword in the filter box and click **"Apply Filter"** to display only matching responses.
   - Alternatively, click **"View All Saved Forms"** to see all submissions.
2. **Manage Submissions:**  
   - Click **"Clear All Saved Forms"** to remove all stored responses.
   - Click **"Download CSV"** to download all submissions as a CSV file for further analysis.

## Prerequisites

This project is designed to run on [Google Colab](https://colab.research.google.com/) and requires the following libraries:
- `ipywidgets`
- `pandas`
- `google.colab` (for file download functionality)
- `os`

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone <https://github.com/suryanshuanand1407x/AI-Resume-Screener.git>
   cd <https://github.com/suryanshuanand1407x/AI-Resume-Screener.git>
