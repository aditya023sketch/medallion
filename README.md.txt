# Medallion Architecture Implementation

This repository demonstrates the implementation of a Medallion Architecture using Cassandra. The project processes sales data through Bronze, Silver, and Gold layers.

## Project Structure
- `main.py`: Python script for creating tables and processing data.
- `tables.cql`: CQL commands for creating keyspaces and tables.
- `screenshots/`: Contains screenshots of query outputs from Gold tables.

## How to Run
1. Install dependencies:
   ```bash
   pip install cassandra-driver
