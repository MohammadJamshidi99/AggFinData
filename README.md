# AggFinData

A software engineering project focused on building a Python-based system for financial data processing and delivery.

## Overview

AggFinData is a project developed in the context of a Software Engineering course.
The repository contains the main implementation of the system, along with packaging, migrations, automation workflows, and deployment-related components.

## Main Features

* Python-based project structure
* Automated workflows for CI/CD
* Database migration support
* Packaged for distribution
* Release and deployment setup
* Accompanied by project documentation and report material

## Repository Structure

```text
.github/workflows/   # CI/CD workflows
AggFin/              # Main application/package code
migrations/          # Database migration scripts
report/              # Project report-related material
run.py               # Main execution entry point
setup.py             # Packaging/setup configuration
requirements.txt     # Runtime dependencies
requirements-dev.txt # Development dependencies
```

## Tech Stack

* Python
* GitHub Actions
* Packaging with setup.py
* Database migrations
* GitHub Pages / deployment support

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MohammadJamshidi99/artifact.git
cd artifact
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

#### On Windows

```bash
.venv\Scripts\activate
```

#### On macOS/Linux

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

For development:

```bash
pip install -r requirements-dev.txt
```

### 4. Run the project

```bash
python run.py
```

## Development

This repository includes development tooling and automation to support:

* testing
* packaging
* release management
* deployment workflows

If needed, database-related changes can be handled through the migration scripts in the `migrations/` directory.

## Documentation

The project also includes supporting report/documentation material.
For structured project documentation, see the related report repository sections covering:

* concept
* requirements
* design
* development
* validation
* release
* deployment
* CI/CD
* user guide
* developer guide
* future work

## Release

A release pipeline is configured for the project, and published releases are available through the repository’s Releases section.

## License

This project is licensed under the MIT License.

## Authors

Developed as part of the **AggFinData** Software Engineering project.

---

> Replace this section with your team names, your role, and 2–3 lines describing what *you* specifically implemented.
