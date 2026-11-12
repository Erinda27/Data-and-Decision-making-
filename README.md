# Data and Decision Making

Applied analytics notebooks covering HR workforce attrition and social media NLP — written in Python on Google Colab.

**Author:** Erinda Simakaj · **GitHub:** [@Erinda27](https://github.com/Erinda27)

---

## Notebooks

| Notebook | Topic | What it covers |
|---|---|---|
| [`Unit_5_HR_CSV.ipynb`](Unit_5_HR_CSV.ipynb) | HR workforce attrition | Derives active/terminated status from termination dates, then segments turnover rates by gender, race and department. Surfaces department-level attrition patterns through comparative bar charts and reports overall headcount loss — the same analysis a people analytics team runs before a workforce planning cycle. |
| [`unit_7_consolidate.ipynb`](unit_7_consolidate.ipynb) | Social media NLP (Bitcoin marketing) | Consolidates multi-source Excel exports of social media posts, runs data quality checks, then applies a full NLP preprocessing pipeline: URL and mention removal, stop-word filtering, tokenisation, stemming and lemmatisation. Outputs term-frequency distributions and a word cloud to surface the dominant messaging themes across the dataset. |

---

## How to run

**On Colab (no local setup):** open a notebook on GitHub and click the **Open in Colab** badge. Upload the data file when prompted:

- Unit 5: the HR employee CSV
- Unit 7: the Excel exports of social media posts

Cells run top to bottom; outputs appear inline.

**Locally:** install dependencies with `pip install pandas matplotlib numpy nltk textblob openpyxl wordcloud`, then swap the `google.colab` upload cell for a standard `pd.read_csv(...)` or `pd.read_excel(...)` call pointing at the local file.

---

## Data

Datasets are not included in this repository.
