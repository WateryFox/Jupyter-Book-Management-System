# Jupyter Book Management System

An Object-Oriented Programming (OOP) application developed in Python using Jupyter Notebooks (`.ipynb`) to manage book inventories. The project implements modular notebook design and persists data using CSV file storage.

---

## Features

- **Display Book List:** View all book records within the interactive `tampil_buku.ipynb` notebook environment.
- **Add New Book:** Insert new book entries interactively through `tambah_buku.ipynb`.
- **Data Persistence:** Automatically save and retain records in `buku.csv`.
- **Modular OOP Architecture:** Utilizes `models.py` for class definitions and data models to maintain clean separation of concerns.

---

## Project Structure

```text
pbo_praktik_11if/
├── Main.ipynb          # Main execution and workflow notebook
├── models.py           # Data models and OOP classes
├── tambah_buku.ipynb   # Notebook module for adding books
├── tampil_buku.ipynb   # Notebook module for displaying books
├── buku.csv            # CSV data storage file
├── .gitignore          # Git ignore rules
└── LICENSE             # Project license (MIT)
