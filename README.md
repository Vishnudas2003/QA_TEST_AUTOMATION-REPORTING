# QA_TEST_AUTOMATION-REPORTING

qa_test_demo/
│
├── tests/
│   ├── test_login.py
│   └── test_navigation.py
│
├── reports/
│   └── test_results.csv
│
├── utils/
│   └── logger.py
│
├── app.py         # Flask UI (optional)
├── requirements.txt
├── README.md


QA Test Automation Demo

This is a lightweight QA automation demo using Python, Selenium, and optional Flask for reporting. It simulates manual and regression tests and generates structured logs for reporting.
Features:
Automated login and navigation testing
Test result logging (CSV)
Optional Flask web dashboard
Technologies:
Python, Selenium, Flask, logging, HTML
How to Run:
pip install -r requirements.txt
Run a test: python tests/test_login.py
View reports in /reports/ folder or Flask UI