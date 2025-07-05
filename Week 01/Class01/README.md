# Python Programming Class – Batch Guide

## Class 1 – Project Setup Guide

Welcome to the Python Programming course!  
This guide will walk you through setting up your development environment using **Anaconda**, **VS Code**, **Git Bash**, and **Python**. By the end, you'll be ready to write your first Python program and manage your projects efficiently.

---

## Prerequisites

Please install the following software before proceeding:

- [Anaconda (Python + Jupyter)](https://www.anaconda.com/products/individual#Downloads)
- [Git Bash](https://git-scm.com/downloads)
- [Visual Studio Code (VS Code)](https://code.visualstudio.com/download)

---

## Installation Guides

- 📦 [Anaconda & Jupyter Installation Guide](https://github.com/ayanhussain81/python_programming/blob/main/documents/Anaconda%26%20JupyterNotebook%20Installati)
- 🔧 [Git Bash Installation Guide](https://github.com/ayanhussain81/python_programming/blob/main/documents/GtiBash%20Installation.pdf)
- 💻 **VS Code Installation Steps:**
  1. Download from [VS Code Official Site](https://code.visualstudio.com/)
  2. During installation:
     - ✅ Check “Add to PATH”
     - ✅ Install Python extension when prompted
  3. After launch:
     - Go to Extensions (`Ctrl+Shift+X`)
     - Search for **Python** (by Microsoft)
     - Click **Install**

---

## 📑 Table of Contents

1. [Running a "Hello World" Program](#-running-a-hello-world-program)
2. [Setting Up a Virtual/Conda Environment](#-setting-up-a-virtualconda-environment)
3. [Installing Required Packages](#-installing-required-packages)

---

## 👋 Running a "Hello World" Program

Test your setup by running your first Python program.

### 🔹 Using Command Prompt / Git Bash

1. Open **Command Prompt** or **Git Bash**
2. Verify Python and Conda are installed:

    ```bash
    conda --version 
    python --version
    ```

3. Enter Python interactive mode:

    ```bash
    python
    ```

4. Run your first program:

    ```python
    print("Hello Saylani...!!!")
    ```

5. Exit Python shell:  
   - `Ctrl + Z` then `Enter` (Windows)  
   - `Ctrl + D` (Linux/Mac)

---

### 🔹 Using Jupyter Notebook

1. Navigate to your project folder (e.g., `Documents/Python912`)
2. Open **Command Prompt** in that folder
3. Start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

4. Create a new file named `class1.ipynb`
5. In the first cell, write:

    ```python
    print("Hello world")
    ```

6. Run the cell with `Shift + Enter`

---

## 📦 Setting Up a Virtual/Conda Environment

Using virtual environments helps you manage dependencies cleanly.

### 🔹 Create a New Environment

```bash
conda create --name <env_name>
# Example:
conda create --name python912
