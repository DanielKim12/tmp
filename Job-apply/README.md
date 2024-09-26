# Job Application Tracker

## Overview

This **Job Application Tracker** is a personal project designed to help me stay organized and accountable during my job search process. By using a Jupyter Notebook, I can track all the positions I've applied for, keep my resume updated, and record important details about each application, such as application status, interview preparation, and any additional tasks needed to follow up.

The main goal of this tracker is to keep a structured log of job applications and ensure that I don't miss important steps in the hiring process. It also helps with organizing all the applied positions in a single CSV file for easy reference and analysis.

## Features

- **Add Job Applications**: Easily add details about each job application, including company name, job title, application date, current status, and any additional notes (e.g., application deadlines, contacts).
- **Update Application Status**: Modify the status of an existing application (e.g., Applied, Interviewed, Rejected, Offer).
- **Track Interview Preparation**: Document any interview prep work and other actions required to improve chances for success (e.g., coding practice, research about the company).
- **Visualize Job Status**: See a bar chart representing the number of job applications in different statuses (e.g., how many are in the "Applied" state versus "Interviewed" or "Rejected").
- **Export to CSV**: Save all job application data in a CSV file for easy access and future reference.
- **Resume Updates**: Keep a log of when and how you updated your resume for specific job applications.
- **Stay Accountable**: With a clear log of your job search progress, you can keep yourself on track to ensure you're applying to jobs consistently and preparing properly for interviews.

## Setup Instructions

1. **Clone or Download** the repository and open the Jupyter Notebook in your preferred environment.
   
2. **Install the required libraries** by running the following command in a cell:
   ```bash
   !pip install pandas matplotlib
   ```
3.	Run the Notebook and follow the prompts in the interactive menu to start tracking your job applications.
4.	Save Data: Your job application data can be saved to a CSV file (job_tracker.csv) for persistence between sessions.

## Usage

### Once the Jupyter Notebook is open, you will see a menu system that provides options such as:
- Add a New Job Application: Input details about the jobs you apply to.
- View All Applications: Display all job applications you’ve tracked so far.
- Update Status: Update the status of an application as you progress through the hiring process.
- Save/Load CSV: Save the data to a CSV file or load it for reference in the future.
- Visualize Application Status: Create a bar chart to see how your applications are distributed across different statuses.

### Example Workflow
- Apply to a job and log it in the tracker.
- Update the application status (e.g., after an interview or rejection).
- Prepare for an interview by documenting key prep tasks in the notes.
- Update and save the data to a CSV file, keeping track of every position applied for.
- Analyze the progress by visualizing the application status.

## Future Enhancements
- Add more fields for tracking interview dates, company research, and coding challenges.
- Link to external resources for interview preparation.
- Include reminders for follow-up emails or tasks.
