# ITPM_playwright_IT23149076

# IT3040 - ITPM Assignment 1 - Option 1

## Transliteration Accuracy Testing for Chat Sinhala

## Project Description

This project contains an automated testing setup for evaluating the Chat Sinhala transliteration feature available at:

https://www.pixelssuite.com/chat-translator

The main purpose of this assignment is to test how accurately the application converts informal chat-style Singlish inputs into Sinhala text. The focus is on identifying cases where the generated Sinhala output is incorrect or inaccurate.

This project includes negative test cases based on different Singlish input types such as questions, commands, greetings, English word insertions, punctuation, numbers, dates, time formats, emojis, slang, and online identifiers.

## Assignment Scope

This automation project tests only the Chat Sinhala transliteration function.

## Out of Scope

The following areas are not tested in this project:

- Standard Sinhala transliteration
- Backend API testing
- Performance testing
- Security testing
- Scalability testing

## Test Case Summary

The assignment includes 50 negative test cases.

These test cases cover the 24 Singlish input types mentioned in the assignment brief. At least two test cases are included for each input type, and the remaining test cases are selected from relevant Singlish input categories.

Each test case includes:

- Test Case ID
- Input length type
- Singlish input
- Expected Sinhala output
- Actual Sinhala output
- Test status
- Singlish input type covered
- Evidence or rationale

## Files Included

- `package.json` - Project dependency file
- `package-lock.json` - Dependency lock file
- `playwright.config.js` - Playwright configuration file
- `tests/` - Folder containing Playwright test scripts
- `Assignment 1 - Test cases.xlsx` - Excel file containing test cases and execution results
- `README.md` - Project setup and execution instructions

## Requirements

Before running this project, make sure the following software is installed:

- Node.js
- npm
- Google Chrome or Playwright browser dependencies
- Visual Studio Code

## Installation Steps

Open the project folder in Visual Studio Code.

Then open the terminal and run the following command:

```bash
npm install
```

After installing dependencies, install Playwright browsers using:

```bash
npx playwright install
```

## How to Run the Tests

To run all Playwright tests, use:

```bash
npx playwright test
```

To run the tests in headed mode, use:

```bash
npx playwright test --headed
```

To open Playwright test UI mode, use:

```bash
npx playwright test --ui
```

## How to View the Test Report

After running the test cases, generate and view the Playwright report using:

```bash
npx playwright show-report
```

## Expected Result

The automation script opens the Chat Sinhala transliteration website, enters the selected Singlish inputs, captures the generated Sinhala output, and compares the result with the expected Sinhala output.

The final test results are recorded in the Excel file named:

```text
Assignment 1 - Test cases.xlsx
```

## GitHub Repository Instructions

This project should be uploaded to a public GitHub repository.

The repository must include:

- Playwright test scripts
- Playwright configuration files
- `package.json`
- Completed Excel test case file
- README.md file

## Submission Instructions

For final submission:

1. Rename the required files using the registration number.
2. Create a folder using the registration number.
3. Add the Playwright project files, Excel file, and Git repository link text file into the folder.
4. Zip the folder.
5. Upload the zipped folder to the CourseWeb submission link.

## Notes

- Do not use the sample test cases given in the assignment appendix as final test cases.
- All 50 test case IDs should begin with `Neg`.
- Make sure the GitHub repository is public before submission.
- Run the automation before submitting the final files.
