# 30 Days of Streamlit


## Installation

### Prerequisites

* [Python 3.10+](https://www.python.org/)

### Virtual Environment

Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html), after which we can create a dedicated Python virtual environment for the project:

```bash
# Create a virtual environment for Python 3.10
conda create -n 30-days-of-streamlit python=3.10

# Activate the environment
conda activate 30-days-of-streamlit

# Deactivate the environment, if needed
conda deactivate
```

### Python Dependencies

Install Python dependencies, including those needed for development:

```bash
pip install -r requirements-dev.txt
```

> **Note:** Make sure the Python virtual environment is active before installing requirements.


## Usage

Start the Streamlit demo application:

```bash
streamlit hello 
```

Start the Streamlit application:

```bash
streamlit run streamlit_app_day<SPECIFIC_DAY_NUMBER>.py

# For example, Day 2:
streamlit run streamlit_app_day2.py
```
