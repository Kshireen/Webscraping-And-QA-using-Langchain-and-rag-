# Intelligent Agents for Website Scraping and Query Answering

## Objective

Design and implement a set of intelligent agents that work together to accomplish the following tasks:

Scrape content from a specified website URL (www.knovatekinc.com) and save it in a structured format.

Utilize the scraped data to answer user queries about the website content.

## Input

Task 1: URL of the webpage.

Task 2: Any query regarding the scraped data.

## Output

Task 1: JSON file with scraped data.

Task 2: Answer to questions regarding Knovatek Inc's homepage.

## Task Overview

Agent 1: Data Scraping and Storage Agent

This agent is responsible for receiving a website URL from the user, scraping content from the website, and storing the scraped data in a structured JSON format. The agent should ensure the data is stored in a manner that facilitates efficient retrieval and processing for answering user queries.

Agent 2: Query Answering Agent

This agent will interact with a database to fetch relevant information in response to user queries about the website content. For this task, use any vector database solution for storing and querying the scraped data.

## Getting Started

To begin, follow the instructions provided in the Jupyter notebook file. Ensure you have the required dependencies installed by referring to the requirements file.

## Project Architecture

The project architecture consists of two main components: the data scraping and storage agent and the query answering agent. Each agent performs specific tasks to achieve the overall objective of scraping website data and answering user queries. The agents may communicate with each other or with external databases as needed.
