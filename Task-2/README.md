# Task 2 – Deep Technical Blog on LangChain

This project explores **LangChain**, a powerful framework used to build applications powered by **Large Language Models (LLMs)**. The notebook demonstrates how to create modular AI pipelines using prompt templates, chains, memory, tools, and agents. The goal of this task is to understand how modern LLM applications are structured and how LangChain simplifies building intelligent systems.

## Objective
The objective of this project is to understand the LangChain framework and learn how to build applications powered by large language models. It focuses on exploring important components such as Prompt Templates, Chains, Memory, Tools, and Agents while implementing a step-by-step pipeline for LLM-based applications.

## Introduction
LangChain is a framework designed to help developers build applications using large language models such as Gemini, GPT, and others. Instead of writing simple prompts, LangChain allows developers to design dynamic and reusable AI workflows. It solves many common problems in LLM development including prompt management, workflow chaining, tool integration, memory handling, and agent-based reasoning. In this project, LangChain concepts are demonstrated through practical examples implemented in a Jupyter Notebook.

## Pipeline Flow
The LangChain workflow implemented in this project follows a simple pipeline:

User Input → Prompt Template → LLM → Chain Processing → Tool / Agent → Output

This modular architecture makes AI applications scalable, organized, and easier to maintain.

## Project Structure
Task-2.ipynb – Main notebook containing the LangChain implementation  
README.md – Project documentation

## Setup & Installation
Before running the notebook, install the required dependencies:

pip install langchain  
pip install langchain-google-genai  
pip install google-generativeai  
pip install python-dotenv

## API Key Setup
This project uses the Google Gemini API for accessing the language model. When running the notebook, you will be prompted to enter your API key.

Example code used in the notebook:

import os  
from getpass import getpass  

os.environ["GOOGLE_API_KEY"] = getpass("Enter your Gemini API Key: ")

You can generate your API key from:  
https://makersuite.google.com/app/apikey

## Features Implemented
This project demonstrates several important LangChain features including environment setup, prompt template creation, integration with the Gemini LLM, creation of chain-based workflows, tool usage, agent-based reasoning, and building an end-to-end AI pipeline.

## Technologies Used
Python  
LangChain  
Google Gemini API  
Jupyter Notebook

## Learning Outcomes
Through this project, you will understand how large language model pipelines work, how LangChain simplifies AI application development, how modular AI workflows are created, and how external tools can be integrated with language models to build intelligent systems.

## Author
Mohd Saqib

This project was developed as part of an AI/ML internship task focusing on LangChain and LLM-based application development.

If you found this project helpful, consider giving the repository a star.
