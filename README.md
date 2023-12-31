# 30 Days of Streamlit

This repository contains the code for the [30 Days of Streamlit](https://30days.streamlit.app) challenge.

The latest version of the application is automatically deployed to [Streamlit Cloud](https://streamlit.io/cloud) and available online at https://30-days-of-app-sdhefnmqknadxy3zrxiak8.streamlit.app/.


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
# Latest version of the app
streamlit run streamlit_app.py
```


## License

Copyright (c) 2023 [Markku Laine](https://markkulaine.com)

This software is distributed under the terms of the [MIT License](https://opensource.org/license/mit/). See [LICENSE](./LICENSE) for details.
