# Video Game Sales Forececasting

## What the Project Does

This project analyzes a dataset of historical global video game sales (1980–2016) to **identify and model the core factors that determine a game's success**. Specifically, it focuses on:

1.  **Data Preparation and Cleaning:** Handling missing values (including the unique 'TBD' case for user scores), correcting data types, and standardizing column names.
2.  **Trend Analysis:** Determining the relevant time frame for forecasting, analyzing platform life cycles (appearance and decay), and identifying current market leaders.
3.  **Success Factor Modeling:** Investigating the correlation between game reviews (critic and user scores) and sales across different platforms.
4.  **Regional Market Profiling:** Creating detailed user profiles for North America (NA), Europe (EU), and Japan (JP), including top platforms, top genres, and the impact of **ESRB ratings** on sales in each region.
5.  **Hypothesis Testing:** Statistically testing two key hypotheses using T-tests:
      * Whether the average user ratings for the **Xbox One** and **PC** platforms are the same.
      * Whether the average user ratings for the **Action** and **Sports** genres are different.

The ultimate deliverable is a set of **data-backed recommendations for a 2017 advertising campaign**.

-----

## Why the Project Is Useful

This project delivers essential **business intelligence** for the (fictitious) online store, Ice, addressing critical needs in marketing and strategy:

  * **Optimized Advertising ROI:** By identifying platforms and genres with the highest potential for success, the project ensures marketing dollars are spent efficiently on the most profitable segments for the upcoming year.
  * **Strategic Forecasting:** It establishes a methodology for determining the **relevant data period** for a forecast, a key step in any time-series analysis or forward-looking business plan.
  * **Geographic Customization:** The detailed regional profiles allow the marketing team to tailor advertising messages and game selection to specific cultural and demographic preferences, such as the distinct platform and genre dominance observed in the Japanese market.
  * **Risk Mitigation:** The analysis of review score correlation helps the company prioritize or deprioritize games based on review performance, reducing the risk of investing heavily in titles with low critical/user reception.

-----

## How Users Can Get Started with the Project

To explore and run this analysis, you will need a Python environment with the following libraries:

### Prerequisites

1.  **Python 3.x**
2.  **Jupyter Notebook** (or JupyterLab)

### Installation

Clone the repository and install the required Python libraries:

```bash
# Clone the repository
git clone <repository-url>
cd video-game-sales-forecasting

# Install dependencies
pip install pandas numpy matplotlib scipy
```

### Running the Notebook

1.  Place the provided dataset (`games.csv`) in the root directory of the cloned project folder.

2.  Launch Jupyter Notebook or JupyterLab:

    ```bash
    jupyter notebook
    ```

3.  Open the file **`Sprint 5 Final Project - Video Game Sales Forecasting (approved).ipynb`**.

4.  Run the cells sequentially to reproduce the data preparation, analysis, and conclusions.

-----

## Where Users Can Get Help with Your Project

If you encounter any issues, have questions about the methodology, or wish to discuss the findings:

  * **Open a GitHub Issue:** The fastest way to get support is to open a new **[Issue](https://www.google.com/search?q=%3Crepository-url%3E/issues)** in this repository. Please provide a detailed description of the problem, including any error messages.
  * **Discussion:** For general questions about the data, analysis, or interpretation, use the **[Discussions](https://www.google.com/search?q=%3Crepository-url%3E/discussions)** tab.

-----

## Who Maintains and Contributes to the Project

### Maintainer

  * **[YT-MrHuman]** 

### Contributions

All contributions, bug reports, feature suggestions, and pull requests are welcome\!

1.  Fork the repository.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

Your contributions help make this analysis more robust and insightful\! 💡
