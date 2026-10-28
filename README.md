# Data and Decision Making

Coursework notebooks for the Data and Decision Making module, written in Python on Google Colab.

**Author:** Erinda Simakaj · **GitHub:** [@Erinda27](https://github.com/Erinda27)

## Notebooks

| Notebook | Topic | What it does |
| --- | --- | --- |
| [`Unit_5_HR_CSV.ipynb`](Unit_5_HR_CSV.ipynb) | HR employee turnover | Marks each employee as active or terminated from the termination date, compares termination rates by gender, race and department with bar charts, and reports overall turnover. |
| [`unit_7_consolidate.ipynb`](unit_7_consolidate.ipynb) | Bitcoin and social media marketing (NLP) | Combines several Excel exports of social media posts, checks data quality, cleans the text (URLs, mentions, symbols, stop words), tokenises, stems and lemmatises it, and analyses the most frequent words. |

## How to run

1. Open a notebook on GitHub and click the **Open in Colab** badge at the top.
2. Run the cells in order. The first cells ask you to upload the data file(s):
   - Unit 5: the HR CSV file
   - Unit 7: the Excel files of social media posts
3. Charts and tables appear under each cell.

To run locally instead, install `pandas`, `matplotlib`, `numpy`, `nltk`, `textblob`, `openpyxl` and `wordcloud`, and replace the `google.colab` upload cell with `pd.read_csv(...)` or `pd.read_excel(...)` pointing at your file.

## Data

The datasets were provided for the module and are not included in this repository.
