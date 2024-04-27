# LLM-Langchain-Projects

Welcome to **LLM-Langchain-Projects**! This repository hosts two distinct projects that leverage advanced language model technologies. These projects are designed to demonstrate the power of LLMs (Large Language Models) in generating dynamic content and interacting with unstructured data like PDF files.

## Projects Overview

### 1. Generating blog content using Llama 2

This project enables automatic blog content creation based on user-specified topics and word counts. It is an excellent tool for content creators looking to generate initial drafts or gather ideas swiftly.

#### Features
- Generate blog content tailored to specific topics.
- Customize the length of generated content.

#### Technology Stack
- Streamlit
- Llama 2 LLM

#### Setup and Usage
To set up and run the project:

##### Clone the repository and navigate to the project directory
```bash
git clone <repository-url>
cd LLM-Langchain-Projects/Blog generation using Llama 2
```
##### Install dependencies
```bash
pip install -r requirements.txt
```
##### Run the Streamlit application
```bash
streamlit run app.py
```
# Querying PDF using Langchain and AstraDB

This application allows users to dynamically query any PDF document by asking relevant questions. Powered by an OpenAI LLM, this project utilizes advanced natural language processing to extract and summarize information from your PDF documents effectively.

## Features

- **Interactive PDF Querying:** Users can ask questions directly about the content of PDF documents and receive accurate answers.
- **Advanced Language Understanding:** Leverages the capabilities of OpenAI's LLM to understand and process complex queries.

## Getting Started

These instructions will guide you through setting up the project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook

### Installation

To set up this project, follow these steps:

Clone the repository:
   ```bash
   git clone <repository-url>
   cd LLM-Langchain-Projects/Querying PDF using langchain and AstraDB
   ```
Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
Here is how you can start using this project:
Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
Navigate to the project's directory and open the provided Jupyter notebook file.
Execute the notebook cells sequentially to interact with the PDF querying functionalities.

## Built With
- Jupyter Notebook - An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.
- OpenAI LLM - Utilizes machine learning models for natural language understanding.
- AstraDB - Used for scalable data storage and retrieval (depending on project configuration).
  
## Contributing
Contributions are what make the open-source community such a fantastic place to learn, inspire, and create. Any contributions you make are greatly appreciated.

### Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request
