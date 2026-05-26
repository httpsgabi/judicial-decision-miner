# Judicial Decision Miner

Automated system for collecting, processing and storing judicial decisions from Brazilian court systems such as PJe and e-SAJ.

---

# Overview

This project aims to automate the collection, processing and storage of judicial decisions from Brazilian court systems.

The system integrates web automation, PDF document processing and structured persistence mechanisms in order to facilitate extraction and analysis of judicial information.

The architecture was designed using object-oriented principles and software design patterns, allowing scalability, modularity and easier maintenance.

---

# Main Features

- Automated navigation in judicial systems
- Integration with PJe and e-SAJ
- Automated PDF download
- Judicial decision parsing
- Decision filtering
- Structured data persistence
- Modular and extensible architecture

---

# Technologies

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Playwright | Web automation |
| PostgreSQL | Database |
| SQLAlchemy | ORM |
| PyMuPDF | PDF processing |
| FastAPI | Backend/API |
| Pydantic | Data validation |
| Pytest | Automated testing |

---

# Project Structure

```
project/
│
├── docs/
├── tests/
├── src/
│   ├── controller/
│   ├── connectors/
│   ├── factories/
│   ├── models/
│   ├── parser/
│   ├── filter/
│   ├── storage/
│   ├── strategies/
│   └── utils/
│
├── requirements.txt
├── README.md
├── .env
└── .gitignore
```

---

# Environment Setup

## 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/judicial-decision-miner.git
```

---

## 2. Access the project directory

```bash
cd judicial-decision-miner
```

---

## 3. Create virtual environment

### Windows

```bash
python -m venv venv
```

---

## 4. Activate virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / MacOS

```bash
source venv/bin/activate
```

---

## 5. Install dependencies

```bash
python -m pip install -r requirements.txt
```

---

## 6. Install Playwright browsers

```bash
python -m playwright install
```

---

# Running the Project

Future implementation.

---

# Development Status

🚧 Project under development.

Current phase:
- Software architecture
- UML modeling
- Initial project structure
- Connector implementation

---

# Future Improvements

- Elasticsearch integration
- OCR support
- AI-based decision analysis
- Parallel processing
- Web dashboard
- Multi-court scalability

---

# License

This project is intended for academic and educational purposes.