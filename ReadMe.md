# Job Interview Tasks

This repository collects my solutions and study notes for common data science and analytics interview prompts. Each subdirectory focuses on a different skill set, ranging from language-specific question banks to an end-to-end case study on natural language processing.

## Repository structure

| Folder | Description |
| --- | --- |
| `Python-Interview-Questions/` | A Jupyter notebook with **51 Python interview questions** and succinct answers that cover core syntax, object-oriented programming, functional utilities, and data manipulation patterns for data scientists. |
| `R-Interview-Questions/` | An R script mirroring the Python set, containing **51 R interview questions** with inline answers and code snippets that demonstrate data wrangling, visualization, modeling, and language fundamentals. |
| `kaspersky-lab-test/` | A full solution to a hiring assessment from Kaspersky Lab that evaluates a proprietary news text extraction library. Includes the exploratory notebook, exported PDF, input spreadsheet, and generated analysis CSV. |

## Getting started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Job-Interview-Tasks.git
   cd Job-Interview-Tasks
   ```
2. **Explore the question banks**
   - Open `Python-Interview-Questions/51-python-interview-questions.ipynb` in JupyterLab/Notebook to review the prompts and answers interactively.
   - Open `R-Interview-Questions/51-r-interview-questions.R` in your preferred R IDE to walk through the commented solutions.
3. **Review the Kaspersky Lab NLP case study**
   - Launch the `kaspersky-lab-test/solution-kutivadze.ipynb` notebook to rerun the analysis or read the generated `solution-kutivadze.pdf` for a static summary.

## Reproducing the Kaspersky Lab analysis

The NLP case study requires a Python 3.9+ environment with a few additional libraries:

```bash
pip install pandas newspaper3k sentence-transformers matplotlib nltk scikit-learn
```

Running the notebook will download NLTK resources on demand, fetch the reference articles listed in `Test_check.xlsx`, calculate similarity and importance metrics, and export the enriched dataset to `output-data.csv`.

> **Note:** Because the notebook retrieves the full text of every article, you will need an active internet connection.

## Contributing

These materials evolve as I refine interview prep resources and case studies. If you spot issues or have suggestions, feel free to open an issue or submit a pull request.

## License

Please check the contents of each folder for any specific licensing information before reuse.
