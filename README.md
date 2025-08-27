# Nmap TXT to CSV Converter
A lightweight and efficient Python script designed to parse standard nmap command output from a text file (.txt) and convert it into a structured, easy-to-analyze Comma-Separated Values file (.csv).

# Description
This tool solves a common problem for security professionals, network administrators, and pentesters: making Nmap scan results more accessible. While Nmap's output is rich with information, it's not ideal for data analysis, reporting, or importing into other tools. This converter extracts key data points (IP, Port, Protocol, State, Service, and Version) and organizes them into a clean CSV format, ready for spreadsheets, databases, or further processing.

# Features
**Simple & Lightweight: **A single Python script with no external dependencies beyond the standard library.
**Interactive CLI: **Prompts the user for input and output filenames with smart defaults.
**Robust Parsing: **Uses regular expressions to accurately extract data from typical Nmap output.
**Error Handling: **Gracefully handles missing files and unexpected input errors.
**Summary Feedback: **Provides a summary of the conversion, including the number of open ports found.
