# Loan Qualifer Application

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans. When the user find the loans that they qualify for the user can save as a csv, opt out, and have their path saved. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```


---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```
Here is an example of the app in use 

![Loan Qualifier Prompts](https://github.com/Tmccoy22/loan_qualifier_app2/blob/main/Images/Screen%20Shot%202022-11-30%20at%2012.51.27%20PM.png) 

---

## Contributors

DU Starter Code
Terrence McCoy

Mayeb ET Home loans

---

## License

MIT