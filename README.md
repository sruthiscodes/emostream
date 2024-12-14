# Scalable Emoji System

This project implements a highly scalable, real-time emoji system, built using Flask, Kafka, WebSockets, and Apache Spark for real-time data processing and monitoring.

# Prerequisites
Before running the application, make sure you have the following installed and running:
- **Python 3.10+**
- **Apache Kafka (version 3.9.0+)**
- **Zookeeper (version 3.9.3+)**
- **Apache Spark (version 3.5.3+)**

### Recommended: Virtual Environment Setup

It is recommended to use a virtual environment to isolate dependencies. Follow these steps to set up the environment:

1. **Install Python 3.10+** (if not already installed). You can download it from [python.org](https://www.python.org/downloads/).

2. **Create a virtual environment**:
   In your project directory, create a virtual environment using Python 3.10:
   ```bash
   python3.10 -m venv venv
   ```

3. **Activate the virtual environment:**:
    On macOS/Linux:
    ```bash
    source myenv/bin/activate
    ```

    On Windows:
    ```bash
    myenv\Scripts\activate
    ```

## Install dependencies ##
Install dependencies by running
```
pip install -r requirements.txt
```

## Run each python file ##
Run all four python files by executing
```
python *filename*.py
```