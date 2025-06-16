# Postman Collection for API Testing

## Project Overview

This repository contains a collection of Postman collections developed as a toy project by Juyoung Moon to enhance the company's operations. The primary focus of these collections is to automate and streamline the testing process for various APIs using AI-driven approaches.

## Objectives

- To automate API testing using Postman collections.
- To integrate AI methodologies for improving test accuracy and efficiency.
- To provide a comprehensive and reusable test suite for API validation.

## Features

- **Centralized Collection**: All API endpoints are organized into logical and easy-to-navigate collections.
- **Automated Testing**: Set up to run seamlessly with CI/CD pipelines for continuous testing.
- **AI Integration**: Future plans to include AI elements that assist in test optimization.
- **Detailed Documentation**: Each collection includes detailed descriptions and example requests/responses.

## How to Use

**Clone the Repository**: 
   Clone the repository to your local machine:
   ```bash
   git clone git@github.com:jmoon-ionos/Whole_API_Testing.git

**Import Collections into Postman**

Open Postman.
Click on Import in the top left corner.
Select the JSON files you want to import from the Whole_API_Testing directory.
Run Collections:

Select a collection in the Postman app.
Click Run to execute the test cases in the Postman Collection Runner.
Automation via CLI (Optional):

Use Newman, Postman’s CLI tool, to run collections in a CI/CD environment:
newman run [collection-file.json]

## Contributions
Contributions to improve or expand these collections are welcome. Please submit a pull request with a clear explanation of your changes.

