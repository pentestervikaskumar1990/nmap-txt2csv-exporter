# Nmap to CSV Converter

A lightweight and efficient Python script that parses standard Nmap output from a text file (`.txt`) and converts it into a structured CSV file (`.csv`) for easy analysis and reporting.

## Features

-   **Simple & Lightweight:** Single Python script with no external dependencies.
-   **Interactive CLI:** Smart defaults for input and output filenames.
-   **Robust Parsing:** Accurately extracts data using regular expressions.
-   **Essential Data:** Parses IP address, port, protocol, state, service, and version.
-   **Error Handling:** Gracefully handles missing files and errors.
-   **Summary Feedback:** Shows number of open ports found after conversion.

## Installation

1.  **Prerequisites:** Ensure you have Python 3.6+ installed:
    ```bash
    python --version
    # or
    python3 --version
    ```

2.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/nmap-to-csv.git
    cd nmap-to-csv
    ```

## Usage

1.  **First, create an Nmap scan file:**
    ```bash
    nmap -sV -sC -T4 scanme.nmap.org -oN nmap.txt
    ```

2.  **Run the converter:**
    ```bash
    python3 nmap_to_csv.py
    ```

3.  **Follow the prompts:**
    - Press `Enter` for input file (`nmap.txt`)
    - Press `Enter` for output file (`nmap_results.csv`)

**Example output:**

📁 Repository Structure

