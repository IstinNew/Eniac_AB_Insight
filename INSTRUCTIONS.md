# Instructions for Eniac A/B Testing Project

## Setup Instructions
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/YOUR_GITHUB_USERNAME/Eniac-A-B-testing.git
    cd Eniac-A-B-testing
    ```
2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```
3. **Prepare the Environment**:
    Make sure you have Jupyter Notebook installed. If not, you can install it via:
    ```sh
    pip install notebook
    ```

## Running the Analysis
1. ## Commonly Used Libraries
This project makes use of few of the below commonly used libraries:
- **Pandas**: Data manipulation and analysis.
  - Installation: `pip install pandas`
  - Import: `import pandas as pd`
- **NumPy**: Numerical computing and array operations.
  - Installation: `pip install numpy`
  - Import: `import numpy as np`
- **Matplotlib**: Data visualization.
  - Installation: `pip install matplotlib`
  - Import: `import matplotlib.pyplot as plt`
- **Seaborn**: Statistical data visualization.
  - Installation: `pip install seaborn`
  - Import: `import seaborn as sns`
- **SciPy**: Scientific computing.
  - Installation: `pip install scipy`
  - Import: `import scipy.stats as stats`
- **scikit-learn**: Machine learning and data mining.
  - Installation: `pip install scikit-learn`
  - Import: `from sklearn.model_selection import train_test_split`
- **Statsmodels**: Statistical modeling and hypothesis testing.
  - Installation: `pip install statsmodels`
  - Import: `import statsmodels.api as sm`
- **Jupyter Notebook**: Interactive computing and data analysis.
  - Installation: `pip install notebook`
  - Usage: `jupyter notebook`
- **Plotly**: Interactive graphing library.
  - Installation: `pip install plotly`
  - Import: `import plotly.express as px`
- **SQLAlchemy**: SQL toolkit and ORM library.
  - Installation: `pip install sqlalchemy`
  - Import: `from sqlalchemy import create_engine`

2. **Launch Jupyter Notebook**:
    ```sh
    jupyter notebook "Eniac AB Test.ipynb"
    ```
3. **Follow the Steps in the Notebook**:
    - The notebook is divided into sections that walk you through the data exploration, analysis, and chi-square test.
    - Ensure to run each cell sequentially for a smooth execution of the analysis.

## Interpretation
- Check the `Chart.png` file for a graphical representation of the A/B test results.

## Contribution Guidelines
1. **Fork the Repository**:
    Click the “Fork” button at the top-right of the repository page to create a copy of this repository under your GitHub account.
2. **Clone Your Fork**:
    ```sh
    git clone https://github.com/YOUR_GITHUB_USERNAME/Eniac-A-B-testing.git
    cd Eniac-A-B-testing
    ```
3. **Create a Branch**:
    ```sh
    git checkout -b your-feature-branch
    ```
4. **Make Your Changes**:
    Make your changes and commit them with appropriate messages.
5. **Push Your Changes**:
    ```sh
    git push origin your-feature-branch
    ```
6. **Create a Pull Request**:
    Go to your forked repository on GitHub and click the “New Pull Request” button to submit your changes for review.
