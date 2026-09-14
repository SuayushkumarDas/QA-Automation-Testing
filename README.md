# 🧪 QA Automation Testing

<p align="center">
  <b>Web UI Test Automation using Python & Selenium</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Selenium-WebDriver-green?logo=selenium&logoColor=white" alt="Selenium">
  <img src="https://img.shields.io/badge/Pytest-Test%20Framework-orange?logo=pytest&logoColor=white" alt="Pytest">
  <img src="https://img.shields.io/badge/Automation-Web%20Testing-purple" alt="Web Testing">
  <img src="https://img.shields.io/badge/Status-Active-success" alt="Status">
</p>

---

## 📌 Overview

**QA Automation Testing** is a Python-based web automation project developed to demonstrate the fundamentals of **automated software testing using Selenium WebDriver**.

The project focuses on automating browser interactions, executing web validation steps, and establishing a foundation for scalable UI test automation using **Python, Selenium, and Pytest**.

It is designed as a practical demonstration of core **QA automation concepts**, including browser automation, test execution, validation, and organized test assets.

---

## 🎯 Project Objectives

The primary objectives of this project are to:

* 🔹 Automate web browser interactions using Selenium WebDriver
* 🔹 Execute automated functional testing workflows
* 🔹 Validate web page behavior through automated checks
* 🔹 Use Python for test automation scripting
* 🔹 Establish a foundation for Pytest-based test execution
* 🔹 Maintain organized test cases and supporting project documentation
* 🔹 Demonstrate practical understanding of software QA and automation concepts

---

## 🛠️ Tech Stack

| Technology                | Purpose                                |
| ------------------------- | -------------------------------------- |
| 🐍 **Python**             | Automation scripting                   |
| 🌐 **Selenium WebDriver** | Browser automation                     |
| 🧪 **Pytest**             | Test execution framework               |
| 🌎 **Google Chrome**      | Automated browser                      |
| 🔧 **Git & GitHub**       | Version control and project management |

---

## 🔍 Current Automation Workflow

The current Selenium automation script demonstrates a basic browser automation flow:

```text
Start Test
    │
    ▼
Launch Google Chrome
    │
    ▼
Navigate to Web Page
    │
    ▼
Retrieve Page Title
    │
    ▼
Display Title
    │
    ▼
Wait for Execution
    │
    ▼
Close Browser
    │
    ▼
Test Complete
```

---

## 🧪 Automated Test

The current automation script is located at:

```text
scripts/
└── scripts/
    └── test_login.py
```

The script demonstrates:

* Starting a Chrome WebDriver session
* Navigating to a web URL
* Retrieving the browser page title
* Displaying the result
* Closing the browser session

### Example

```python
from selenium import webdriver
import time

driver = webdriver.Chrome()

driver.get("https://example.com")

print(driver.title)

time.sleep(3)

driver.quit()
```

---

## 📁 Project Structure

```text
QA-Automation-Testing/
│
├── 📂 screenshots/
│   └── .gitkeep
│
├── 📂 scripts/
│   ├── .gitkeep
│   ├── requirements
│   └── 📂 scripts/
│       └── test_login.py
│
├── 📂 test-cases/
│   └── .gitkeep
│
├── 📄 index.html
├── 📄 project-notes.md
├── 📄 README.md
└── 📄 requirements.txt
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SuayushkumarDas/QA-Automation-Testing.git
```

Navigate into the project:

```bash
cd QA-Automation-Testing
```

---

### 2️⃣ Create a Virtual Environment

It is recommended to use a Python virtual environment.

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Current dependencies:

```text
selenium
pytest
```

---

## ▶️ Running the Automation

Run the Selenium script directly with Python:

```bash
python scripts/scripts/test_login.py
```

The script will:

1. Open Google Chrome
2. Navigate to the configured URL
3. Retrieve the page title
4. Print the title in the terminal
5. Wait briefly
6. Close the browser

---

## 🧪 QA Concepts Demonstrated

This project provides hands-on exposure to fundamental QA automation concepts:

### 🔹 Browser Automation

Automating browser operations using **Selenium WebDriver**.

### 🔹 Functional Validation

Performing automated checks against expected web application behavior.

### 🔹 Test Automation Scripting

Writing reusable automation logic using **Python**.

### 🔹 Test Framework Exposure

Including **Pytest** as the project's testing framework dependency.

### 🔹 Test Organization

Maintaining separate directories for scripts, test cases, screenshots, and project documentation.

### 🔹 Version Control

Managing the automation project using **Git and GitHub**.

---

## 📊 Testing Approach

The project follows a basic automation-oriented testing workflow:

```text
Test Planning
     ↓
Test Scenario
     ↓
Automation Script
     ↓
Browser Execution
     ↓
Application Interaction
     ↓
Validation
     ↓
Result Observation
     ↓
Browser Cleanup
```

This provides a foundation for expanding the project into a more comprehensive automated testing framework.

---

## 📸 Screenshots

The `screenshots/` directory is included for storing test execution evidence and screenshots generated during future automation scenarios.

```text
screenshots/
```

---

## 📝 Test Cases

The `test-cases/` directory is maintained for documenting manual and automated test scenarios.

Potential test scenarios can include:

* Valid input testing
* Invalid input testing
* Navigation validation
* UI element validation
* Page title verification
* Functional workflow validation

---

## 🚀 Future Enhancements

The project can be extended into a more advanced QA automation framework by implementing:

* [ ] Page Object Model (POM)
* [ ] Proper Pytest test functions
* [ ] Automated assertions
* [ ] Login test automation
* [ ] Positive and negative test scenarios
* [ ] Explicit waits
* [ ] Screenshot capture on test failure
* [ ] HTML test reports
* [ ] Parameterized testing
* [ ] Test configuration management
* [ ] Cross-browser testing
* [ ] CI/CD integration using GitHub Actions
* [ ] Automated test execution pipelines

---

## 💼 Skills Demonstrated

### Software Testing

* Functional Testing
* Test Case Design
* Test Scenario Development
* UI Validation
* Test Execution
* Defect-oriented thinking

### Automation

* Selenium WebDriver
* Python Automation
* Browser Automation
* Pytest Exposure

### Development Tools

* Git
* GitHub
* Chrome WebDriver
* Command Line / PowerShell

---

## 🎓 Project Relevance

This project demonstrates practical exposure to **software quality assurance and web test automation** and is particularly relevant to entry-level roles such as:

* 🧪 QA Engineer
* 🔍 Test Analyst
* ⚙️ QA Automation Engineer
* 💻 Software Test Engineer
* 🧩 Functional Test Engineer
* 📊 Quality Engineering Associate

---

## 👨‍💻 Author

**Suayush Kumar Das**

B.Tech — Electronics & Communication Engineering
ITER, SOA University

📍 Bhubaneswar, India

🔗 **GitHub:**
https://github.com/SuayushkumarDas

---

## ⭐ Repository

If you find this project useful, consider giving the repository a ⭐.

**QA Automation Testing — Python | Selenium | Pytest**

Built to learn, automate, validate, and improve software quality. 🚀
