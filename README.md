# OWASP-ZAP Streamlit App

## Overview

This project is a web application that leverages the OWASP ZAP (Zed Attack Proxy) Python package for security testing. It provides a user-friendly interface built with Streamlit. The application offers the following features:

- Spider: Automatically crawls and discovers web application pages.
- Ajax Spider: Identifies and scans AJAX-based web applications.
- Active Scan: Scans the web application for potential vulnerabilities.
- Report Generation: Generates security reports in HTML and PDF formats.

## Getting Started

### Prerequisites

- Python: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/owasp-zap-streamlit-app.git
    cd owasp-zap-streamlit-app
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

To start the OWASP-ZAP Streamlit App, run the following command:

```bash
streamlit run app.py
