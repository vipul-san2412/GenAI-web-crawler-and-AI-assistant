# GenAI-web-crawler-and-AI-assistant
This repository contains the product developed during the OOSC hackathon at Indian Institute of Technology, Kanpur. The problem solved here was proposed by Overlayy in the GenAI domain.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Backstory](#backstory)
- [Learning](#learning)
- [Contact](#contact)

## Overview

### What is it?

This project was developed as part of the Overlayy problem statement proposed during the OOSC hackathon at IIT Kanpur. The hackathon was a 12-hour event, and our team spent this time developing a web crawler capable of scraping a provided website, extracting 10 highly relevant questions from the data on the webpage, and identifying the top 5 hyperlinks that contain answers pertinent to those questions. Every time   of the hackathon was utilized to the fullest by dedicating time for discussion, developement and validation.

### Why did we build it?

The project was designed to tackle the challenge of efficiently gathering and processing data from web pages, leveraging the power of large language models (LLMs) and generative AI (GenAI) to extract meaningful insights and information. This solution aims to simplify data extraction and analysis from web content, making it easier to generate useful and relevant information from large datasets.

## Features

- **Modular Code Structure:** The project follows the principle of modularity, with functions organized for easy readability and handling.
- **Recursive Web Scraping:** Extracts hyperlinks and data from web pages recursively, delving into in-depth hyperlinks.
- **Question Generation:** Utilizes Google's Gemini Pro GenAI to generate relevant questions from the webpage content.
- **Data Structures and Algorithms:** Implements Queue, Sets, Lists, Breadth-First Search (BFS), and Recursion for efficient data handling.
- **Model Initialization:** Multiple instances of Gemini Pro are initialized to avoid model overfitting.
- **Data Validation:** Pydantic is used to validate data, ensuring accuracy and consistency.

## Installation

* pip install requests
* pip install bs4
* pip install json
* pip install google-generativeai
* pip install sentence_transformers
* pip install langchain langchain_community
* pip install BeatifulSoup

## Usage 

* The product can be used to scan a website and look for potential questions that might arise with the solutions provided in the highlighted hyperlinks.

## Backstory

* We participated in the 12 hour hackathon to feel the thrill and the suspense of working under a deadline.
* The hackathon which started as fun turned out to be one of the most memorable moment because we realized our potential, unexplored until now.
* Even though 12 hour seems less, a well planned approach backed by good team with mutual respect and great communication, no task felt difficult.
* Initial 2 hours were spent only on rough sheets to understand the problem clearly and frame a rough outline about our upcoming 10 hour hackathon.
* Next 4 hours were spent on scrapping the website, building the pipeline and debugging the programs, also keeping in mind the enhancements.
* The last 6 hours were left for the iceberg ie LLMs and GenAI models. Langchain and RAG was a new term to us yet we managed to go through the articles, videos, vlogs and finally developed a fully furnished product.
  
## Learning

* The product involved working with JSON files, handling and manipulating them as and when required by the need of the flow.
* We spend a lot of time working on websites, extracting information, classes, tags to not miss any important information.
* LLMs and GenAI tools played a vital role in our project. Langchain framework was used to implement the features of RAG.
 ## Contact

Name: Shivam Mishra <br>
Email: shivam1602m@gmail.com

PS : All the team members of the group have been added as the contributor.
 
