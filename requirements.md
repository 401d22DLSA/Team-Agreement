# Software Requirements

## Vision

**What is the vision of this product?**
We will create a CLI app that will build a web scraper from job search sites online like monster.com, indeed.com, etc. We will collect data for job listings in the tech industry such as company name, skills, education level, salary detail, etc. and then allow users to search for jobs by keyword, save jobs they are interested in, and run the job's data through AI to produce a sample cover letter for that job.

**What pain point does this project solve?**
Helps users find relevant and recent job listings in the tech industry, select listings they like, and then prompt AI to process the listing's data to produce a sample cover letter for the given job posting.

**Why should we care about your product?**
People looking for work in the tech industry should care about this product because it will allow users to more efficiently browse, filter, and apply for recently posted relevant jobs.


## Scope (In/Out)

**In: what will the product do?**
- It will scrape job sites for job postings.
- It will look for jobs based on user filters.
- It will create a cover letter (or more) for a selected job posting.
- It will save the job posting and cover letter in a user's folder.


**Out: what will the product NOT do?**

- It will not scrape data outside of job-related websites.
- It will not send applications in to the job posts for the applicant.


## MVP & Stretch Goals

**What will MVP functionality be?**
- It will scrape job sites for job postings.
- It will look for jobs based on user filters.
- It will create a cover letter (or more) for a selected job posting.
- It will save the job posting and cover letter in a user's folder.

**What stretch goals will we aim for?**
- Multiple cover letters for the same job posting.
- Create multiple folders for jobs based on job title, date posted, etc.


## Functional Requirements

**Feature Tasks**
- It will scrape job sites for job postings.
- It will look for jobs based on user filters.
- It will create a cover letter (or more) for a selected job posting.
- It will save the job posting and cover letter in a user's folder.


**Data Flow**
See DOM on the main README page.


## Non-Functional Requirements
What is the requirement and how will it be implemented?

**1. Usability**
Usability: To ensure a user-friendly experience, the CLI app should have a clear and intuitive interface, allowing users to easily navigate and interact with the features. This can be achieved by implementing a command-line menu with clear instructions and prompts, providing informative error messages, and incorporating features like autocomplete or suggestions to assist users in entering search keywords or filtering options. Additionally, the app should have proper documentation or a help section to guide users on how to use its functionalities effectively.

**2. Testability**

Testability: To ensure the reliability and quality of the application, it should be designed in a way that facilitates testing. This can be achieved by using modular code and following software engineering best practices like separation of concerns and adhering to the SOLID principles. The codebase should be well-structured and organized, allowing for easy isolation of different components or modules for unit testing. Additionally, automated testing and tools can be used to create test cases that cover various scenarios and validate the functionality of the web scraper, data processing, and cover letter generation features. Testability should be a priority to catch any potential bugs or issues early in the development process.
