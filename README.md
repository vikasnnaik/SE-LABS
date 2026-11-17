# Software Engineering Lab (SE-LABS)

Repository containing lab assignments, projects, reports, and code artifacts for the **5th Semester Software Engineering Laboratory** at PES University.

**Author:** Vikas N Naik  
**SRN:** PES2UG24CS583  

---

## 📂 Repository Structure

| Directory | Topic / Title | Description |
|---|---|---|
| [`LAB 1/`](./LAB%201) | **Software Requirements & Specifications** | Requirements analysis, user stories, and specification documentation. |
| [`LAB 2/`](./LAB%202) | **Software Modeling & Design** | System design diagrams, UML architecture, and software design reports. |
| [`LAB 3/`](./LAB%203) | **Software Design Patterns & Architecture** | Design patterns and architectural modeling exercises. |
| [`LAB 4/`](./LAB%204) | **Dots and Boxes Game Refactoring** | Bug fixes (coordinate conversion vulnerabilities), input validation, dynamic board sizing (2x2, 3x3, 4x4), and unit testing. |
| [`LAB 5/`](./LAB%205) | **Static Code Analysis & Security Auditing** | Code inspection using **Pylint**, **Bandit**, and **Flake8** on a SQLite bike-share station program (parameterized queries, secrets module, score 10.0/10). |
| [`LAB 6/`](./LAB%206) | **Statement & Branch Coverage Testing** | Unit testing with `pytest` and `coverage` to achieve high statement and branch coverage on shopping cart calculation logic. |
| [`LAB 7/`](./LAB%207) | **Fuzz & Property-Based Testing** | Automated fuzz testing using `Hypothesis` on shopping cart pricing, discounts, and boundary conditions. |

---

## 🛠️ Tech Stack & Tools

- **Programming Language:** Python 3
- **Testing Frameworks:** `unittest`, `pytest`, `pytest-cov`, `Hypothesis`
- **Static Analysis & Security:** `Pylint`, `Bandit`, `Flake8`
- **Database:** SQLite3
- **Version Control:** Git & GitHub

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/vikasnnaik/SE-LABS.git
cd SE-LABS
```

### 2. Lab-specific Execution

#### Lab 4: Dots and Boxes Game
```bash
cd "LAB 4"
python main.py

# Run automated tests
python -B -m unittest discover -s tests -v
```

#### Lab 5: Static Analysis
```bash
cd "LAB 5"
# Run analysis tools
pylint bike_share_stations.py
bandit -r bike_share_stations.py
flake8 bike_share_stations.py
```

#### Lab 6: Code Coverage Testing
```bash
cd "LAB 6"
pytest --cov=. --cov-branch --cov-report=term-missing
```

#### Lab 7: Fuzz Testing with Hypothesis
```bash
cd "LAB 7"
pytest test_shopping_cart.py
```

---

## 📜 License

Academic use only.
