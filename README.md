# Group43 Week 4 Assignment

This repository contains Jupyter Notebooks and code for various practical tasks and experiments conducted as part of the Group43 Week 4 Assignment. The focus areas include Python sorting algorithms, AI-assisted code, data analysis, and Selenium test automation.

---

## Table of Contents

- [Task 1: Sorting Algorithms](#task-1-sorting-algorithms)
- [Task 2: Data Analysis with Pandas and Scikit-learn](#task-2-data-analysis-with-pandas-and-scikit-learn)
- [Task 3: Web Automation with Selenium IDE](#task-3-web-automation-with-selenium-ide)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

---

## Task 1: Sorting Algorithms ([Task1.ipynb](Task1.ipynb))

This notebook explores two approaches to sorting a list of dictionaries by a specified key:

1. **Manual Bubble Sort Implementation**  
   - Implements a bubble sort algorithm to sort a list of dictionaries.
   - Does not use built-in sorting or AI tools.
   - Useful for understanding basic sorting logic and algorithm efficiency.

2. **AI-Generated Sorting (Using Built-in Functions)**  
   - Uses Python’s `sorted()` function with a lambda for key selection.
   - Demonstrates how AI/code completion tools can generate more efficient solutions.

3. **Efficiency Comparison**  
   - Benchmarks both methods using the `time` module.
   - Analyzes performance differences between manual and built-in approaches.

---

## Task 2: Data Analysis with Pandas and Scikit-learn ([week4.ipynb](week4.ipynb))

This notebook focuses on basic data science and exploratory data analysis tasks:

- Loads a dataset (569 rows, 31 columns).
- Displays the first 5 rows for a quick preview.
- Explores features such as mean radius, texture, perimeter, area, and more.
- Intended as a starting point for deeper analysis or machine learning tasks.

---

## Task 3: Web Automation with Selenium IDE ([seleniumIDE.ipynb](seleniumIDE.ipynb))

This notebook demonstrates automated web UI testing using Selenium:

- **Test Target**: [the-internet.herokuapp.com/login](https://the-internet.herokuapp.com/login)
- **Features**:
  - Automates login attempts with valid and invalid credentials.
  - Captures screenshots for each test.
  - Asserts expected outcomes (success or error messages).
  - Uses headless Chrome for efficient test execution.
- **Use Cases**:
  - Demonstrates basics of browser automation for QA.
  - Shows how to validate login flows and error handling.

---

## Getting Started

Clone this repository:

```bash
git clone https://github.com/Ar-murithi/Group43_wk4_Assignment.git
cd Group43_wk4_Assignment
```

---

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas, scikit-learn
- selenium
- Chrome browser and ChromeDriver (for Selenium tasks)
- IPython (for display functions in Selenium notebook)

Install requirements (recommended in a virtual environment):

```bash
pip install -r requirements.txt
```
*Note: If `requirements.txt` is missing, install packages individually as shown above.*

---

## How to Run

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open the desired notebook (`Task1.ipynb`, `week4.ipynb`, or `seleniumIDE.ipynb`) and run the cells.

---

## Contributing

Contributions are welcome! Please fork the repository and open a pull request with your proposed changes.

---

## License

This repository is for educational purposes. See the LICENSE file for details (if available).

---

## More Information

For details on each notebook, consult the inline documentation and comments within each `.ipynb` file.

---
