# GRADEME Installation and Usage Manual


This manual explains how to obtain the **42-EXAM** project folder and execute the command required to run **GRADEME locally**, as an alternative to using the grademe.fr website for offline testing

> **Project:** **42-EXAM**  
> **Author:** [JCluzet](https://github.com/JCluzet)

## Prerequisites

- **Git** installed (if you choose to clone the repository).
- **Curl** and **Bash** available on your system.
- An active internet connection.

## Obtaining the Project

There are two ways to obtain the project folder:

### Option A: Cloning the Repository

If the project is hosted in a Git repository, clone it by running:

```bash
git clone https://github.com/Greatspot/42-EXAM.git
```

### Option B: Decompressing the ZIP Archive

```bash
unzip 42-EXAM.zip
```

### Navigating to the Project Folder

```bash
cd 42-EXAM
```

### Running GRADEME
Once you are in the project directory, execute the following command to run GRADEME:

```bash
bash -c "$(curl https://grademe.fr)"
```
**Important:** Make sure you are **not** using the **Fish** shell in your terminal. The command is designed to work with Bash.

This command downloads and executes the GRADEME script. Follow any on-screen instructions in your terminal to complete the setup.
