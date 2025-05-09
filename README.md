# Datasheet Comparator

This project provides a tool to extract and compare technical specifications of electronic components based on their PDF datasheets.

The goal is to assist in evaluating whether a replacement part meets the requirements of an obsolete component, especially in regulated environments like medical device development.

## Features

- Text extraction from PDF datasheets using PyMuPDF
- Summarization and property comparison using the OpenAI API
- Tabular display of key differences
- Modular and extendable Jupyter Notebook implementation

## Requirements

- Python 3.11
- openai
- pymupdf
- pandas
- jupyterlab

## Usage

Run the notebook in Jupyter Lab. Make sure to set your OpenAI API key via environment variable `.env`.

