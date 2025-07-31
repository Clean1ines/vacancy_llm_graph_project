# Vacancy Scraper & LLM Enricher to Graph Database

## Project Overview

This project aims to develop a semi-automated solution for collecting job vacancy data from various sources (HH.ru, Habr Career, Telegram channels), enriching it with structured insights using a Large Language Model (LLM) through a manual interaction process, and storing the processed, interconnected information in a Graph Database for advanced analysis.

## Motivation & Personal Goal

This is not just a portfolio piece; it's a **working tool** designed for in-depth job market analysis. My primary goal is to leverage this project for:
* **Detailed Vacancy Analysis:** Decomposing job descriptions to understand true requirements.
* **Skill Gap Identification:** Pinpointing specific skills needed for target roles, aiding in self-education.
* **Interview Preparation:** Extracting common tasks and expectations to prepare effectively.
* **Career Path Planning:** Analyzing connections between roles, companies, and required skills in the job market.
* **Deciding on Applications:** Efficiently filtering and assessing if a vacancy is worth my time and effort.

The project demonstrates proficiency in:
* **System Analysis:** Full SDLC approach, requirements gathering, system design.
* **Ontology & Graph Data Modeling:** Designing a robust graph schema for complex data relationships.
* **Data Engineering (ETL):** Designing data pipelines (Extract, Transform, Load) for diverse sources, data validation, and structured storage.
* **LLM Engineering:** Crafting effective prompts for semi-automated data extraction from unstructured text.
* **Technical Writing:** Producing clear, structured, and comprehensive technical documentation.

## Project Workflow (SDLC Approach)

This project strictly follows an industry-standard Software Development Life Cycle (SDLC) adapted for a solo, portfolio context. Key phases include:
1.  **Planning & Requirements Analysis (Discovery):** Defining goals, gathering functional and non-functional requirements, initial scope, and workflow design.
2.  **Design & Architecture:** High-level system design, module interdependencies, detailed data modeling (including graph ontology and JSON schema).
3.  **Development & Implementation:** Coding modules, integrating components, unit testing, continuous integration principles.
4.  **Testing & Quality Assurance:** Unit, integration testing, data validation against schemas.
5.  **Deployment & Release (Conceptual/Personal Use):** Planning for application packaging and use.
6.  **Maintenance & Evolution:** Considering future enhancements, logging, and monitoring.

## Key Features

* **Multi-Source Scraping:** Support for HH.ru, Habr Career, and Telegram job descriptions.
* **Hybrid Data Extraction:** Automated scraping of structured fields, complemented by LLM-powered extraction from unstructured text.
* **Semi-Automated LLM Integration:** Manual copy-paste interaction with LLM (e.g., Google Gemini) for rich data enrichment, bypassing costly API access while demonstrating LLM prompt engineering skills.
* **Graph Database Modeling:** Design and generation of import scripts for a Graph Database (e.g., Neo4j) to represent and query complex relationships between jobs, skills, companies, and roles.
* **Structured Data Output:** Saving fully decomposed and enriched vacancies in a validated YAML format.
* **Console-based UI Simulation:** An interactive command-line interface that guides the user through the semi-automated enrichment process.

## Getting Started / Setup Guide

To get this project up and running locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Clean1ines/vacancy_llm_graph_project.git](https://github.com/Clean1ines/vacancy_llm_graph_project.git)
    cd vacancy_llm_graph_project
    ```
2.  **Set Up Python Virtual Environment:**
    ```bash
    python -m venv .venv
    # For Windows (PowerShell):
    .venv\Scripts\Activate.ps1
    # For Linux/macOS:
    source .venv/bin/activate
    ```
3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run Code Quality Checks (Optional, but recommended):**
    * **Code Formatting with Black:**
        ```bash
        black .
        ```
    * **Code Linting with Flake8:**
        ```bash
        flake8 .
        ```
    * **Run Tests (Once implemented):**
        ```bash
        pytest
        ```

## Project Management & Documentation

This project follows an agile approach with transparent task tracking and comprehensive documentation.

* **Task Board (Trello):** For a detailed backlog, current sprint tasks, and progress tracking, please visit our [Trello Board](https://trello.com/invite/b/688b46232de761ea2ffa7b73/ATTI5b6ca8361f659cf0f2dac86a45aa5953F0FF2463/trello).
* **Project Wiki (Notion)::** All comprehensive documentation, including detailed requirements, architectural decisions, and graph ontology, is available in our [Notion Workspace](https://trello.com/invite/b/688b46232de761ea2ffa7b73/ATTI5b6ca8361f659cf0f2dac86a45aa5953F0FF2463/trello).

## Current Technical State

*(This section will be updated as the project progresses to reflect implemented modules and their status.)*

## How to Contribute (Conceptual for Solo Project)

*(If this were an open-source project, contribution guidelines would go here. For a solo project, this section can be used to reflect on collaboration practices.)*

## License

*(Standard MIT or other license)*