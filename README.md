# ECS427 Multi-Agent Reinforcement Learning

Taught by **Prof. P B Sujit** at **Indian Institute of Science Education and Research Bhopal**, in *Fall 2024-25*.

## Student Details

- **Name:** Sattwik Kumar Sahu
- **Roll No.:** `21241`

# Installation

## Clone Repo

```bash
git clone https://github.com/sattwik-sahu/ecs427.git
cd ecs427
```

## Setup the virtual environment

### Create and Activate Virtual Environment

```bash
python3 -m venv .venv --prompt=ecs427   # Create the venv
source .venv/bin/activate               # Linux
source .venv/Scripts/activate.bat       # Windows
```

### Install Dependencies

```bash
python3 -m pip install -U pip           # Upgrade pip to latest version
python3 -m pip install poetry           # Install dependency manager
poetry install                          # Install all project dependencies
```

> If `poetry install` does not work, try
> ```bash
> python3 -m poetry install
> ```
> to run poetry as a module.

# Evaluation

## Assignments

- To evaluate assignments, please navigate to the `assignments` directory.
- To evaluate assignment #1, open the notebook inside `assignments` named `assignment-01.ipynb`
