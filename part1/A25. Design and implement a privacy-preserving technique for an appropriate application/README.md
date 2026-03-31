# A25. Design and implement a privacy-preserving technique for an appropriate application

A simple privacy preserving technique for an example **student feedback application**.

## Privacy preserving technic

The privacy-preserving technique I chose is **pseudonymisation with data minimisation**.

Instead of storing a student real name, student number, or personal email in the main feedback record, the feedback stores:
- a random user ID or nickname
- the feedback message
- the date of submission

This means the feedback avoids collecting unnecessary personal information. The identity of the student is not directly visible in the main stored data.


## Example implementation

Example of less private design:

- Name: Jonathan Soetanto
- Student ID: 24004961
- Email: 24004961@student.uwa.edu.au
- Feedback: "The lab instructions were unclear."

Improved privacy-preserving design:

- User ID: student_204
- Feedback: "The lab instructions were unclear."
- Date: 31 marvh 2026
