Build an end‑to‑end analytics engineering project using Postgres, dbt, and Python. This project focuses on foundational skills: data modeling, medallion architecture, ingestion, testing, and documentation.
Primary Goals
    • Practice dbt fundamentals
    • Build bronze → silver → gold layers
    • Load CSV data into Postgres
    • Create business‑ready analytics models
    • Produce dashboards and documentation
Package everything into a portfolio‑ready GitHub repo
## Project Structure

```
ecommerce_analytics/
├── data/                 # Raw CSV files
├── dbt/
│   ├── models/
│   │   ├── bronze/       # Raw data layer
│   │   ├── silver/       # Cleaned & transformed
│   │   └── gold/         # Business-ready models
│   ├── tests/            # dbt tests
│   └── dbt_project.yml
├── scripts/              # Python ingestion & utilities
├── dashboards/           # Documentation & visualizations
└── README.md
```

## Getting Started

1. **Prerequisites**: Python 3.8+, PostgreSQL, dbt-core
2. **Setup**: Clone repo, install dependencies (`pip install -r requirements.txt`)
3. **Configure**: Set database credentials in `profiles.yml`
4. **Run**: `dbt run` to execute the pipeline
5. **Test**: `dbt test` to validate data quality

## Key Features

- **Data Ingestion**: Python scripts load CSV data into bronze layer
- **Medallion Architecture**: Three-layer transformation approach
- **Quality Assurance**: dbt tests ensure data integrity
- **Documentation**: Auto-generated dbt docs and model lineage

## Deliverables

- Production-ready dbt project with full documentation
- Sample dashboard demonstrating analytics capabilities
- Complete data pipeline from ingestion to insights