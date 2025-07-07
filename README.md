# Retail_Analysis

A PySpark-based data processing and analysis project focused on extracting insights from retail datasets using a structured, test-driven, and modular approach.

## Project Structure

```
Retail_Analysis/
├── application_main.py           # Main driver script to run the application
├── conftest.py                   # Pytest configuration for test fixtures
├── test_retail_project.py        # Test cases for retail project logic
├── configs/
│   ├── application.conf          # Application configuration file
│   └── pyspark.conf              # PySpark-specific settings
├── Pipfile                       # Project dependency management
├── Pipfile.lock                  # Lock file for exact dependency versions
├── pytest.ini                    # Pytest settings
```

## Features

1. Modular PySpark Code for scalable and distributed data processing.
2. Configuration-Driven design using .conf files for flexibility.
3. Unit Testing enabled with pytest to ensure reliable logic.
4. Virtual Environment managed using pipenv.

## Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/your-username/Retail_Analysis.git
cd Retail_Analysis
```

### 2. Set Up Environment

Install dependencies using Pipenv:
```
pipenv install
pipenv shell
```

### 3. Run the Application
```
python application_main.py
```

### 4. Run Tests
```
pytest
```

##  Tech Stack

1. Python 3.11+
2. PySpark
3. Pytest
4. Pipenv

## Notes
1. Make sure Apache Spark is installed and configured if you're running this in a local or cluster environment.
2. Update configs/application.conf and configs/pyspark.conf as per your Spark cluster or local setup.
