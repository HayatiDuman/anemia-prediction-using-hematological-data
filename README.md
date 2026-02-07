# CENG313 Data Science Project

### Repository Contents
* `v3_anemiaProject.ipynb` : Source code
* `Anemia_Dataset.xlsx`    : Dataset
* `Group7-report.pdf`      : Technical Report

---

### Execution Protocols (Ordered by Stability)

#### Method 1: Manual Import to Colab
Use this if the direct link is inaccessible.

1.  **Upload Notebook:** Upload `v3_anemiaProject.ipynb` to Google Colab.
2.  **Upload Dataset:**
    * Open the **Files** pane (folder icon on left).
    * Drag & Drop `Anemia_Dataset.xlsx` into the root session storage.
    * *Constraint:* Filename must match `Anemia_Dataset.xlsx` exactly.
3.  **Execution:** Select **Runtime > Run all**.

#### Method 2: Local Environment
Requires Python 3.x environment.

1.  **Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn gradio openpyxl
    ```
2.  **Setup:** Place `v3_anemiaProject.ipynb` and `Anemia_Dataset.xlsx` in the **same root directory**.
3.  **Execution:** Launch Jupyter Notebook and run all cells.

Dataset Source: https://data.mendeley.com/datasets/y7v7ff3wpj/1
