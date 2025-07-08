# 📊 Netflix Titles Dataset - Data Cleaning & Preprocessing

This repository contains the cleaned version of the Netflix Titles dataset, as part of the **Data Analyst Internship Task 1** at **Elevate Labs (MSME, Govt. of India)**.

## ✅ Task Objective

Clean and prepare a raw dataset containing:
- Null values
- Duplicates
- Inconsistent formats

### 🛠️ Tools Used
- Python
- Pandas Library

---

## 📁 Dataset

The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and includes information about movies and TV shows available on Netflix.

---

## 🧹 Cleaning & Preprocessing Steps

1. **Handled Missing Values**
   - Filled missing `director` values with `"Unknown"`.
   - Dropped rows where `title` was missing.

2. **Removed Duplicates**
   - Removed duplicate rows using `drop_duplicates()`.

3. **Standardized Text Data**
   - Converted text columns (e.g., `type`, `country`, `rating`) to lowercase or uppercase where appropriate.
   - Stripped unnecessary spaces.

4. **Formatted Dates**
   - Converted `date_added` column to datetime format (`dd-mm-yyyy`).

5. **Renamed Columns**
   - Changed column names to lowercase with underscores (`_`) instead of spaces.

6. **Fixed Data Types**
   - Ensured correct types (e.g., `release_year` as integer, `date_added` as datetime).

---

## 📂 Files Included

- `netflix_titles.csv` — Original dataset from Kaggle.
- `cleaned_netflix_titles.csv` — Cleaned and processed dataset.
- `summary_of_changes.md` — Summary of all changes made.

---

## 📌 Summary of Changes

A detailed breakdown of all preprocessing steps is available in `summary_of_changes.md`.

---

## 🤝 Contributing

Contributions are welcome! If you find additional improvements or want to enhance preprocessing, feel free to open a pull request.

---

## 📬 Contact

For any queries or collaboration, feel free to connect:

- 📧 Email: [your-email@example.com]
- 💼 LinkedIn: [your-linkedin-url]

---

## 📄 License

This project is licensed under the MIT License.

