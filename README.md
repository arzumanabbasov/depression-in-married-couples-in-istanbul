# Depression in Married Couples in Istanbul

This project aims to analyze the levels of depression among married couples in Istanbul and explore the influence of various demographic factors. The data was collected through an online form and includes information on demographic factors and Beck Depression Inventory (BDI) scores.

## Dataset

The dataset used for this analysis can be found in the file "Depression-in-Married-Couples-in-Istanbul.csv". It includes the following columns:

- Gender: 1-Female, 2-Male
- Education: 1-Primary, 2-High School, 3-Bachelor, 4-Msc or PhD
- Working Status: 1-Employed, 2-Unemployed
- Marriage Style: 1-Arranged Marriage, 2-Flirt Marriage
- Status of Having a Child: 1-Yes, 2-No
- BDI Scores: Calculated scores based on Beck Depression Inventory responses

## Analysis

The notebook "Depression-in-Married-Couples-in-İstanbul.ipynb" contains the code and analysis performed on the dataset. The following tasks are covered:

1. Loading and cleaning the data
2. Data manipulation and transformation
3. Basic statistics and data exploration
4. Visualizations and analysis of the data
5. Exploratory data analysis by gender and other factors

## Results

Some key findings from the analysis include:

- Women have higher average BDI scores, indicating higher levels of marital depression compared to men.
- Unemployed individuals tend to experience less marital depression than employed individuals.
- Higher education levels are associated with lower levels of marital depression.
- The type of marriage (arranged or flirt) appears to have an impact on marital depression, with lower levels observed in flirt marriages.
- The presence of children in the family is associated with lower levels of marital depression, particularly for women.

These findings provide insights into the factors influencing marital depression among couples in Istanbul.

## Requirements

To run the notebook and reproduce the analysis, you will need the following packages:

- pandas
- numpy
- matplotlib
- seaborn

You can install these packages using pip:

```
pip install pandas numpy matplotlib seaborn
```

## Usage

To use the notebook, follow these steps:

1. Download the dataset file "Depression-in-Married-Couples-in-Istanbul.csv".
2. Install the required packages (pandas, numpy, matplotlib, seaborn) if you haven't already.
3. Open the notebook "Depression-in-Married-Couples-in-İstanbul.ipynb" in a Jupyter Notebook environment.
4. Run each cell in the notebook to execute the code and generate the analysis.

Feel free to explore the code, modify it, or adapt it for further analysis or visualization.

## Credits

The data used in this project was collected via an online form and made available on [Kaggle](https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis).

## License

This project is licensed under the [MIT License](LICENSE).
