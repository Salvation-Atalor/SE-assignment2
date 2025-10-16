# SE-assignment2: Version Control Using GitHub

## 📘 Project Description
This project demonstrates the practical use of **Git** and **GitHub** for version control and collaborative software development.  
It was created as part of **CINS 5318 – Software Engineering (Fall 2025)** under the guidance of **Dr. Mary Kim**.

The repository includes:
- A simple “Hello, World!” program written in Python.
- Feature branches that demonstrate branching, merging, and conflict resolution.
- Pull requests for collaborative reviews.
- Example issues for project tracking.



## ⚙️ Installation Instructions

### Prerequisites
Before running the project, ensure you have:
- [Python 3.10+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- A GitHub account

### Steps to Set Up Locally
1. **Clone this repository**
   ```
    bash
    git clone https://github.com/Salvation-Atalor/SE-assignment2

    cd SE-assignment2
    ```


2. (Optional) Create and activate a virtual environment

```
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
```

3. Run the program

```
python hello.py
```

## 💻 Usage Example
Example 1: Default Greeting

```
python hello.py
```

Output:

```
Hello, World!
Hi! Salvation
```


| Branch        | Description                            |
| ------------- | -------------------------------------- |
| `main`        | Stable version of the code             |
| `feature-1`   | Adds personalized greeting             |
| `feature-2`   | Demonstrates merge conflict resolution |


## 🧾 Issues and Project Management

Two issues were created to track tasks:

Issue #1: Modify The Hello World Program to Include a personalized Greeting Message.

Issue #2: Resolve merge conflict between main and features-2.

Each issue was closed automatically through commits using Fixes #<issue-number> syntax.