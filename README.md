# NYC Congestion Pricing Analysis

This repository contains an analysis of the impact of New York City's Congestion Relief Zone on vehicle entries, MTA ridership, and traffic patterns.  

It includes performance benchmarks for PostgreSQL, Elasticsearch, and MySQL using the provided datasets and docker compose files.

---

## 📂 Contents

### **Datasets**
- `UPDATED_MTA_Congestion_Relief_Zone_Vehicle_Entries__Beginning_2025_20250823.csv.gzip`  
  Vehicle entry counts into the Congestion Relief Zone by date, time, vehicle class, and toll period.

- `UPDATED_MTA_Daily_Ridership_and_Traffic__Beginning_2020_20250823.csv.zip`  
  Daily MTA ridership traffic counts from 2020–2025.

- `UPDATED MTA_Bridges_and_Tunnels_Hourly_Crossings__Beginning_2019_20250823.csv.gzip`  
  Hourly bridge and tunnel crossing traffic counts from 2019–2025.

- `nyc_congestion_datasets.json`  
  Necessary to run `ElasticSearch_final_project.ipynb` file.
---

### **Jupyter Notebooks**
1. **`PostgreSQL_final_project.ipynb`** — PostgreSQL implementation and benchmarking with the datasets.
2. **`ElasticSearch_final_project.ipynb`** — Elasticsearch implementation and benchmarking with the datasets.
3. **`MySQL_benchmark.ipynb`** — MySQL implementation and benchmarking with the datasets.

### **Docker files**
1. **`docker-compose-postgres.yml`** – PostgreSQL docker container to connect to PostgreSQL server.
2. **`docker-compose-elasticsearch.yml`** – Elasticsearch docker container to connect to Elasticsearch server.
3. **`docker-compose-mysql.yml`** – MySQL docker container to connect to MySQL server.

---

## Run Code
To run the code, follow these steps:
1. Download all the files in the `Contents` folder.
2. Download & install [Docker Desktop](https://www.docker.com/products/docker-desktop/) on your machine.
3. Ensure the necessary files are within the same folder as the Jupyter Notebooks.
4. Unzip compressed files.
5. Update necessary file paths in the Jupyter Notebooks to ensure they run smoothly.
6. Uncomment any `!pip install` lines to install necessary modules.
7. Run the code.
