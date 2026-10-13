# pythonfastapi

## Snowflake configuration

The default Snowflake database and schema are `PHARMA_DB.CLINICAL_TRIALS`.
Override them with `SNOWFLAKE_DATABASE` and `SNOWFLAKE_SCHEMA`, respectively.
The `/api/ask` and `/api/chat` endpoints use this configuration unless explicit
connection settings are provided to `/api/chat` or `/api/connect`.
