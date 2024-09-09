# Project Documentation
## Overview
This project focuses on User Acceptance Testing (UAT) and Robotic Process Automation (RPA). UAT is essential for ensuring that a solution behaves as expected before going into production. RPA helps automate repetitive UAT tasks, allowing users to focus on more complex activities.

This project automates the UAT process for a web application using UiPath, which inserts input data from a test dataset and verifies that the correct output is generated.

## Prerequisites
Before using this project, ensure the following:

- UiPath Automation Cloud Account: Create an account at UiPath Automation Cloud.
- UiPath Studio Community Edition: Download and install UiPath Studio.
- Access to Web Application: Verify you can access the web app at Telemetry Portal.
- Test Data: Ensure you have the Excel test data file that will be used for input during automation.

## How to Use
Clone this repository to your local machine:


git clone https://github.com/your-repo/project-uat-automation.git

Open UiPath Studio and navigate to the project folder.

## Use the Excel test data file as the input source for the RPA workflow:

The workflow reads the input data from the file.
It then automatically fills in the web application form fields using the UiPath bot.
The desired output (a new record being displayed on the web application) is validated.
To execute the RPA process:

Launch the automation from UiPath Studio by clicking on the "Run" button.
The bot will begin the UAT process, inputting data from the Excel file into the web application fields and verifying the output.
Review the UiPath logs and ensure that all test cases pass. If any test case fails, amend the web application or UiPath automation script as necessary.

## Implementation Options
For students who have exhausted free Azure resources, use the provided web application at Telemetry Portal for testing. No access will be provided to the Azure resource or its database. The focus is on automating the UI testing process with UiPath.

## Requirements
Functional Requirements: Automate the manual UAT process using UiPath to ensure the web application outputs match the expected results.
Non-Functional Requirements: Ensure quality attributes like performance and reliability during the RPA process.


