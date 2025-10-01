# CLI Calculator

A modular **Command Line Calculator** built in Python for Assignment 4.  
This project demonstrates clean architecture, modular coding, error handling, and automated testing with GitHub Actions (CI/CD).

---

## 📂 Project Structure

- **Basic operations**: addition, subtraction, multiplication, division  
- **Modular design**: separated into `calculation`, `calculator`, and `operation` packages  
- **Interactive REPL (Read–Eval–Print Loop)**: type expressions to calculate directly in the terminal  
- **Error handling**: safe division and input validation  
- **Testing**: `pytest` with 90%+ coverage enforced in CI  
- **Continuous Integration**: GitHub Actions run tests automatically on every push or PR to `main`  

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Rajat-njit/cli-calculator.git
cd cli-calculator
```

## 2. Create Virtual Environment
```bash
pip install -r requirements.txt
```

## 4. Run the calculator from the terminal:
```bash
python main.py

```
## 5. REPL Session
```bash
Welcome to CLI Calculator!
Enter expressions like: Add 21 22

Type 'exit' to quit.

```

## 6. Running Tests
-- **Run tests locally:**
```bash
pytest
```

-- **Run tests locally:**
```bash
pytest --cov=app
```

## Continuous Integration (GitHub Actions)
**Every time you push or open a Pull Request to main, the following happens automatically:**

**1. Code is checked out.**

**2. Python environment is set up.**

**3. Dependencies from requirements.txt are installed.**

**4. Tests are run with pytest.**

**5. Coverage threshold is enforced.**

**6. If tests or coverage fail, the workflow fails.**

## Key Takeaways
-- **Practiced clean, modular Python design**

-- **Learned error handling in real applications**

-- **Gained experience with pytest & coverage reports**

-- **Integrated CI/CD pipelines via GitHub Actions**

-- **Built a project that’s extensible (easy to add power, square root, etc.)**

## Author
**Rajat Pednekar**
**Assignment 4 - CLI Calculator Project**
**NJIT**
