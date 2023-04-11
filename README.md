![Screenshot1](screenshot.docx)
![superman](https://user-images.githubusercontent.com/126728866/231224948-6852689f-02be-40a0-b37e-091bb29e3629.PNG)


# Loan Qualifier App CLI

This is a command-line interface application for connecting banks with potential loan applicants.


The goal of this portion of the project is to permit the user to have the ability to save the qualifying loans to a CSV file so that they can share the results as a spreadsheet.

    The tool should prompt the user to save the results as a CSV file.

       1. Given that no qualifying loans exist, when prompting a user to save a file, then the program should notify the user and exit.

        2. Given that there is a list of qualifying loans, when the user is prompted to save the results, they should be able to opt out of saving the file.

        3. Given a list of qualifying loans, when the user chooses to save the loans, the tool should prompt for a file path to save the file.

        4. Given the loan qualifier CLI, when the user chooses to save the loans, then the tool should save the results as a CSV file.

---

## Technologies

This project leverages python 3.9.13 with the following packages:

* [fire](https://github.com/google/python-fire) - Fr the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* Sysexit 

* Pathlib 


---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```
---

## Usage

To use the loan qualifier app, simply run the program and input the csv of bank data. The user will then  fill out the form with credit score, current amount of monthly debt, totalmonthly income, desired loan amount and home value. The application will calculate monthly debt to income ration and loan to value ratio. The applicant will then be matched with banks that can accommodate the applicant loan needs. 

To use the Loan Qualifier CLI simply clone the repository and run the **app_v2.py**:

Upon launching the Loan Analyzier CLI the user will follow these prompts:

![Loan Analyzer CLI](![https://onedrive.live.com/?cid=14C4696BEBFF683D&id=14C4696BEBFF683D%21261207&parId=14C4696BEBFF683D%21252061&o=OneUp])

## Contributors

Michelle Silver
supersilver1978@hotmail.com
*with help from Bootcamp*

---

## License

Berkeley Bootcamp project
