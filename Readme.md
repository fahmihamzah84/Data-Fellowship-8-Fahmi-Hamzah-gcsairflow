### Ingest data to GCS and Big Query, scheduled using Airflow

- First, you need to modify google_credentials.json or replace the file
- Modify the DAG (URL file to ingest, GCS Bucket, BigQuery table) inside dags folder. Open with VCS code with:
```bash
cd Data-Fellowship-8-Fahmi-Hamzah-gcsairflow && code .
```
- Build the container
```bash
docker compose up
```
- After airflow installed, you can open Airflow WebUI on [localhost](https://localhost:8080)
- Login using default username "airflow" and password "airflow"
