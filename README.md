# 🔎 Machine learning concepts

A repository dedicated to learning and experimenting with machine learning concepts and techniques.

## 📌 Prerequisites

- Python **3.10+** (recommended: 3.11)
- VS Code (recommended) + extensions:
  - **Python**
  - **Jupyter**

## 💻 Quick Start (Recommended)

### 1) Clone repo

``` bash
git clone <REPO_URL>
cd machine-learning
```

### 2) Create a virtual enviroment

#### Windows

```bash
py -m venv .venv
```

#### MacOS/Linux

```bash
python3 -m venv .venv
```

### 3) Activate the environment

#### Windows (PowerShell)

``` bash
.\.venv\Scripts\Activate.ps1
```

#### Windows (CMD)

``` bash
.\.venv\Scripts\activate
```

#### macOS/Linux

```bash
source .venv/bin/activate
```

### 4) Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## 📓 Jupyter Kernel Setup (Important)

To make sure Jupyter uses this .venv environment:

1. Install kernel package

```bash
pip install ipykernel jupyter
```

2. Register the kernel

```bash
python -m ipykernel install --user --name ml-venv --display-name "Python (ml-venv)"
```

## 💙 VS Code Setup (see if it actually works)

1. Open the repo folder in VS Code.
2. Press Ctrl+Shift+P → Python: Select Interpreter
3. Select the interpreter from: `./.venv/...`
4. Open any notebook.
5. In the top-right of the notebook, click Kernel and select: `Python (ml-venv)`

If you skip this step, VS Code may run notebooks with a different Python than the one where you installed packages.

## ✅ Verify is everything correct

Run this in a notebook cell:

```bash
import sys
print(sys.executable)
```

Expected output should point to the repo’s virtual environment, e.g.:

- Windows: `.../machine-learning/.venv/Scripts/python.exe`

- macOS/Linux: `.../machine-learning/.venv/bin/python`

## 👉 Useful documenation

- **[Python](https://docs.python.org/3/)** - easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming.
- **[scikit-learn](https://scikit-learn.org/stable/user_guide.html)** - simple and efficient tools for predictive data analysis, open source
- **[Pandas](https://pandas.pydata.org/docs/)** - package that provides fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive
- **[NumPy](https://numpy.org/doc/)** - offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more
