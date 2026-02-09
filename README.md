# Homework 2: Probability Models

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the repository for Homework 2 for [BEE 4850/5850](https://viveks.me/simulation-data-analysis), taught at [Cornell University](https://cornell.edu) in Spring 2026 by [Vivek Srikrishnan](https://viveks.me).

If enrolled in the class, a PDF of the completed assignment, **with all cells evaluated if a notebook**, should be submitted to Gradescope *no later* than Friday, February 20, 2026, at 9:00pm. The assignment will be penalized 50% if it is submitted up to 24 hours late.

## Learning Objectives

After completing this lab, students will be able to:

* develop linear and generalized linear models for data under a variety of statistical assumptions;
* evaluate the appropriateness of those assumptions through the use of qualitative and quantitative evaluations of goodness-of-fit.

## Repository Overview

The repository consists of the following files:

- `hw02.ipynb`: Jupyter Notebook for the homework assignment. Students should create code or Markdown blocks as necessary to answer questions. **This is the only file you should need to edit.**
- `Project.toml`, `Manifest.toml`: Julia environment files. These should just work, but feel free to add other packages as needed using the `Pkg` package manager. **This is the only other file that you might end up making changes to, though you should do this using `Pkg`, not directly.**
- `hw02.qmd`: Source file for Jupyter notebook generation. You shouldn't need to or want to touch this; everything is in the `.ipynb` file.
- `LICENSE`: This material is licensed using the MIT license. You can ignore this for working on the problem set.
- `README.md`: This file. You shouldn't need to touch this.
- `.gitignore`: This tells `git` what files to ignore. You shouldn't need to touch this.
- `.github/`: This folder contains workflow files which generate the notebook. Again, you shouldn't need to touch this.
- `data/`: This folder contains several .csvs and other data files to complete the projects.

## Prerequisites

### Julia

[Julia](https://julialang.org/downloads/): This notebook was developed with version 1.11.5, but any 1.11.x should work (there could be some issues with other versions, depending on what's changed). You can solve this assignment using other languages, but the provided notebook is based on Julia.

### Packages

These are provided in the project environment assuming the assignment will be solved in Julia; similar packages from other languages can be used instead.

1. Random.jl: random number generation and seed-setting
2. DataFrames.jl: tabular data structure
3. CSV.jl: reads/writes .csv files
4. Distributions.jl: interface to work with probability distributions
5. Plots.jl: plotting library
6. StatsBase.jl: statistical quantities like mean, median, etc
7. StatsPlots.jl: some additional statistical plotting tools
8. Optim.jl: optimization tools
9. LaTeXStrings.jl: latex formatting for plot strings
