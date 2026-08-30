# Survey Feedback Analyzer

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
# Survey Feedback Analyzer

## Project Overview

Survey Feedback Analyzer is a Python-based project designed to analyze textual survey feedback and extract meaningful insights from customer responses.

## Problem Statement

Analyzing textual feedback is important for understanding user opinions, improving services, and extracting useful insights. This project uses core Python programming concepts to clean feedback data, analyze words, calculate ratings, and summarize survey responses.

## Objectives

- Store survey feedback using a dictionary of lists.
- Allow users to add new feedback entries.
- Clean textual feedback.
- Count feedbacks containing specific words.
- Calculate the average rating.
- Find the longest feedback comment.
- Identify unique words used across all feedbacks.
- Sort feedback entries based on rating.

## Technologies Used

- Python
- Jupyter Notebook
- Core Python
- Lists
- Dictionaries
- Loops
- Conditional Statements
- Functions
- String Operations
- `zip()`
- `sorted()`
- `set()`

## Features

### 1. Preloaded Feedback Data

The project starts with 10 predefined survey feedback entries containing names, feedback comments, and ratings.

### 2. Add New Feedback

Users can enter additional feedback along with the name and rating.

### 3. Text Cleaning

The feedback is cleaned by:

- Removing punctuation
- Removing extra spaces
- Removing leading and trailing spaces
- Converting text to lowercase

### 4. Word Count Analysis

The program counts how many feedback entries contain:

- good
- poor
- excellent

The word matching is case-insensitive.

### 5. Average Rating

The program calculates the average rating across all feedback entries.

### 6. Longest Feedback

The program identifies the feedback comment containing the highest number of words.

### 7. Unique Words

The program extracts unique words used across all feedback entries without duplicates.

### 8. Feedback Sorting

The feedback entries can optionally be sorted from the highest rating to the lowest rating using `zip()` and `sorted()`.

## Sample Output

The program displays:

- Final cleaned feedback data
- Number of feedbacks containing "good"
- Number of feedbacks containing "poor"
- Number of feedbacks containing "excellent"
- Average rating
- Longest feedback
- Word count of the longest feedback
- List of unique words
- Sorted feedback entries

## Learning Outcomes

Through this project, I practiced:

- Python dictionaries and lists
- For loops
- While loops
- Conditional statements
- User-defined functions
- String manipulation
- Data cleaning
- Sets
- `zip()`
- `sorted()`
- Basic data analysis

## Author

Katravath Naveen
