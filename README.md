<div align="center">

# Hi, I'm Asad Sajjad 👋

### Python Automation Developer · PySide6 Desktop Applications · Data & ML Pipelines

I build reliable Python automation tools and responsive **PySide6 (Qt)** desktop applications that turn repetitive file, media, and data workflows into clean, one-click processes.

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PySide6](https://img.shields.io/badge/PySide6-Qt_for_Python-41CD52?style=for-the-badge&logo=qt&logoColor=white)](https://doc.qt.io/qtforpython/)
[![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Git](https://img.shields.io/badge/Git-%26_GitHub_Actions-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)

</div>

---

## 👨‍💻 About Me

I engineer modular Python utilities, command-line pipelines, and desktop GUI applications with a strong focus on **safety, responsiveness, and observability**—using background worker threads (`QThread`), pre-execution dry-run validation, defensive error handling, and multi-channel logging (`GUI`, `FileHandler`, and `StreamHandler`).

- 🐍 **Core Stack:** Python, PySide6 (Qt), `pathlib`, `csv`, `json`, `argparse`, `logging`, `NumPy`
- 🖥️ **Desktop GUI Engineering:** Non-blocking `QThread` background workers, custom Qt Stylesheets (QSS), and live `Signal(str)` log consoles
- ⚙️ **Workflow Automation:** Recursive directory auditing, bulk file renaming & sanitization, media asset organization, and high-volume JSON/CSV batch pipelines
- 🧠 **Machine Learning & Data:** Vectorized numerical computing with NumPy, regression modeling from first principles, feature scaling, leak-free train/test workflows, and evaluation metrics

---

## 🚀 Featured Repositories

### 1. [CSV Manifest Generator](https://github.com/asadsajjadcodes-maker/csv_manifest_generator)
**Responsive PySide6 Desktop File-System Auditing & CSV Inventory Tool**
- Recursively audits directory trees using `pathlib` and extracts structured OS metadata (`Filename`, `Extension`, `Parent_Folder`, `Size_MB`, `Last_Modified`, `Full_Path`).
- Executes scans inside a background `QThread` worker (`ScanWorker`) with real-time progress signals and mid-scan cancellation so the GUI never freezes.
- Routes runtime diagnostics simultaneously to the PySide6 log panel, console, and `logs/app.log`, and exports clean reports via `csv.DictWriter`.

**Tech:** `Python` · `PySide6` · `QThread & Signals` · `pathlib` · `csv` · `logging`

---

### 2. [File Batch Renamer](https://github.com/asadsajjadcodes-maker/file_batch_renamer)
**Safe Desktop Bulk File Renaming & Sanitization Utility with CI/CD Packaging**
- Implements a strict **Scan → Plan → Validate → Preview → Execute** workflow for bulk file renaming with 3-digit zero-padded indexing (`<prefix>_001.ext`).
- Includes regex filename sanitization (`cleaner.py`), dry-run GUI console previews, and pre-execution collision checks (`validator.py`) to prevent accidental overwrites.
- Packaged as a standalone Windows executable via an automated **GitHub Actions + PyInstaller** workflow.

**Tech:** `Python` · `PySide6` · `pathlib` · `re` · `logging` · `GitHub Actions` · `PyInstaller`

---

### 3. [Python Pipeline Core & Pro Media Asset Manager](https://github.com/asadsajjadcodes-maker/python_pipeline_core)
**39-Lesson Automation Engineering Suite, 10k+ Batch Auditor & QSS-Styled Desktop Organizer**
- Features **Pro Media Asset Manager** (`media_organizer/`), a dark QSS-styled PySide6 desktop app that audits directories and automatically organizes files into category folders (`Images`, `Videos`, `Audio`, `Documents`, `Archives`, `Code`) without overwriting existing assets.
- Includes a CLI batch JSON verification and telemetry engine (`day_27_pipeline_summary.py`) with `--dry-run` simulation and automated JSON summary reports.
- Demonstrates custom Qt multiple-inheritance logging (`QObject` + `logging.Handler`) and defensive JSON loader/saver utilities.

**Tech:** `Python` · `PySide6 (QSS)` · `pathlib` · `json` · `argparse` · `logging`

---

### 4. [Machine Learning → Deep Learning → AI Engineering Lab](https://github.com/asadsajjadcodes-maker/ml-local-ai-automation-lab)
**Code-First Machine Learning & Numerical Computing Implementations from Scratch**
- Implements univariate and multivariate linear regression, analytical gradient descent, and vectorized forward/backward passes using **Python** and **NumPy** array broadcasting.
- Covers production ML hygiene including Z-score feature scaling, leak-free train/test split pipelines, overfitting diagnostics, model selection, and regression evaluation metrics (`MAE`, `MSE`, `RMSE`, $R^2$).

**Tech:** `Python` · `NumPy` · `Machine Learning` · `Numerical Computing`

---

### 5. [Python Foundations & Mini-Projects](https://github.com/asadsajjadcodes-maker/python-beginner-programs)
A structured collection of 17 foundational Python scripts, interactive CLI games, text filters, and file-handling utilities.

### 6. [CLI To-Do List Task Manager](https://github.com/asadsajjadcodes-maker/Todo_list_python_app)
A lightweight command-line task management utility with persistent file storage for adding, viewing, and deleting tasks.

---

## 🛠️ Technical Skills Overview

| Domain | Technologies & Engineering Practices |
| :--- | :--- |
| **Languages & Core** | Python 3.10+, Modular Architecture, Type Annotations, Exception Handling |
| **Desktop GUI** | PySide6 (Qt for Python), `QThread` Concurrency, Qt Signals & Slots, Custom QSS Styling |
| **File & OS Automation** | `pathlib`, Recursive Directory Traversal (`rglob`), Batch Renaming, Media Classification |
| **Data & Serialization** | CSV Report Generation (`csv.DictWriter`), Defensive JSON Parsing (`json.load`/`dump`), Log Parsing |
| **CLI & Diagnostics** | `argparse` CLI Tools, `--dry-run` Simulation Workflows, Multi-Handler `logging` (GUI/File/Console) |
| **Machine Learning** | NumPy Vectorization, Linear Regression, Gradient Descent, Feature Scaling, Model Evaluation |
| **DevOps & Tooling** | Git, GitHub Actions CI/CD, PyInstaller Executable Packaging, VS Code |

---

## 🤝 Connect With Me

- **GitHub:** [@asadsajjadcodes-maker](https://github.com/asadsajjadcodes-maker)
- **Upwork:** [Asad S. — Python Automation & PySide6 Developer](https://www.upwork.com/freelancers/~017ee2793979b471c3)