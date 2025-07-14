## pipenv install langchain_groq

## pipenv install crewai

## pipenv install crewai_tools


# Retail Property Investment Analysis System

## Overview

This project is a Python-based system for analyzing retail property investments using the CrewAI framework. It leverages AI agents to perform comprehensive market research and property analysis, providing data-driven investment recommendations for retail properties.

## Features

- **Market Research**: Identifies high-potential retail property investment locations by analyzing market trends, demographics, and local retail ecosystems.
- **Property Evaluation**: Assesses properties based on foot traffic, accessibility, proximity to complementary businesses, and economic development plans.
- **Financial Analysis**: Estimates rental yields, ROI, property valuation, and identifies renovation opportunities.
- **Risk Assessment**: Evaluates competitor landscapes, e-commerce impacts, regulatory challenges, and long-term growth barriers.
- **Comprehensive Reporting**: Generates detailed, investor-focused reports with executive summaries, financial projections, and risk analysis.

## Project Structure

- **`tools.py`**: Configures the `SerperDevTool` for web-based research.
- **`agents.py`**: Defines two AI agents:
  - `property_researcher`: A senior retail property investment analyst focused on identifying and analyzing high-potential retail properties.
  - `property_analyst`: A senior investment property research analyst responsible for creating investor-grade reports.
- **`tasks.py`**: Defines tasks for market research and property analysis, including detailed requirements for data collection, financial modeling, and reporting.
- **`crew.py`**: Orchestrates the workflow using the CrewAI framework, currently set up to execute the research task with the `property_researcher` agent.

## Prerequisites

- Python 3.8+
- Required Python packages:
  - `crewai`
  - `crewai_tools`
  - `langchain_groq`
- A valid API key for Grok (configured in `agents.py` via `ChatGroq`).
- A valid API key for SerperDevTool (configured in `tools.py`).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name



Final Projection

## Screenshots

- **Input Interface**  
  Allows users to enter region and investment focus to generate a comprehensive AI-driven property investment report.

  ![WhatsApp Image 2025-07-14 at 11 29 57 PM](https://github.com/user-attachments/assets/a556d81e-9f80-4dfe-be98-6c1dc7f8964f)


- **Research Results - Key Insights**  
  Displays an AI-generated property investment report for Hyderabad, including market overview, financial metrics, and economic development details.

  ![WhatsApp Image 2025-07-14 at 11 29 57 PM (1)](https://github.com/user-attachments/assets/1561ee00-cd05-42e3-9cd1-b244c167661c)


- **Research Results - Employment and Tech Growth**  
  Provides insights into tech job growth rate, startup proximity, and recent investments by major corporations.

  ![WhatsApp Image 2025-07-14 at 11 29 58 PM](https://github.com/user-attachments/assets/7bd4c945-14e5-47e5-a5b1-7901247650ed)


- **Research Results - Residential Demand and Recommendations**  
  Offers details on residential demand growth and tailored investment recommendations based on market analysis.

  ![WhatsApp Image 2025-07-14 at 11 29 58 PM (1)](https://github.com/user-attachments/assets/a1d7d2bd-c1e2-4a3d-8b2f-2822b3121444)


