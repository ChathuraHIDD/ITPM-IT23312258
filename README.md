# ITPM-IT23312258
# IT23312258 - Hiddallaarachchi C S


# Automation Test Cases

This project contains an automation script to run test cases using Python,Playwright, and Excel.

## Prerequisites

Install the following before running the project:

- Python 3.11 or 3.12
- Google Chrome browser
- Git

## Project Setup

Clone the repository:

git clone <your-repository-url>
cd test_automation

## Install the dependancy

run this commands on your terminal in vs code

- pip install -U pip
- pip install playwright openpyxl
- playwright install

## Excel Test Case File

open the excel file (IT23312258.xlsx) and remove those 

## Run the automation tests

open the terminal and run this command

python test_automation_IT23312258.py --excel "IT23312258/IT23312258 - IT23312258.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
