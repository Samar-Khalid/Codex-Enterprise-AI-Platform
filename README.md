# Codex Enterprise AI Platform

A framework for integrating AI capabilities into enterprise systems with a focus on data governance, master data management, and ERP integration.

## Motivation

Enterprise applications share common patterns - authentication, data management, workflows, and reporting. Codex Enterprise AI Platform provides a reusable foundation for building AI-powered enterprise features, with a particular focus on manufacturing and ERP environments.

## Focus Areas

### Data Governance
- Data quality monitoring and validation
- Access control and audit logging
- Data lineage tracking

### Master Data Management
- Customer, product, and supplier data hubs
- Data deduplication and matching
- Hierarchical data structures

### AI Integration
- LLM-powered data querying
- Automated report generation
- Anomaly detection in operational data

## Quick Start

```bash
git clone https://github.com/Samar-Khalid/Codex-Enterprise-AI-Platform.git
cd Codex-Enterprise-AI-Platform
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Run with Docker:

```bash
docker-compose up -d
```

API docs at http://localhost:8000/docs

## Repository Structure

```
backend/
    core/       Configuration, database setup
    api/        FastAPI endpoints
    services/   Business logic
    workers/    Background tasks
```

## Status

Early-stage. Auth and basic CRUD operational. Data governance and AI features under active development.

## License

MIT