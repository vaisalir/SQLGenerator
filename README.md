# Natural Language to SQL Query Generator

## Description
A web-based application that converts natural language queries into SQL statements.  
This project allows users to enter simple English questions and automatically generates the corresponding SQLite SQL query.

The application also includes query validation, export options, and a simple interactive interface built with Gradio.

---

## Overview
This project demonstrates how natural language processing techniques can be used to interpret user queries and generate structured SQL commands.

The system processes user input, identifies relevant database tables and columns, extracts conditions, and generates a valid SQL query. It also includes security checks to prevent dangerous or malicious SQL commands.

---

## Features
- Natural language to SQL query generation  
- SQLite schema-based query mapping  
- Security filtering for unsafe SQL keywords  
- Query history tracking  
- Export generated queries as:
  - PDF report
  - Text file
- Share generated queries through social media links  
- Interactive user interface using Gradio  

---

## Technologies Used
- Python  
- Transformers (Hugging Face)  
- Gradio  
- SQLite  
- Torch  
- ReportLab  
