

<h1 align='center'> Tukey’s Honest Significant Difference | Comparing Group Differences</h1>

## 📝 Overview

This project explores **Tukey’s Honest Significant Difference test** as a robust statistical method for comparing group means after conducting **ANOVA**. In real-world data analysis, we often need to determine not just whether groups are different, but **which specific groups differ**. This project implements the HSD procedure in **Python** to allow precise post-hoc comparisons across multiple groups. By providing detailed insights into group-level differences, the analysis helps researchers, students, and professionals make statistically sound conclusions while minimizing the risk of false positives due to multiple comparisons.

The workflow was carefully designed to ensure replicability, clarity, and flexibility. The project demonstrates not only the implementation of statistical methods but also best practices in **data analysis workflow, reproducibility, visualization, and interpretation**.

---

## ⚙️ Workflow / Methodology

The project follows a structured, professional workflow:

1. **Data Preparation**

   * Import dataset (real or simulated).
   * Clean, preprocess, and ensure assumptions for ANOVA are met.

2. **Exploratory Data Analysis (EDA)**

   * Summary statistics and descriptive plots.
   * Checking distribution and variance assumptions.

3. **ANOVA (Analysis of Variance)**

   * Test for overall significance across groups.
   * Identify whether group differences exist.

4. **Tukey’s Honest Significant Difference (HSD) Test**

   * Perform post-hoc analysis to compare pairs of groups.
   * Adjust for multiple testing to reduce Type I error.

5. **Results Interpretation**

   * Tabular summary of significant differences.
   * Visualizations to highlight where differences lie.

6. **Documentation and Reporting**

   * Structured output in both text and graphical formats.
   * Clear interpretation of findings.

## 🛠️ Tools and Technologies Used

This project was built in **Python** and demonstrates proficiency with the following libraries:

* **pandas** → Data manipulation and analysis
* **numpy** → Numerical computations
* **scipy** → Statistical testing
* **statsmodels** → ANOVA and post-hoc tests (including Tukey’s HSD)
* **matplotlib** & **seaborn** → Data visualization and results plotting
* **Jupyter Notebook** → Interactive workflow, documentation, and reporting


## 📈 Results

* Conducted ANOVA to test overall group differences.
* Applied **Tukey’s HSD test** to identify **specific group pairs with statistically significant differences**.
* Visualizations (confidence intervals and mean difference plots) were generated to support statistical conclusions.
* Results show **clear group separation**, providing actionable insights for further decision-making or research.


## 💻 Usage and Installation

### 🔹 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/ukey-hsd-group-differences.git
cd ukey-hsd-group-differences
pip install -r requirements.txt
```

### 🔹 Usage

Run the analysis using Jupyter Notebook or directly via Python scripts:

```bash
python analysis.py
```

Or open the notebook:

```bash
jupyter notebook ukey_hsd_analysis.ipynb
```


## 🤝 Contribution

Contributions are welcome! If you’d like to:

* Improve the methodology
* Add datasets for testing
* Enhance visualization and reporting

Please fork the repository and create a pull request.


## 📜 License

This project is licensed under the **MIT License** – you’re free to use, modify, and distribute with attribution.


## 📬 Contact

👤 **Author**: \[Your Name]
📧 Email: [your.email@example.com](mailto:your.email@example.com)
🔗 LinkedIn: \[Your LinkedIn Profile]
🐙 GitHub: \[Your GitHub Profile]


✨ *This project is part of my professional data analysis portfolio, demonstrating expertise in statistical hypothesis testing, post-hoc analysis, and visualization using Python.*

--
