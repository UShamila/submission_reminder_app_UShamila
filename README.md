Submission Reminder App

This app keeps deadlines for assignments and reminds late submissions by students. It works based on the submissions.txt file holding the students' names, assignment names, and submissionstatus.

Key Components

config.env – Stores app variables.
submissions.txt – Central file with student and assignment data.
reminder.sh – Checks deadlines for each assignment.
functions.sh – Displays students with pending assignments.
startup.sh – Starts the application.

Project Structure

After running create_environment.sh, the directory structure should look like this:

submission_reminder_{yourName}/  
│── app/  
│   ├── reminder.sh  
│── assets/  
│   ├── submissions.txt  
│── config/  
│   ├── config.env  
│── modules/  
│   ├── functions.sh  
│   ├── startup.sh  
│── README.md  
│── create_environment.sh  

How to Run the App

Clone the repository to your terminal.
Navigate to submission_reminder_{yourName}/.
Modify assignments in assets/submissions.txt if needed.
Edit variables in config/ and app/ directories.
Run the app by executing startup.sh.
