# 🎬 Movie Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)

---

## 📖 Table of Contents
- [Overview](#overview)
- [Files Included](#files-included)
- [Data Cleaning Steps](#data-cleaning-steps)
- [Usage](#usage)
---

## 📝 Overview
This repository contains a dataset of movies with details like `movie_id`, `title`, `imdb_rating`, and `studio`. The dataset was initially unclean and has been processed to make it **consistent, complete, and analysis-ready**.

---

## 📂 Files Included
- **`movies_raw.csv`** – Original dataset with issues such as:  
  - Combined `movie_id` and `title` in one column  
  - Missing IMDb ratings  
  - Missing or inconsistent studio names  
  - Extra spaces in text fields  

- **`movies_clean.csv`** – Cleaned dataset:  
  - Split `movie_id` and `title` into separate columns  
  - Missing `imdb_rating` filled with the column mean  
  - Missing `studio` replaced with `"Not Available"`  
  - Extra spaces removed and headers standardized  

---

## 🛠️ Data Cleaning Steps
1. **Separated Combined Column** – Used Excel Text-to-Columns to split `movie_id` and `title`.  
2. **Handled Missing IMDb Ratings** – Filled missing values with the **mean rating** of the column.  
3. **Cleaned Studio Column** – Replaced missing values with `"Not Available"` and removed extra spaces.  

---

## 🚀 Usage
- The **cleaned dataset** (`movies_clean.csv`) is ready for:  
  - Data analysis  
  - Visualization  


