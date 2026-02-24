# Store Performance Analysis: Divestment Strategy
## Project Purpose
The goal of this project is to use data-driven insights to determine which of four retail branches should be sold based on its historical performance. By analyzing transaction data across multiple dimensions, the project seeks to identify systemic weaknesses and provide a strategic recommendation to optimize the business footprint.

## Project Structure
The analysis follows a structured pipeline to evaluate each location:

* Total Revenue per Store: A comparative analysis of gross earnings to identify the top and bottom performers.

* Sales by Category: Evaluating market share and penetration in core segments like Electronics and Appliances.

* Average Store Rating: Measuring customer satisfaction and service quality.

* Top and Bottom Products: Identifying product turnover rates and inventory efficiency.

* Average Shipping per Store: Analyzing logistics costs paid by clients to determine operational reach.

## Insights & Visualizations
* The Revenue Deficit: Visualizations highlight that Store 4 lags behind its peers, failing to cross the $1.1B revenue mark achieved by other units.
  
  <img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/097c0140-be87-4575-92a4-b1dc7f8871cf" />


* Category Performance Gap: Data shows that Store 4 significantly underperforms in the "Electronics" and "Appliances" categories, which are the primary revenue drivers for the company.

  <img width="1170" height="525" alt="newplot" src="https://github.com/user-attachments/assets/b7f66299-08b9-436d-832f-d7d947136135" />


* Satisfaction Benchmarking: Store 4 consistently ranks below the high-performance benchmarks set by Stores 2 and 3.

  <img width="851" height="554" alt="image" src="https://github.com/user-attachments/assets/323284e2-d84d-496c-8a21-d9d972a989ab" />

|Analysis|Store 1|Store 2|Store 3|Store 4|
|-------|-------|-------|-------|-------|
|Revenue|1150880400.0|1116343500.0|1098019600.0|1038375700.0|
|Average store rating|3.98/5|4.04/5|4.05/5|4.0/5|
|Average Shipping Cost|26018.61|25216.24|24805.68|23459.46|
|Max Sales Volume|214|223|191|196|
|Min Sales Volume|78|89|94|88|


## How to Run the Notebook
Clone the Repository:

    git clone https://github.com/your-username/store-analysis.git

## Tech Stack
* [![Python 3](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
* [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
* [![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/)
* [![Seaborn](https://img.shields.io/badge/Seaborn-%23447091.svg?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)
* [![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)

## Execution:
Open Store_Analysis.ipynb in any Jupyter environment (VS Code, JupyterLab, or Google Colab) and run all cells. The notebook is designed to automatically process the datasets and generate the final report table.
