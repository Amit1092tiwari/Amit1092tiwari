# 📦 Repository: cross-rdbms-dataops-toolkit

> **Visibility:** 🌐 Public | **Default Branch:** `main` | **Size:** 3 MB | **License:** `MIT`

- **GitHub Remote:** [https://github.com/Amit1092tiwari/cross-rdbms-dataops-toolkit](https://github.com/Amit1092tiwari/cross-rdbms-dataops-toolkit)
- **Total Blobs (Files):** 123
- **Total Trees (Directories):** 39
- **Pushed At:** 2026-11-22T16:57:16Z
- **Created At:** 2022-04-03T11:45:16Z

---

## 📝 Description
No description provided.

---

## 🛠️ File Extensions & Content Distribution

| File Type | Count |
| :--- | :--- |
| `.md` | 56 files |
| `.sql` | 34 files |
| `.png` | 24 files |
| `.yml` | 5 files |
| `.py` | 2 files |
| `.sh` | 1 files |
| `(no extension)` | 1 files |

---

## ⚡ CI/CD Automation & Workflows

- ⚡ `daily-db-audit.yml`
- ⚡ `db-ci.yml`

---

## 📂 Directory & File Hierarchy (Depth <= 4)

``text
cross-rdbms-dataops-toolkit/
├── .github
  ├── ISSUE_TEMPLATE
    ├── bug_report.yml
    ├── feature_request.yml
  ├── PULL_REQUEST_TEMPLATE.md
  ├── workflows
    ├── daily-db-audit.yml
    ├── db-ci.yml
├── CONTRIBUTING.md
├── data_dictionary_scripts.md
├── data_validation_scripts.md
├── docker-compose.yml
├── docs
  ├── OPERATIONAL_ARCHITECTURE.md
├── greenplum
  ├── data_dictionary
    ├── data_dict_dump.sql
  ├── schemadiff
    ├── simple_schema_dump.sql
├── img
  ├── 01_schemadiff_side_by_side.png
  ├── 02_data_dictionary_in_xl.png
  ├── 03_data_dictionary_edit_and_run_script.png
  ├── 04_data_validation_scripts.png
  ├── db_icons
    ├── gp_icon.png
    ├── mssql_icon.png
    ├── mysql_icon.png
    ├── oracle_icon.png
    ├── pgsql_icon1.png
├── LICENSE
├── mssql
  ├── data_dictionary
    ├── data_dict_dump.sql
  ├── data_validation
    ├── best_practices.md
    ├── demo_data
      ├── demo_hr_01_create_database.sql
      ├── demo_hr_02_create_tables.sql
      ├── demo_hr_03_populate_tables.sql
    ├── how_to_use_advanced_script.md
    ├── how_to_use_basic_script.md
    ├── img
      ├── 01_data_val_mssql_example_test_case_sql_code.png
      ├── 02_data_val_mssql_run_results1.png
      ├── 03_data_val_mssql_adv_test_case_ex.png
      ├── 04_data_val_mssql_run_results_adv.png
    ├── rule_set_01__row_counts.md
    ├── rule_set_02__keys.md
    ├── rule_set_03__heuristic_thresholds.md
    ├── rule_set_04__numeric_values.md
    ├── rule_set_05__date_values.md
    ├── rule_set_06__text_values.md
    ├── rule_set_07__regular_expressions.md
    ├── rule_set_08__diff_checks.md
    ├── rule_set_09__defect_regression.md
    ├── sql_scripts
      ├── dv_advanced_test_cases.sql
      ├── dv_basic_test_cases.sql
      ├── dv_test_case_snippets.sql
  ├── schemadiff
    ├── simple_schema_dump.sql
├── mysql
  ├── data_dictionary
    ├── data_dict_dump.sql
  ├── data_validation
    ├── best_practices.md
    ├── demo_data
      ├── demo_hr_01_create_database.sql
      ├── demo_hr_02_create_tables.sql
      ├── demo_hr_03_populate_tables.sql
    ├── how_to_use_advanced_script.md
    ├── how_to_use_basic_script.md
    ├── img
      ├── 01_data_val_mysql_example_test_case_sql_code.png
      ├── 02_data_val_mysql_run_results.png
      ├── 03_data_val_mysql_adv_test_case.png
      ├── 04_data_val_mysql_run_results_adv.png
    ├── rule_set_01__row_counts.md
    ├── rule_set_02__keys.md
    ├── rule_set_03__heuristic_thresholds.md
    ├── rule_set_04__numeric_values.md
    ├── rule_set_05__date_values.md
    ├── rule_set_06__text_values.md
    ├── rule_set_07__regular_expressions.md
    ├── rule_set_08__diff_checks.md
    ├── rule_set_09__defect_regression.md
    ├── sql_scripts
      ├── dv_advanced_test_cases.sql
      ├── dv_basic_test_cases.sql
      ├── dv_test_case_snippets.sql
  ├── schemadiff
    ├── simple_schema_dump.sql
├── oracle
  ├── data_dictionary
    ├── data_dict_dump.sql
  ├── data_validation
    ├── best_practices.md
    ├── demo_data
      ├── demo_hr_01_create_tables.sql
      ├── demo_hr_02_populate_tables.sql
    ├── how_to_use_advanced_script.md
    ├── how_to_use_basic_script.md
    ├── img
      ├── 01_data_val_oracle_example_test_case_sql_code.png
      ├── 02_data_val_oracle_run_results1.png
      ├── 03_data_val_oracle_adv_test_case_ex.png
      ├── 04_data_val_oracle_run_results_adv.png
    ├── rule_set_01__row_counts.md
    ├── rule_set_02__keys.md
    ├── rule_set_03__heuristic_thresholds.md
    ├── rule_set_04__numeric_values.md
    ├── rule_set_05__date_values.md
    ├── rule_set_06__text_values.md
    ├── rule_set_07__regular_expressions.md
    ├── rule_set_08__diff_checks.md
    ├── rule_set_09__defect_regression.md
    ├── sql_scripts
      ├── dv_advanced_01_setup.sql
      ├── dv_advanced_02_test_cases.sql
      ├── dv_basic_test_cases.sql
      ├── dv_test_case_snippets.sql
  ├── schemadiff
    ├── simple_schema_dump.sql
├── postgresql
  ├── data_dictionary
    ├── data_dict_dump.sql
  ├── data_validation
    ├── best_practices.md
    ├── demo_data
      ├── demo_hr_01_create_database.sql
      ├── demo_hr_02_create_tables.sql
      ├── demo_hr_03_populate_tables.sql
    ├── how_to_use_advanced_script.md
    ├── how_to_use_basic_script.md
    ├── img
      ├── 01_data_val_postgresql_example_test_case_sql_code.png
      ├── 03_data_val_postgresql_adv_test_case_ex2.png
      ├── 04_data_val_postgresql_run_results_adv.png
    ├── rule_set_01__row_counts.md
    ├── rule_set_02__keys.md
    ├── rule_set_03__heuristic_thresholds.md
    ├── rule_set_04__numeric_values.md
    ├── rule_set_05__date_values.md
    ├── rule_set_06__text_values.md
    ├── rule_set_07__regular_expressions.md
    ├── rule_set_08__diff_checks.md
    ├── rule_set_09__defect_regression.md
    ├── sql_scripts
      ├── dv_advanced_test_cases.sql
      ├── dv_basic_test_cases.sql
      ├── dv_test_case_snippets.sql
  ├── schemadiff
    ├── simple_schema_dump.sql
├── README.md
├── schemadiff_scripts.md
├── scripts
  ├── run_dvf.py
  ├── run_dvf.sh
├── SECURITY.md
├── tests
  ├── test_dataops_scripts.py
``
