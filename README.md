This is a hiring web application that implements the Laravel PHP framework

## App Modules

# Job Applicant Module
- Applicants are able to login to the application with their credentials, and they will only have access to their own data.
- Applicants are able to maintain multiple resumes • One resume shall be marked as default.
- Applicants are able to maintain their cover letter.
- Applicants are able to watch a list of active jobs.
    - Job applications have the following filters: (job Title, Skills and Location).
- On every page there is a list of recommended jobs matching with the resume of the user.
- Applicants are able apply to a job.
    - On a click on apply button; a popup should prompt the user to upload a new resume or use existing resumes.
    - After confirmation, the resume is sent to the company that posted the job.
- Applicants are able to track their job application (Company will update the status; that will be shown to the applicants).
- An applicant receives notification on updates of status of their job applications.


# Company Module
- Company managers are able to login to the application with their credentials, and they will only have access to their own data.
- They are able to manage jobs.
- They are able to watch applications/submissions to a job and change their statuses.


# Website Admin Module
- Administrators are able to approve users.
    - A badge is assigned to users indicating verification.
- Administrators are able to remove/block any user, job or application.
- Administrators are able to reset passwords of the users.
- Admins are able to watch a list of all registered and unemployed applicants(specifically of an institute).


# Landing Page
Main page with simple text input
- Allows user to input the text or keyword, job to search for.
- View the listed result for the submitted search.

# General Points
- On top of this list, following stats must be shown:
1. Total number of institute graduates
2. Number of registered graduates
3. Number of graduates with job
4. Number of unemployed graduates
- Maintain in this document means Create, Read, Update and Delete (CRUD)

