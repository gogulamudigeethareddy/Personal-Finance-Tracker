# Personal-Finance-Tracker

## Overview
The Personal-Finance-Tracker is a Python-based application that helps you manage and track your personal finances. You can add income and expense entries, view transactions within a specified date range, and visualize your financial data over time.

## Features
- Add new income and expense entries
- View transactions and summary within a specified date range
- Visualize income and expense trends over time using matplotlib

## Requirements
- Python 3.12
- pandas
- matplotlib
- numpy

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Personal-Finance-Tracker.git
    cd Personal-Finance-Tracker
    ```

2. Install the required packages using pipenv:
    ```sh
    pipenv install
    ```

## Usage
1. Run the application:
    ```sh
    pipenv run python main.py
    ```

2. Follow the on-screen prompts to add entries, view transactions, and visualize data.

## File Structure
- [data_entry.py](http://_vscodecontentref_/1): Contains functions for getting user input for date, amount, category, and description.
- [main.py](http://_vscodecontentref_/2): Main script that handles user interaction, data processing, and visualization.
- [finance_data.csv](http://_vscodecontentref_/3): CSV file where financial data is stored.
- [Pipfile](http://_vscodecontentref_/4) and [Pipfile.lock](http://_vscodecontentref_/5): Pipenv files for managing dependencies.

## Example
```sh
1. Add a new Entry
2. View Transactions and summary
3. Exit
Enter your choice(1 to 3): 2
Enter the start date (dd-mm-yyyy): 01-01-2024
Enter the end date (dd-mm-yyyy): 31-12-2024