# 📦 Repository: open-lakehouse-platform-000a01bc

> **Visibility:** 🌐 Public | **Default Branch:** `main` | **Size:** 33.03 MB | **License:** `MIT`

- **GitHub Remote:** [https://github.com/Amit1092tiwari/open-lakehouse-platform-000a01bc](https://github.com/Amit1092tiwari/open-lakehouse-platform-000a01bc)
- **Total Blobs (Files):** 203
- **Total Trees (Directories):** 48
- **Pushed At:** 2026-11-22T15:04:24Z
- **Created At:** 2026-04-06T11:21:36Z

---

## 📝 Description
A containerized, vendor-neutral enterprise data platform replacing proprietary SaaS stacks with open-source engines (Spark, Kafka, Airflow, DuckDB, dbt Medallion, MinIO, and Superset/Grafana). Includes 20 Docker services and 90+ automated tests.

---

## 🛠️ File Extensions & Content Distribution

| File Type | Count |
| :--- | :--- |
| `.cs` | 46 files |
| `.py` | 44 files |
| `.yaml` | 27 files |
| `.md` | 12 files |
| `.tf` | 11 files |
| `.sql` | 9 files |
| `.yml` | 9 files |
| `(no extension)` | 6 files |

---

## ⚡ CI/CD Automation & Workflows

- ⚡ `cicd-pipeline.yml`
- ⚡ `nightly-e2e-pipeline.yml`

---

## 📂 Directory & File Hierarchy (Depth <= 4)

``text
open-lakehouse-platform-000a01bc/
├── .devcontainer
  ├── devcontainer.json
├── .dockerignore
├── .editorconfig
├── .env.example
├── .gitattributes
├── .github
  ├── CODE_OF_CONDUCT.md
  ├── CONTRIBUTING.md
  ├── ISSUE_TEMPLATE
    ├── bug_report.yml
    ├── feature_request.yml
  ├── pull_request_template.md
  ├── SECURITY.md
  ├── workflows
    ├── cicd-pipeline.yml
    ├── nightly-e2e-pipeline.yml
├── .gitignore
├── .prettierignore
├── .prettierrc
├── ai_vector_pipeline
  ├── run_vector_search_demo.py
  ├── vector_ingestion_engine.py
├── airflow
  ├── dags
    ├── batch_ingestion_dag.py
    ├── streaming_monitoring_dag.py
    ├── warehouse_transform_dag.py
  ├── Dockerfile
  ├── plugins
    ├── .gitkeep
  ├── requirements.txt
├── apps
  ├── ai_data_portal
    ├── app.py
    ├── static
      ├── app.js
      ├── index.html
      ├── styles.css
├── ARCHITECTURE.md
├── assets
  ├── architecture_diagram.png
  ├── full_flow_diagram.png
  ├── indian_market_cap_distribution.png
  ├── indian_stock_valuation_matrix.png
  ├── reliance_technical_indicators.png
├── bi_dashboards
  ├── bi_dashboard.py
├── CHANGELOG.md
├── CITATION.cff
├── data
  ├── indian_stock_market_summary.csv
  ├── RELIANCE_NS_historical_ohlcv.csv
├── dbt_medallion
  ├── dbt_project.yml
  ├── models
    ├── intermediate
      ├── _int_models.yml
      ├── int_orders_enriched.sql
    ├── marts
      ├── _marts_models.yml
      ├── dim_customers.sql
      ├── fct_daily_customer_orders.sql
    ├── staging
      ├── ecommerce
├── DEPLOYMENT_STRATEGIES.md
├── docker-compose.ci.yaml
├── docker-compose.kraft.yaml
├── docker-compose.lite.yaml
├── docker-compose.yaml
├── End_to_End_Data_Pipeline.ipynb
├── governance
  ├── atlas_stub.py
├── great_expectations
  ├── expectations
    ├── raw_data_validation.py
  ├── great_expectations.yaml
├── helm
  ├── e2e-pipeline
    ├── Chart.yaml
    ├── templates
      ├── _helpers.tpl
      ├── airflow.yaml
      ├── configmap.yaml
      ├── dotnet-api.yaml
      ├── kafka-producer.yaml
      ├── namespace.yaml
      ├── secrets.yaml
      ├── spark.yaml
    ├── values.yaml
    ├── values-aws.yaml
    ├── values-azure.yaml
    ├── values-gcp.yaml
    ├── values-onprem.yaml
├── index.html
├── Indian_Stock_Market_Analysis.ipynb
├── kafka
  ├── Dockerfile
  ├── producer.py
├── kubernetes
  ├── analysis-templates.yaml
  ├── argo-app.yaml
  ├── argo-rollouts-install.yaml
  ├── deployment.yaml
  ├── ingress.yaml
  ├── rollout-blue-green.yaml
  ├── rollout-canary.yaml
  ├── servicemonitors.yaml
  ├── services.yaml
├── LICENSE
├── Makefile
├── ml
  ├── feature_store_stub.py
  ├── mlflow_tracking.py
├── monitoring
  ├── grafana-deployment-dashboards.json
  ├── monitoring.py
  ├── prometheus.yml
  ├── prometheus_grafana_setup.md
├── packages
  ├── script.js
  ├── styles.css
├── pyproject.toml
├── QUICK_START.md
├── README.md
├── reports
  ├── daily_test_scenario_validation_report.md
├── requirements.txt
├── sample_dotnet_backend
  ├── appsettings.json
  ├── appsettings.Production.json
  ├── Dockerfile
  ├── README.md
  ├── src
    ├── DataPipelineApi
      ├── Controllers
      ├── DataPipelineApi.csproj
      ├── HealthChecks
      ├── Models
      ├── Options
      ├── Program.cs
      ├── Security
      ├── Services
├── scripts
  ├── deploy.sh
  ├── deploy-blue-green.sh
  ├── deploy-canary.sh
  ├── generate_market_visualizations.py
  ├── indian_stock_market_scraper.py
  ├── init_db.sql
  ├── init_warehouse.sql
  ├── run_daily_test_scenarios.ps1
  ├── run_daily_test_scenarios.py
  ├── run_e2e_pipeline.py
  ├── setup-advanced-deployments.sh
├── serve_wiki.py
├── snowflake
  ├── __init__.py
  ├── init_warehouse.sql
  ├── snowflake_connector.py
├── spark
  ├── Dockerfile
  ├── spark_batch_job.py
  ├── spark_streaming_job.py
├── storage
  ├── aws_s3_influxdb.py
  ├── hadoop_batch_processing.py
  ├── minio_influxdb.py
  ├── mongodb_streaming.py
  ├── redis_integration.py
├── terraform
  ├── argo-rollouts.tf
  ├── ec2.tf
  ├── eks.tf
  ├── load-balancer-controller.tf
  ├── networking.tf
  ├── outputs.tf
  ├── providers.tf
  ├── rds.tf
  ├── s3.tf
  ├── security.tf
  ├── terraform.tfvars.example
  ├── variables.tf
├── tests
  ├── __init__.py
  ├── test_ai_data_portal.py
  ├── test_ai_vector_pipeline.py
  ├── test_airflow_dags.py
  ├── test_data_validation.py
  ├── test_dbt_models.py
  ├── test_docker_infrastructure.py
  ├── test_kafka_producer.py
  ├── test_ml_and_governance.py
  ├── test_opensource_stack.py
  ├── test_pipeline_config.py
  ├── test_snowflake.py
  ├── test_spark_jobs.py
  ├── test_storage_sinks.py
  ├── test_warehouse_sql.py
├── warehouse
  ├── __init__.py
  ├── init_warehouse.sql
  ├── warehouse_connector.py
``
