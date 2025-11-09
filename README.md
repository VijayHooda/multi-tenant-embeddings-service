# Multi-Tenant Embeddings Service

A production-grade vector search and embedding storage service supporting multi-tenancy and live MySQL/MS-SQL → PostgreSQL migrations.

## 🏗️ Stack
FastAPI · PostgreSQL(pgvector) · Terraform · Ansible · Debezium · Prometheus

## ⚙️ Features
- MySQL/MS-SQL → PostgreSQL CDC migration with <10min downtime
- Tenant-isolated embedding API (create/search/delete)
- Infra automation via Terraform & Ansible
- Prometheus metrics for latency, throughput
