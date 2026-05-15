File Upload Error Experience – UX Designer Assignment
Figma Prototype
• Figma Link: [https://www.figma.com/design/vbTL9BQsGWcbGdCdO52laq/Untitled?node-id=14-25&t=Bnvna964OQlwOSf9-1](https://www.figma.com/design/vbTL9BQsGWcbGdCdO52laq/File-Upload-Error-Experience?node-id=0-1&t=Bnvna964OQlwOSf9-1)
________________________________________
Project Overview
This assignment focuses on redesigning the file upload error experience for a web-based dashboard where users upload CSV or Excel files.
The main objective was to make the upload process easier to understand when validation errors occur, and to guide users clearly toward fixing and re-uploading their files.

## Problem Understanding
In the current flow, users upload a file but often struggle to understand:
•	Whether the upload was successful

•	How many records failed

•	Why those records failed

•	What they need to do next

This creates confusion and slows down the import process.

## Design Goal
The goal of this design was to create a clear, step-by-step experience that helps users:
1.	Upload their file
2.	Understand the processing state
3.	View upload results
4.	Review validation errors
5.	Download an error report
6.	Fix the file externally
7.	Re-upload the corrected file
   
## Screens Included
1. File Upload Screen
This is the starting point where users can:

•	Drag and drop a CSV or Excel file

•	Browse files from their computer

•	View supported file types

•	See the maximum file size allowed

Design Decisions
•	Large upload area to make the action obvious

•	Simple instructions with supporting text

•	Primary CTA button: Upload File

•	Clear note that validation will happen after upload

<img width="947" height="692" alt="Screenshot 2026-05-15 135057" src="https://github.com/user-attachments/assets/b05c9b4d-7c24-43d9-944a-d93c4846d95e" />


2. Processing State
After uploading, users see a processing screen while the system validates the file.

Design Decisions

•	Loader animation to show progress

•	Message explaining what the system is doing

•	Reassuring text so users know they should wait

This prevents uncertainty and makes the system feel responsive.

<img width="931" height="687" alt="Screenshot 2026-05-15 135108" src="https://github.com/user-attachments/assets/eb391f73-534c-4f05-85af-ca9f7b9bd9ab" />


3. Upload Result (Error Summary)
This screen provides a high-level summary of the upload outcome.

Example Data Used
•	Total Uploaded: 250

•	Successfully Imported: 210

•	Errors Found: 40

Error Breakdown
•	Missing Values: 18

•	Invalid Dates: 12

•	Invalid Options: 10

Actions Available
•	Download Error Report

•	View Errors

Design Decisions
•	Summary cards make key numbers easy to scan

•	Error breakdown gives users immediate context

•	Action buttons clearly indicate the next steps


<img width="905" height="682" alt="Screenshot 2026-05-15 135117" src="https://github.com/user-attachments/assets/156d7081-4b3f-429b-a4f9-c4c4b7e660e4" />


4. Error Review Screen
This screen shows detailed information about the rows that failed validation.

Information Displayed
•	Row number

•	Column name

•	Error type

•	Suggested fix
Actions

•	Download Full Error Report

•	Return to Upload Result
Design Decisions

•	Tabular layout for easy review

•	Suggested fixes reduce guesswork

•	Download option allows users to fix issues offline

<img width="910" height="687" alt="Screenshot 2026-05-15 135125" src="https://github.com/user-attachments/assets/6a6500a0-86f0-435d-9480-b715077677b6" />


5. Re-upload Corrected File
6. 
Once users correct their CSV externally, they can upload it again.

Design Decisions

•	Same upload component as the initial screen

•	Success message reminding users that the corrected file is ready to upload

•	Keeps the experience consistent and familiar

<img width="916" height="690" alt="Screenshot 2026-05-15 135134" src="https://github.com/user-attachments/assets/10ed7322-7051-4d91-b16c-e47b8eab37c2" />


## User Flow
Upload File
→ Processing
→ Upload Result Summary
→ Review Errors
→ Download Error Report
→ Fix File Offline
→ Re-upload Corrected File

<img width="1556" height="861" alt="Screenshot 2026-05-15 135150" src="https://github.com/user-attachments/assets/483a24d1-1582-45fa-b77a-3476c83f66a8" />


## Design Consistency

Buttons

1.Primary Button

Used for main actions such as:
•	Upload File

•	Re-upload File

•	Download Error Report

2.Secondary Button

Used for supporting actions such as:

•	View Errors

•	Back

Typography Hierarchy

•	Page Title: Large, bold

•	Section Heading: Medium, semibold

•	Body Text: Regular

•	Helper Text: Small and muted

Error Message Style

•	Error messages are shown in structured cards or table rows

•	Each includes the issue and a suggested fix

•	Red accents indicate problematic records

