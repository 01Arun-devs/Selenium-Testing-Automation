<<<<<<< HEAD
# Test Automation of Banking Project – Guru99

![Python](https://img.shields.io/badge/Python-blue)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-green)
![pytest](https://img.shields.io/badge/pytest-Framework-yellow)
![Browser](https://img.shields.io/badge/Browser-Firefox-orange)
![Automation](https://img.shields.io/badge/Test-Automation-success)
![GitHub](https://img.shields.io/badge/GitHub-Project-black)

# Test Automation of Banking Project – Guru99 (Selenium + Python + Firefox)

## Project Overview

This project demonstrates automated functional testing of the Guru99 Banking Demo Application using Selenium WebDriver with Python and Mozilla Firefox.

The objective of this project was to simulate a real-world corporate testing environment by automating test cases across multiple banking modules. The automation validates system functionality, input validation, alert handling, and banking operations.

A total of **111 test cases across 9 modules** were automated, with **107 passing and 4 bugs identified and documented**.

Application under test:
https://demo.guru99.com/V4/

---

## Modules Automated

The following banking modules were automated:

| Module               | Description                                         |
| -------------------- | --------------------------------------------------- |
| New Customer         | Add new customers with personal and contact details |
| Edit Customer        | Modify customer information                         |
| Delete Customer      | Delete existing customers                           |
| New Account          | Create new savings or current accounts              |
| Edit Account         | Modify account details                              |
| Delete Account       | Delete existing accounts                            |
| Balance Enquiry      | Check account balance                               |
| Mini Statement       | View recent transactions                            |
| Customized Statement | View filtered transaction history                   |

---

## Test Automation Approach

* **Automation Tool**: Selenium WebDriver
* **Programming Language**: Python
* **Test Framework**: pytest
* **Browser Used**: Mozilla Firefox
* **WebDriver**: GeckoDriver

### Automation Strategy

* Automated test cases using Selenium WebDriver
* Used assertions to validate expected results
* Handled browser alerts using WebDriverWait and Expected Conditions
* Implemented reusable test methods
* Used explicit waits for synchronization
* Validated form inputs, alerts, and system responses

---

## Tools and Technologies Used

* Python
* Selenium WebDriver
* pytest
* Mozilla Firefox
* GeckoDriver
* Git and GitHub
* Excel (Test case management and bug tracking)

---

## Test Execution Summary

| Module               | Total Cases | Passed  | Failed |
| -------------------- | ----------- | ------- | ------ |
| New Customer         | 26          | 22      | 4      |
| Edit Customer        | 21          | 21      | 0      |
| Delete Customer      | 7           | 7       | 0      |
| New Account          | 14          | 14      | 0      |
| Edit Account         | 7           | 7       | 0      |
| Delete Account       | 7           | 7       | 0      |
| Balance Enquiry      | 7           | 7       | 0      |
| Mini Statement       | 7           | 7       | 0      |
| Customized Statement | 16          | 16      | 0      |
| **Total**            | **111**     | **107** | **4**  |

---

## Project Structure

```id="yl05bn"
Selenium-Python-Automation/
│
├── Account/
│   ├── newAccount.py
│   ├── editAccount.py
│   └── deleteAccount.py
│
├── Customer/
│   ├── newCustomer.py
│   ├── editCustomer.py
│   └── deleteCustomer.py
│
├── Balance/
│   ├── balanceEnquiry.py
│   ├── miniStatement.py
│   └── customisedStatement.py
│
├── README.md
└── requirements.txt
```

---

## Key Automation Features Implemented

* Automated login functionality
* Automated customer management testing
* Automated account management testing
* Input validation testing
* Alert handling automation
* Reset button validation
* Explicit waits using WebDriverWait
* Reusable automation methods
* Functional UI automation testing

---

## Example Automation Scenario

Delete Account validation test:

* Open Guru99 Banking Application
* Login using manager credentials
* Navigate to Delete Account page
* Enter account number
* Handle confirmation alert
* Validate system response

---

## Installation and Setup

### Step 1: Clone repository

```id="k8d1sd"
git clone https://github.com/01Arun-devs/Selenium-Python-Automation.git
```

### Step 2: Navigate to project folder

```id="7u3n2u"
cd Selenium-Python-Automation
```

### Step 3: Install dependencies

```id="t3cmwj"
pip install -r requirements.txt
```

### Step 4: Install GeckoDriver

Download from:
https://github.com/mozilla/geckodriver/releases

Add GeckoDriver to system PATH.

### Step 5: Run tests

```id="wbhl5q"
pytest
```

---

## Challenges Faced and Solutions

Challenge: Difficulty locating correct web elements
Solution: Used browser developer tools to inspect element attributes

Challenge: Handling browser alerts
Solution: Used WebDriverWait with Expected Conditions to handle alerts properly

Challenge: WebDriver configuration issues
Solution: Installed and configured GeckoDriver correctly

Challenge: Code repetition
Solution: Created reusable methods to improve code maintainability

---

## Skills Demonstrated

* Selenium WebDriver automation using Firefox
* Functional test automation
* Test case design and implementation
* Input validation testing
* Alert handling automation
* Automation framework organization
* Debugging and problem solving
* Version control using Git and GitHub

---

## Project Outcome

* Automated 111 real-world banking test cases
* Identified and documented 4 bugs
* Successfully automated 9 banking modules
* Demonstrated real-world automation testing workflow

---

## Author

Arun Kumar

---

## References

* Guru99 Banking Demo Application
* Selenium Official Documentation
* Python Official Documentation
=======
# Selenium-Testing-Automation
>>>>>>> ae6ce3ca2dc30d7eb83da28f0985c254edf7c5af
