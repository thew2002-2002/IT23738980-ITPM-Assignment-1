IT23738980-ITPM-Assignment-1
IT23738980 - Assignment 1 (Option 1)

Student Information
  Name: Nimanya H N T
  Registration Number: IT23738980
  Module: IT3040 – ITPM (Semester 1)
  Assignment: Transliteration Accuracy Testing (Option 1)

---

Project Overview

This repository contains the automated testing solution for evaluating the **Chat Sinhala Transliteration** functionality of the web application available at [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator).

The project identifies **50 negative test cases** (scenarios where the system fails or produces incorrect output) covering all **24 Singlish input types** specified in the assignment.

---

Features
- Automated testing using **Playwright**
- Excel-based test case management
- Automatic result recording (Actual Output & Status)
- Supports 50 failing test cases covering all required Singlish input types

---

Folder Structure
IT23738980/
├── IT23738980_Assignment_1_Test_Cases.xlsx          # Completed test cases with results
├── test_automation/                                 # Automation folder
│   ├── test_automation.py                           # Main Playwright script
│   └── (other supporting files)
└── GitHub_Link.txt


---

How to Run the Automation

Prerequisites
- Python 3.11 or 3.12
- Google Chrome browser

Installation Steps

1. Open Command Prompt
2. Navigate to the test_automation folder:
   ```cmd
   cd /d D:\test_automation

Install dependencies:
       pip install playwright openpyxl
       playwright install

Run the Tests
       python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 
       5000 --type-delay-ms 80 --slow-mo-ms 200


Test Cases Summary

Total Test Cases: 50 (All Negative - "Neg_xxxx")
Coverage: All 24 Singlish input types (at least 2 per type)
Input Length Types: S, M, and L


Submission Files

Completed Excel file with Actual Output, Status, and analysis columns (G & H)
Full Playwright automation project
Public GitHub repository
