# Synthetic Call Data Generation and Processing

## Project Overview

This project demonstrates how to generate synthetic call data using the `Faker` library in Python. The generated dataset includes various call details with some "dirty data" such as the caller's first and last names embedded within the `caller_notes` column. The project then uses `pandas` to extract these names into separate columns, cleaning the data for further analysis.

## Requirements

- Python 3.6 or higher
- `Faker` library
- `pandas` library

## Installation

To install the required libraries, run the following command:

```bash
pip install faker pandas
