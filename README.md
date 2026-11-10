
# Judicial Decision Miner

Automated system for collecting, processing, and storing judicial decisions from Brazilian court systems such as PJe and e-SAJ.

---

## Overview

This project aims to automate the collection, processing, and storage of judicial decisions from Brazilian court systems.

The system integrates web automation, PDF document processing, and structured data persistence to facilitate the extraction and analysis of judicial information.

The architecture follows object-oriented principles and software design patterns, allowing scalability, modularity, and easier maintenance.

---

## Main Features

- Automated navigation in judicial systems
- Integration with PJe and e-SAJ
- Automated PDF download
- Judicial decision parsing
- Decision filtering
- Structured data extraction and persistence
- Process and document management
- Modular and extensible architecture

---

## Technologies

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Playwright | Web automation |
| MongoDB | NoSQL database |
| PyMongo | MongoDB integration |
| PyMuPDF | PDF processing |
| FastAPI | Backend/API |
| Pydantic | Data validation |
| Pytest | Automated testing |
| python-dotenv | Environment variable management |

---

## Project Structure

```text
judicial-decision-miner/
│
├── docs/
├── tests/
├── src/
│   ├── controllers/
│   ├── connectors/
│   ├── factories/
│   ├── models/
│   ├── parser/
│   ├── filters/
│   ├── storage/
│   ├── strategies/
│   └── utils/
│
├── requirements.txt
├── README.md
├── .env
├── .env.example
└── .gitignore
```

---

## Environment Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/judicial-decision-miner.git
```

### 2. Access the project directory

```bash
cd judicial-decision-miner
```

### 3. Create a virtual environment

**Windows:**

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 6. Install Playwright browsers

```bash
python -m playwright install
```

---

## Database Configuration

The project uses MongoDB as its primary database.

The application communicates with MongoDB through PyMongo.

Database credentials and connection strings must be stored in environment variables and must not be committed to the repository.

---

## Running the Project

Under development.

---

## Development Status

Project under development.

Current phase:

- Software architecture
- UML modeling
- Initial project structure
- MongoDB database modeling
- Initial database integration

---

## Future Improvements

- OCR support
- AI-based judicial decision analysis
- Parallel processing
- Web dashboard
- Multi-court scalability

---

## License

This project is intended for academic and educational purposes.
