# Introduction to Python

A hands-on, from-scratch introduction to **Python for data analysis** — no prior programming
experience assumed. Roughly equivalent to an introductory DataCamp track, but self-contained
and free to use.

It takes you from your very first line of code to working with real data tables in **pandas**,
with slides and a hands-on notebook for every topic.

---

## Who this is for

Anyone who wants to learn Python for data work — researchers, students, and the merely curious.
You don't need any programming background. If you can use a spreadsheet, you can start here.

It also serves as the recommended **prerequisite** for applied courses that assume basic Python
(such as computational text analysis).

## The modules

| # | Module | What you'll learn |
|---|--------|-------------------|
| **0** | Setting Up Python | Ways to run Python, editors & IDEs, virtual environments, cloning repos |
| **1** | Getting Started | Variables, data types, arithmetic, strings, f-strings |
| **2** | Data Structures | Lists, dictionaries, tuples, sets |
| **3** | Control Flow | `if`/`elif`/`else`, `for` loops |
| **4** | Functions | Defining functions, arguments, scope, list comprehensions |
| **5** | Strings & Files | String methods, splitting/joining, reading & writing files |
| **6** | NumPy | Arrays and fast numerical computing |
| **7** | pandas | DataFrames: loading, filtering, grouping, plotting |

Work through them **in order** — each builds on the last.

## How it's organized

Everything is grouped **by module**. Inside each, `slides/` holds the lecture deck (PDF to view,
`.tex` source to edit) and `notebooks/` holds the hands-on material — an `_exercises` notebook to
work through and a matching `_solutions` notebook.

```
1_getting_started/
  slides/       lecture deck (.pdf + .tex)
  notebooks/    *_exercises.ipynb  and  *_solutions.ipynb
2_data_structures/  ...
```

Module 0 is a little different: setting up Python happens on your own computer, so it's mostly
**slides + a reference notebook** of commands rather than interactive exercises.

## Running the notebooks

The notebooks are built for **Google Colab** — nothing to install. Click the **"Open in Colab"**
badge at the top of any notebook, or open Colab and load it from GitHub.

To run locally instead, see `requirements.txt` (Python 3.10+ recommended). Module 0 walks through
setting that up.

## License

Shared under **CC BY 4.0** — free to use and adapt with attribution. See `LICENSE`.
