# Recomendation System

This project focuses on building a recommendation system using machine learning techniques. It includes exploratory data analysis (EDA), model training, evaluation, and results.

## Project Structure

-	**data/**: The dataset files should be placed here (not exist because of the size).
-	**explore.ipynb**: Jupyter Notebook with code for EDA and modeling.
-	**pyproject.toml**: Contains project dependencies and configurations for Poetry.
-	**poetry.lock**: Locks the specific versions of dependencies used in the project.
-	**README.md**: Project documentation and instructions.

## Installation

To set up the project environment and install all dependencies, follow the steps below.
Then copy your data files to the data folder.
Run pipeline.

### Prerequisites

	-	Python 3.10+ installed on your system.
	-	Poetry package manager for Python.

### Install Poetry

If you don’t have Poetry installed, you can install it using the following command:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Alternatively, refer to the official Poetry installation guide for more options.

### Set Up the Project Environment

1.	Clone the Repository
Clone the project repository to your local machine:

```bash
git clone https://github.com/lezhocheck/simple-recommendation-system.git
```

2.	Install Dependencies
Run the following command to install all project dependencies as specified in the pyproject.toml file:

```bash
poetry install
```

This command will create a virtual environment (if one doesn’t exist) and install all the required packages.

3.	Activate the Virtual Environment
To activate the virtual environment created by Poetry, run:

```bash
poetry shell
```
