# Apache Spark Project: Twitch Streamers Analysis

This repository contains an analysis of Twitch streamers using Apache Spark. The project is structured into different notebooks for Exploratory Data Analysis (EDA), SQL analysis, DataFrame API usage, and Machine Learning with MLlib.

## Notebooks Overview

1. **Twitch_EDA.ipynb**: Notebook focusing on exploratory data analysis of Twitch streamers dataset. Includes data cleaning, visualization of key metrics, and insights into streamers' characteristics.

2. **Twitch_SQL.ipynb**: Notebook demonstrating the use of Spark SQL for querying and analyzing the Twitch dataset. SQL queries are used to extract meaningful information and perform aggregations.

3. **Twitch_DataFrameAPI.ipynb**: Notebook showcasing the usage of Spark DataFrame API for data manipulation and transformation tasks on the Twitch dataset. Includes examples of filtering, aggregating, and joining data.

4. **Twitch_MLlib.ipynb**: Notebook implementing a regression task using Spark's MLlib library. Predicts average viewers per stream based on streamers' attributes. Includes model training, evaluation, and hyperparameter tuning.

## Dataset

The dataset used in this project is "Top 1000 Twitch Streamers Data", which includes various attributes such as rank, language, streamed games, average viewers, followers gained, etc.

## Setup and Requirements

To run the notebooks in this repository, you need:
- Apache Spark installed and configured
- Jupyter Notebook or JupyterLab for running the notebooks
- Python packages: pyspark, matplotlib, seaborn, pandas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Getting Started

1. Clone this repository:
```
git clone https://github.com/your-username/Apache-Spark.git
cd Apache-Spark
```

2. Launch Jupyter Notebook or JupyterLab:
```
jupyter notebook
```

Navigate to the desired notebook (e.g., `Twitch_EDA.ipynb`) to start exploring the analysis.

3. Follow the instructions and code in each notebook to explore, analyze, and visualize the Twitch streamers data.

## Contributing

Contributions to improve and extend this analysis are welcome! Please fork the repository, make your changes, and submit a pull request.
