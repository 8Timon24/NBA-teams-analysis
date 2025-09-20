# 🏀 NBA Teams Analysis

## Introduction
This repository contains a Jupyter Notebook project that analyzes NBA team statistics.  
The goal is to explore team performance across seasons and visualize key stats.  
This is done in the **`predstavitev_podatkov_v1.ipynb`** notebook.  

The other notebooks are helper files used to:
- Download the statistics from [basketball-reference.com](https://www.basketball-reference.com/)
- Process and clean the data so that it can be represented properly

## Contents
- **NBA_TEAMS/** – contains data about all of the teams from 1990–2024  
  (for some teams the data is missing because they were not active that year)
- **web_scraping_v1_FAIL.ipynb** and **web_scraping_v2_FAIL.ipynb** –  
  first two attempts to scrape data, failed because the website blocked requests after ~30 attempts
- **web_scraping_v3_SUCCESS.ipynb** – final and successful scraping attempt  
  (downloads individual HTMLs, takes some time to run)
- **obdelava_html.ipynb** – notebook for cleaning the HTML files, keeping only the required tables
- **vsi_podatki.pkl** – main dataset used by `predstavitev_podatkov_v1.ipynb`
- **predstavitev_podatkov_v1.ipynb** – **main notebook** where all visualization happens

## How to run
1. Make sure you have **Python 3.11+** installed.
2. Install Jupyter and required libraries:
   ```bash
   pip install jupyter pandas matplotlib seaborn
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
4. Open predstavitev_podatkov_v1.ipynb and run all the cells.
