# VNDB Data Pipeline

An end-to-end data pipeline project that extracts visual novel data from the VNDB API, transforms it using dbt, and creates analytics dashboards.

## Project Goals
- Extract data from VNDB Kana v2 API
- Build a cloud data warehouse (BigQuery)
- Transform data using dbt
- Create analytics: Top VNs by year, genre trends, rating analysis
- Orchestrate with automated pipelines

## Technologies Used
- **Python** - Data extraction and loading
- **SQL** - Data transformation and analysis
- **dbt** - Analytics engineering
- **Google BigQuery** - Cloud data warehouse
- **Git/GitHub** - Version control

## Project Status
🚧 Phase 1: Foundation & Setup (In Progress)

## Setup Instructions
1. Clone this repository
2. Create virtual environment: `python -m venv vndbdev`
3. Activate venv: `source vndbdev/bin/activate` (Mac/Linux) or `vndbdev\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`

## Author
Stephen Camilon - Aspiring Data Engineer