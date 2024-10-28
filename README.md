# SDET 2024 - Technical Task

## Project Overview

This repository contains the automation scripts developed for testing the My Store website (multiformis.com) using NightwatchJS for UI testing and Supertest for API testing.

## Table of Contents
- [Technologies Used](#technologies-used)
- [UI Testing](#ui-testing)
- [HTML Report (UI)](#html-report-ui)
- [Test Scenarios](#test-scenarios)
- [Bug Reporting](#bug-reporting)
- [Test Documentation](#test-documentation)
- [API Testing](#api-testing)
- [HTML Report (API)](html-report-api)
- [Test Scenarios](#api-test-scenarios)
- [Bug Reporting](#bug-reporting-api)
- [CI/CD Integration (Not Completed)](#cicd-integration)
- [CircleCI Status Badge (Not Completed)](#circleci-status-badge)

## Technologies Used
- **NightwatchJS**: For UI testing with Page Object Model.
- **Supertest**: For API testing.
- **HTML Reports**: Generated for both UI and API tests.

## UI Testing

### HTML Report (UI)
File Name: Nightwatch HTML Reporter.html (under the API Tests folder)

### Test Scenarios
1. **Contact Us Page**
   - Tested with Valid and Invalid Submissions.

2. **Homepage Search**
   - Search for "dress" and verify the search results.

### Bug Reporting
File Name: Bug Report - UI Testing.docs/xlsx
Bugs found during testing are documented in a Word table (and Excel Sheet - less clustered than word documents) with the following fields:
- **Bug ID**
- **Title**
- **Reported By**
- **Date**
- **Environment**
- **Description**
- **Steps to Reproduce**
- **Expected Result**
- **Actual Result**
- **Severity**
- **Priority**
- **Assignee**
- **Attachments**

### Test Documentation
File Name: Test Scenarios & Cases - Item Page.docx/xlsx
A document listing all test cases, their descriptions, and expected outcomes is available in the repository - Under UI Tests

## API Testing

### HTML Report (API)
File Name: API Test HTML Report.html

### Test Scenarios
- Test all API routes using mock-user-auth.
- Validate routes with both valid and invalid request bodies.
- Validate routes with valid and invalid authorization.

### Bug Reporting (API)
File Name: Bug Report - API Testing.docx/xlsx
Similar to UI testing, bugs found during API testing are documented in a Word table (and Excel sheet as well - less clustered) with the same fields.

## CI/CD Integration (Not Completed)
- UI Testing folder is added under the following Repository: https://github.com/linaelnahal/UI-Tests
- API Testing Folder is added under the following Repository: https://github.com/linaelnahal/API-Tests

### CircleCI Status Badge (Not Completed)


