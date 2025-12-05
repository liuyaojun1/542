# AIDev Pull Request Analysis – Project Documentation

## Group 5
### Yaojun Liu, Sasivimol Sirijangkapattana

This document describes the AIDev Pull Request Analysis project for DATA 542.
It introduces the purpose of the project, the research questions, the dataset used, and the structure of this repository.

---

## 1. Project Purpose

The purpose of this project is to study pull request (PR) behaviour in the AIDev dataset, which contains large-scale information about GitHub repositories, users, and PR activity.

We are interested in how repository popularity, user influence, text characteristics, and AI coding agents relate to PR outcomes such as resolution time and merge success.

Milestone 2 focuses on the first research question (RQ1). RQ2 and RQ3 will be completed for the final report.

---

## 2. Research Questions

- **RQ1:** How do repository popularity (stars, forks) and user influence (followers, account age) relate to PR resolution time?

- **RQ2:** How do text characteristics of PRs (length and sentiment) vary across repositories with different popularity tiers and users with different influence levels?

- **RQ3:** How does AI coding agent contribution behaviour vary across repositories with different popularity levels?

---

## 3. Dataset Description

The project uses three datasets from the AIDev collection:

- **Pull requests:** timestamps, state, merge information, title and body text.
- **Repositories:** stars, forks, creation time, and other metadata.
- **Users:** followers, user type (human or bot), and account creation time.

The datasets are accessed directly from HuggingFace and are not stored in this repository due to size limitations.

---

## 4. Repository File Guide

This section describes the purpose of each file and folder in the repository.

- **Project Milestone 2 Report.pdf**  
  The written submission for Milestone 2, summarizing progress on RQ1 and planning on RQ2 and RQ3.

- **RQ1.ipynb**  
  Jupyter Notebook containing exploratory analysis and visualizations for Research Question 1.

- **data/README.md**  
  Explains how the dataset is accessed directly from HuggingFace and why raw data is not stored in the repository.

---
