# Medallion Architecture Implementation

This repository demonstrates the implementation of a Medallion Architecture using Cassandra. The project processes sales data through Bronze, Silver, and Gold layers.

## Project Structure
- `main.py`: Python script for creating tables and processing data.
- `screenshots/`:screenshots of query outputs from Gold tables.

## How to Run
1. Prerequisites
Python 3.x installed
Cassandra database (e.g., DataStax Astra)
Required Python packages:
bash
Copy code
pip install cassandra-driver pandas requests
2. Steps to Execute
Clone this repository:

bash
Copy code
git clone https://github.com/aditya023sketch/medallion.git
cd medallion
Update the secure connect bundle:

Replace secure-connect-sales-data.zip with your secure connect bundle from Astra.
Open main.ipynb in a Jupyter Notebook or VS Code and execute all cells.


