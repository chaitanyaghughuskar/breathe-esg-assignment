# Breathe ESG Assignment

A prototype ESG data ingestion and analyst review dashboard built using React and Spring Boot.

---

## Overview

This project demonstrates a simplified ESG workflow for handling multiple enterprise data sources such as:

* SAP Fuel & Procurement Data
* Utility Electricity Data
* Corporate Travel Data

The application simulates ingestion, normalization, and analyst review workflows.

---

## Features

* ESG dashboard interface
* Source categorization
* Review status tracking
* Mock analyst workflow
* Multi-source prototype structure

---

## Data Sources

### SAP

Simulated SAP flat-file export data for fuel and procurement records.

### Utility Data

Mock electricity usage data based on utility CSV exports.

### Travel Data

Simulated travel platform records for flights and transportation.

---

## Tech Stack

### Frontend

* React
* Vite
* Axios

### Backend

* Spring Boot
* Java
* REST APIs

### Database

* MySQL

---

## Project Structure

```bash
backend/
frontend/
README.md
MODEL.md
DECISIONS.md
TRADEOFFS.md
SOURCES.md
```

---

## Running the Project

### Backend

1. Create MySQL database:

```sql
CREATE DATABASE breathe_esg;
```

2. Open backend folder in STS / IntelliJ

3. Run:

```bash
BreatheApplication.java
```

---

### Frontend

```bash
npm install
npm run dev
```

---

## Dashboard Preview

The dashboard demonstrates:

* ESG source tracking
* Category mapping
* Review statuses
* Analyst review simulation

---

## Future Improvements

* Authentication & authorization
* Real-time ingestion pipelines
* File upload workflows
* Advanced validation rules
* Production deployment pipeline

---

## Author

Chaitanya Ghughuskar
