# 📚 Goodreads Fiction Books Dataset (25,000 Books)

An end-to-end web scraping project — scraping, cleaning, and feature engineering 25,000 fiction books from Goodreads using Python and BeautifulSoup.

---

## 📌 Project Overview

This project demonstrates a complete web scraping pipeline:

1. **Web Scraping** — Scraped 500 pages of fiction books from Goodreads shelf
2. **Data Cleaning** — Handled nulls, fixed data types, extracted structured data from messy text using Regex
3. **Feature Engineering** — Added rating category, era, popularity, century, and clean title columns
4. **Export** — Saved final clean dataset as CSV ready for analysis

---

## 📊 Dataset Summary

| Property | Value |
|---|---|
| Source | Goodreads Fiction Shelf |
| URL | goodreads.com/shelf/show/fiction |
| Total Books | 25,000 |
| Pages Scraped | 500 |
| Columns | 8 |

---

## 📁 Columns

| Column | Description |
|---|---|
| `name` | Full book title with format |
| `clean_title` | Book title without format (Paperback, Hardcover etc) |
| `author` | Author name |
| `avg_rating` | Average rating (0-5) |
| `num_ratings` | Total number of ratings |
| `year_published` | Year the book was published |
| `rating_category` | Excellent / Good / Average / Below Average |
| `era` | Classic / Modern / Contemporary / Recent |
| `popularity` | Viral / Very Popular / Popular / Niche |
| `century` | 18th / 19th / 20th / 21st century |

---

## 🛠️ Tools & Technologies

- **Python** — core language
- **BeautifulSoup** — HTML parsing and web scraping
- **Requests** — HTTP requests
- **Pandas** — data cleaning and feature engineering
- **Regex** — extracting structured data from messy text
- **Jupyter Notebook** — development environment

---

## 🚀 How to Run

```bash
# Install dependencies
pip install requests beautifulsoup4 pandas lxml

# Run the notebook
jupyter notebook goodreads_scraping.ipynb
```

---

## 📂 Project Structure

```
├── goodreads_scraping.ipynb      # Main Jupyter notebook
├── goodreads_fiction_books.csv   # Final cleaned dataset
└── README.md                     # Project documentation
```

---

## 🔗 Links

- 📦 Kaggle Dataset: [https://www.kaggle.com/datasets/maherrimsha/goodreads-fiction-books-dataset-25000-books/data](#)
- 👤 LinkedIn: [https://www.linkedin.com/in/rimsha-shaukat-ai/](#)

---

## 📜 License

Dataset is published under **CC0 (Public Domain)** — free to use for any purpose.
