# IntelliExtract-AI

Harnessing LLM for Intelligent Information Extraction.

IntelliExtract-AI is an innovative application designed to facilitate interactive data analysis and visualization through natural language conversations with various sources,i.e. csv, text, pdf, database, web url. 

## Table of Contents

- [Introduction](#multiple-csv-chatapp-with-llm)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before getting started with the Multiple-CSV ChatApp with LLM, ensure you have the following prerequisites installed on your system:

- `Python 3.10`
- `Streamlit`
- `Pandasai` for data manipulation
- `Matplotlib` for data visualization
- The `python-dotenv` package for environment variable management
- An active OpenAI account with access to API services

## Installation

To set up the Multiple-CSV ChatApp with LLM on your local machine, follow these steps:

1. Clone the repository from GitHub:

    ```
    git clone https://github.com/your-username/your-repo-name
    cd your-repo-name
    ```

2. Create a conda environment with Python 3.10:

    ```
    conda create -p venv python==3.10 -y
    ```

3. Activate the created virtual environment:

    ```
    conda activate venv/
    ```

4. Install the required dependencies using pip:

    ```
    pip install -r requirements.txt
    ```

5. Create a `.env` file at the root of the project directory and add your OpenAI API key:

    ```
    OPENAI_API_KEY='YourOpenAIKeyHere'
    ```

## Getting Started

After completing the installation, you can start the Multiple-CSV ChatApp with LLM by running the Streamlit application:
    ```
    streamlit run your_app_file.py
    ```

## Usage

The Multiple-CSV ChatApp with LLM enables users to perform various data analysis tasks through an intuitive chat interface:

- **CSV File Upload**: Users can upload multiple CSV files and select one for analysis through a dropdown menu.
- **Natural Language Queries**: Engage in a chat-like interaction with the selected CSV file to ask questions, request summaries, or generate visualizations.
- **Data Visualization**: The application supports on-the-fly generation of charts and graphs based on the user's queries.

## Features

- **Multiple CSV Support**: Seamlessly switch between multiple uploaded CSV files for analysis.
- **LLM-Powered Insights**: Utilizes the OpenAI language model for interpreting natural language queries and generating meaningful responses.
- **Interactive Visualizations**: Generates dynamic matplotlib charts in response to user queries for a more engaging data analysis experience.
- **Streamlit Integration**: Offers a clean and responsive web interface for uploading files, entering queries, and displaying results.

## Contributing

We welcome contributions to the Multiple-CSV ChatApp with LLM project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your changes to your fork and submit a pull request.

Ensure your contributions are well-documented and follow the project's coding standards.
