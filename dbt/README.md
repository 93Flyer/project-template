# dbt

This folder will hold the dbt project for Stop 3 (staging -> intermediate -> marts on BigQuery).

Structure to build later:
- `models/staging/` : 1:1 with source tables, no business logic
- `models/intermediate/` : reusable transformations
- `models/marts/` : BI-ready tables, read by the dashboard
- `dbt_project.yml`, `packages.yml`

Never commit `profiles.yml` or any service-account `.json` key file. Both belong outside version control.