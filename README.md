# Analysis of Polish Bankruptcy Companies Dataset
## Project Purpose
todo
## Data Source
The data was obtained from the UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data

## Dataset Description
The dataset is about bankruptcy prediction of Polish companies. The data was collected from Emerging Markets Information Service (EMIS, [https://www.emis.com/]), which is a database containing information on emerging markets around the world. The bankrupt companies were analyzed in the period 2000-2012, while the still operating companies were evaluated from 2007 to 2013.
Basing on the collected data five classification cases were distinguished, that depends on the forecasting period.

In the context of this work, the concept of bankruptcy is understood as a legal situation in which a company is no longer able to pay its debts and financial obligations to its creditors.

The source of base includes articles, news agency messages, the financial statements of companies, industry reports, stock quotes and statistics and analyzes macroeconomic data.

The set of characteristics considered in the classification process consists of 64 financial indicators.

Read more at: https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data

## Exploratory data analysis
In the project there are:
- 65 variables: 64 numeric and 1 objective variable,
- 43405 observations,
- 41322 missing cells = 1.5% missing cells 
## Prerequisites:
- Python 3.10 or higher

## Recreate the project environment on your computer
1. Install Git

    On Windows: Download and install Git from the official site: https://git-scm.com/download/win
    
    On Linux: On most Linux distributions, Git is available from the default package repository. Depending on your distribution, you can install Git with one of the following commands:
    - Debian/Ubuntu/MacOS: sudo apt-get install git
    - Fedora: sudo dnf install git
    - Arch Linux: sudo pacman -S git

2. Copy the project URL
    - On the project page, find the "Code" button and click on it. A menu should expand from under the button.
    - In this menu, find the HTTPS URL under the "Clone" heading. Click the button next to the URL to copy the address.

3. Clone the project
    - Open a terminal (Command Prompt on Windows, Terminal on Linux).
    - Navigate to the directory where you want to clone the project. You can do this with the
    <code>cd path/to/directory</code> command.
    - Paste the copied URL in the terminal after the <code>git clone </code> command, so that the whole thing looks like this: <code>git clone copied_URL </code>. Then press Enter.
    Git will now start cloning the project to your local directory.

4. Install virtual environment
    
    Windows:
    - Open command prompt
    - Navigate to your project directory
    - Once inside the project directory, create a new virtual environment by running: <code> python -m venv venv</code>
    - Activate the virtual environment <code>.\myvenv\Scripts\activate</code>

    Linux/MacOS:
    - Open Terminal
    - Navigate to your project directory
    - Once inside the project directory, create a new virtual environment by running: <code>python3 -m venv venv</code>
    - Activate the virtual environment: <code> source myvenv/bin/activate </code>

5. Install packages from requirements.txt file
    - Make sure your virtual environment is activated. You can tell if your environment is active by looking at your command line prompt. If it starts with (venv), then your environment is active.
    - Use pip to install the packages: <code> pip install -r requirements.txt </code>