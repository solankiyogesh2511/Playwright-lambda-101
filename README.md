# playwright-python-framework
Create Playwright Framework uisng (Python, playwright, PyTest, Page Object Model, HTML Reports)

Please follow below steps for framework understanding 

## Installation

To install the package run the following command:
```bash
pip install -r requirements.txt
```

•	**playwright** : playwright Libraries

•	**pytest** : Python UnitTest framework

•	**pytest-html** : PyTest HTML Reports

•	**pytest-playwright** : A pytest wrapper with fixtures for Playwright to automate web browsers.

•	**pytest-xdist** : Run Tests Parallel

## Running Tests

```bash
pytest
```

To Run tests parallel 
```bash
pytest -n=2
```

To Run tests on specfic browser, e.g firefox
```bash
pytest --browser-name firefox
```