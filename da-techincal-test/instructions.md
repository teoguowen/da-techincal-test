# Data Analyst Take-Home Technical Test

Thank you for your interest in the Data Analyst role. This technical test is designed to assess your practical skills in **Python** and **SQL**. The test is split into two parts:

## Test Structure

1. **Python Task** – Automating an incentive calculation process  
2. **SQL Task** – Working with a simulated insurance dataset

## Timeline

- You have **1 week** to complete this test from the date it is sent to you.

## Submission Guidelines

- Please upload your solution (code and any relevant artifacts) to your personal **GitHub repository**.  
- Share the link to your GitHub repository as your submission.

## Python Task

### Overview

In the insurance industry, agents are responsible for selling policies to customers. Their compensation is typically commission-based, meaning they earn based on the volume of their sales.

There are often predefined incentive schemes that dictate how these commissions are calculated. These calculations are usually performed by the operations team, sometimes with help from the Data Science & Analytics team for automation.

Your task is to recreate a simplified version of this process in **Python**, simulating how commissions are computed.

### Data Provided

- `policies.csv`
- `agents.csv`
- `persistency.csv`
- `incentive-table.csv`
- `incentive-calculations.xlsx` *(used as the final calculations file – refer to this for the logic/formulas)*

### Instructions

- Recreate the commission calculation in Python, automating what might typically be done in Excel.
- Review the formulas in the `incentive-calculations.xlsx` file, especially the **‘Summary’** tab.
- The final output to reproduce is the **Final Commission Payable** (see column M - `FinalCommission`).
- The purpose of this report is to allow the Finance team to pay the correct incentive amount to the agents.
- Use the provided CSV files to reproduce the final commission column using Python scripts.
- Your final script(s) should be executable from the command line (e.g., `python main.py`) and produce the same output.
- Focus on writing **clean, modular, and readable code**.

### Requirements

You will be required to submit the following in your github repository
- Python script(s)
- Output csv/excel file generated from your Python script(s)

## SQL Task

### Overview

This task evaluates your ability to write **clean, well-structured SQL** to solve real-world analytical problems using an insurance-related dataset.

### Data

You will be working with a SQLite database created from the following CSV files:

   * `claims` ← from `claims.csv`
   * `customers` ← from `customers.csv`
   * `payments` ← from `payments.csv`
   * `policies` ← from `policies.csv`

### Instructions

#### 1. Explain Your Thought Process

- For each question, include your **thought process as SQL comments**.  
- Describe your approach, any assumptions made, and how you arrived at your solution.

#### 2. Write Clean SQL Code

- Format your SQL well – use **indentation**, **aliases**, and **consistent naming conventions**.  
- Well-structured, readable queries will score higher.

#### 3. No Use of Generative AI Tools

- Please **do not use generative AI tools** (e.g., ChatGPT, Copilot, etc.) to assist with your solutions.  
- We want to assess your individual capabilities, and any suspected AI-generated content will invalidate your submission.

### Requirements
You will be required to submit the following in your github repository
- `sql-test-questions.ipynb` Jupyter notebook containing your answers
