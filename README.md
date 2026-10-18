# BookBot (Python)

A command-line tool written in Python to analyze the contents of text files and generate character and word statistics.

> **Curriculum Note:** This was my first project in the [Boot.dev](https://www.boot.dev) Backend Developer Path, built to practice file I/O, dictionary data structures, string manipulation, and CLI arguments.

---

## What It Does

BookBot reads whole books (such as Project Gutenberg text files) and prints a structured statistical report:
- Total word count in the document.
- Sorted character frequency analysis (identifying which alphabetical characters appear most often).
- Supports parsing multiple file paths passed as command-line arguments via `sys.argv`.

---

## Technical Details

- **Language:** Python 3 (Standard Library only)
- **Key Concepts:**
  - File reading with `with open(path) as f`
  - String manipulation (`split()`, `lower()`, `isalpha()`)
  - Dictionary frequency counting and dictionary sorting
  - `sys.argv` command-line argument parsing

---

## How to Run

Pass one or more book paths to `main.py`:

```bash
python3 main.py books/frankenstein.txt
```
