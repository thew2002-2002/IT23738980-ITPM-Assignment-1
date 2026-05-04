Transliteration Accuracy Testing – Assignment 1 (Option 1)
👤 Student Information
Name: Nimanya H N T
Registration Number: IT23738980
Module: IT3040 – IT Project Management (Semester 1)
Assignment: Transliteration Accuracy Testing (Option 1)
---
📌 Project Overview
This repository contains an automated testing solution developed to evaluate the Sinhala transliteration accuracy of the web application below:
🔗 https://www.pixelssuite.com/chat-translator
The project focuses on identifying negative scenarios—cases where the system produces incorrect, unexpected, or failed outputs when converting Singlish text into Sinhala.
A total of 50 negative test cases have been designed and executed, covering all 24 Singlish input types specified in the assignment.
---
🚀 Features
✅ Automated testing using Playwright
✅ Excel-based test case management
✅ Automatic result recording:
Actual Output
Status (Pass/Fail)
✅ Covers all 24 Singlish input types
✅ Includes multiple input lengths:
Short (S)
Medium (M)
Long (L)
---
📂 Folder Structure
```
IT23738980/
├── IT23738980_Assignment_1_Test_Cases.xlsx
├── test_automation/
│   ├── test_automation.py
│   └── (supporting files)
└── GitHub_Link.txt
```
---
⚙️ Prerequisites
Make sure you have the following installed:
Python 3.11 or 3.12
Google Chrome Browser
---
🛠️ Installation Steps
Open Command Prompt
Navigate to the automation folder:
```cmd
cd /d D:\test_automation
```
Install required dependencies:
```cmd
pip install playwright openpyxl
playwright install
```
---
▶️ Run the Automation
Use the following command to execute the test suite:
```cmd
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200
```
🔍 Parameters
`--excel` → Excel test case file path
`--url` → Target application URL
`--wait-ms` → Page load wait time
`--type-delay-ms` → Typing delay per character
`--slow-mo-ms` → Execution slowdown for visibility
---
📊 Test Case Summary
Total Test Cases: 50
Type: Negative (Neg_xxxx)
Coverage: All 24 Singlish input types
Distribution: Minimum 2 per type
Input Lengths: S, M, L
---
📁 Submission Files
✔ Completed Excel file including:
Actual Output
Status
Analysis (Columns G & H)
✔ Playwright automation project
✔ Public GitHub repository link
---
🎯 Conclusion
This project demonstrates an automated approach to uncover weaknesses in Sinhala transliteration systems. By focusing on negative test cases, it highlights areas where the system fails to meet expected behavior, providing useful insights for future improvements.
---
📬 Contact
For any clarifications, feel free to reach out.
---
⭐ Thank you for reviewing this project!
