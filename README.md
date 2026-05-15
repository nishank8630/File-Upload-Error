File Upload Error Experience – UX Designer Assignment
Figma Prototype
• Figma Link: https://www.figma.com/design/vbTL9BQsGWcbGdCdO52laq/Untitled?node-id=14-25&t=Bnvna964OQlwOSf9-1
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

2. Processing State
After uploading, users see a processing screen while the system validates the file.
Design Decisions
•	Loader animation to show progress
•	Message explaining what the system is doing
•	Reassuring text so users know they should wait
This prevents uncertainty and makes the system feel responsive.

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

5. Re-upload Corrected File
Once users correct their CSV externally, they can upload it again.
Design Decisions
•	Same upload component as the initial screen
•	Success message reminding users that the corrected file is ready to upload
•	Keeps the experience consistent and familiar

## User Flow
Upload File
→ Processing
→ Upload Result Summary
→ Review Errors
→ Download Error Report
→ Fix File Offline
→ Re-upload Corrected File

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

