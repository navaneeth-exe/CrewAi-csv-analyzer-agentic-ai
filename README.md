CSV Analyzer – Agentic AI (Day 3)

This project is part of the Agentic AI – Day 3 assignment.
The goal was to modify a multi-agent system to build a notebook-based CSV Analyzer tool using CrewAI and the Gemini API.

What this project does

Loads a CSV file

Shows dataset overview (rows, columns, head, tail, info)

Generates summary statistics

Detects missing values

Detects duplicates

Creates a correlation matrix

Automatically creates a dummy CSV file for testing

Provides a usage example

How it works

The notebook uses three agents:

Research Agent – Defines tool requirements

Coding Agent – Generates full code for the CSV Analyzer

Evaluation Agent – Reviews and suggests improvements

Tasks run sequentially using CrewAI.

Tech used

Python

CrewAI

Google Gemini API

Pandas

File

csv_analyzer.ipynb — Main notebook containing the whole workflow
