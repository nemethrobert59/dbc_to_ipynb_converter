# DBC to IPYNB Converter

## Overview
This repository contains a Python script for converting Databricks notebook files (`.dbc`) into Jupyter notebook files (`.ipynb`). This tool is particularly useful for data scientists and engineers working with Apache Spark in Databricks and looking to transition or integrate their work with Jupyter notebooks.

## Origin of the Code
The initial version of this code was developed as part of the Data Science and Engineering with Spark XSeries on edX. The original code can be found at [this GitHub repository](https://github.com/buswedg/edX/blob/master/Data%20Science%20and%20Engineering%20with%20Spark%20XSeries/C1%20Introduction%20to%20Apache%20Spark/mooc-setup-master/dbc_to_ipynb.ipynb).

## Features
- Extracts `.dbc` files into a temporary directory.
- Parses and converts `.python` files within the extracted directories into `.ipynb` format.
- Handles custom markdown and code cells efficiently.
- Automatically cleans up temporary files post conversion.

## Installation
No installation is required. This script can be run directly in a Python environment where the required libraries (`zipfile`, `os`, `codecs`, `nbformat`, `json`, `re`) are installed.

## Usage
1. Clone this repository to your local machine.
2. Place your `.dbc` file in a known directory.
3. Update the `source_FileLocation` and `output_FileLocation` variables in the script with the locations of your `.dbc` file and where you want the `.ipynb` files to be saved, respectively.
4. Run the script in your Python environment.

## Dependencies
- Python 3.x
- `zipfile`, `os`, `codecs`, `nbformat`, `json`, `re` (These are typically included in standard Python installations)
