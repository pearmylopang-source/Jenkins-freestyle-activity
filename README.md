# Jenkins Freestyle Activity

# Objective
This project demonstrates a Jenkins pipeline that automates:

- Cloning a GitHub repository
- Running a Python script to generate a freestyle quote
- Archiving the generated output file
- Viewing results in Jenkins stages

# Project Structure

- `script.py` → Python script that generates a random quote  
- `output/` → Folder where generated file is stored  
- `README.md` → Project documentation  

# Jenkins Pipeline Stages

#  1. Checkout
Pulls code from GitHub repository.

# 2. Generate Freestyle Quote
Runs Python script:

```bash
python script.py
