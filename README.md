# ExamPoint Online Exam Registration — AI-Assisted Test Case Generation

## Objective
This repository contains the practical artifacts for generating, reviewing, classifying, and comparing manual and AI-generated test cases for an online exam registration module.

## Requirement
The module allows students to enter personal details, select one or more available exam subjects, and pay the applicable examination fee. Mandatory fields and subject selections are validated. Registration is confirmed only after successful payment. Invalid input or failed payment must produce an appropriate message and must not result in a successful registration.

## Repository contents
- `test-cases/manual-test-cases.csv` — five initial manually designed cases.
- `test-cases/final-classified-test-cases.csv` — reviewed sample cases classified by type.
- `prompts/chatgpt-prompt.md` — prompt to submit to ChatGPT.
- `reports/comparison-report.md` — comparison template; fill in actual measured times.
- `evidence/` — place screenshots of the actual prompt and ChatGPT response here.
- `AI_Assisted_Test_Case_Generation_Practical.docx` — copy the completed Word practical here if desired.

## How to use
1. Review the requirement and manual cases.
2. Submit the prompt in `prompts/chatgpt-prompt.md` to ChatGPT.
3. Save screenshots of the actual prompt and response in `evidence/`.
4. Review the AI output for duplicates, accuracy, and unsupported assumptions.
5. Update the final classified test case CSV with the cases you retain.
6. Record actual manual and AI-assisted time in `reports/comparison-report.md`.
7. Commit and push the files to your GitHub repository.

## Important
This is a test-design practical. No live registration website or payment gateway has been tested by this repository. Boundary cases involving limits must be finalized only after the actual requirements specify those limits.
