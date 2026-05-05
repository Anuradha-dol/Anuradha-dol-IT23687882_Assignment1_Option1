# IT3040 ITPM Assignment 1 - Option 1

## Registration Number
IT23687882

## Assignment Option
Option 1: Transliteration Accuracy Testing for Chat Sinhala / Singlish to Sinhala.

## Files Included
- `test_automation/IT23687882_test_automation.py` - Playwright automation script.
- `test_automation/IT23687882_Assignment 1 - Test cases_FIXED.xlsx` - Completed test case Excel file with 50 negative test cases.
- `requirements.txt` - Python package requirements.
- `run_tests_IT23687882.bat` - Windows quick-run command.
- `Git Repository Link - IT23687882.txt` - Add the public GitHub repository URL here before submission.

## Test Case Coverage
The Excel file contains 50 negative test cases. It covers all 24 Singlish input types with at least two test cases for each type, plus two additional cases.

## Setup Instructions
1. Install Python 3.11 or 3.12.
2. Install Google Chrome, or allow Playwright to install Chromium.
3. Open Command Prompt in the root folder of this project.
4. Run the following commands:

```bash
pip install -U pip
pip install -r requirements.txt
playwright install
```

## Run the Automation
From the root folder, run:

```bash
python test_automation/IT23687882_test_automation.py --excel "test_automation/IT23687882_Assignment 1 - Test cases_FIXED.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

Or double-click:

```text
run_tests_IT23687882.bat
```

## Important Notes
- The `Actual output` and `Status` columns are intentionally kept blank before running automation.
- After running the script, reopen the Excel file and verify that the automation has filled `Actual output` and `Status`.
- If the script is still running with the browser open, press `CTRL + C` in Command Prompt after all rows are completed so the workbook is saved and the browser closes.

## Submission Checklist
- Run the Playwright script and confirm the Excel file is updated.
- Create a public GitHub repository and upload this project.
- Paste the public repository link into `Git Repository Link - IT23687882.txt`.
- Zip the `IT23687882` folder.
- Submit the zipped folder to CourseWeb.
