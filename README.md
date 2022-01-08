# Financial_Planning_Tools
An application that evaluate client's financial health, specialize on building a fulllfill financial safety for your emergencies, transfer a visualization pie chart of your portfolio for data storytelling. Secondly, specializing on making up a proper plan for your Retirement by using Monte Carlo Simulation forecast with making api cal via the Alpaca SDK in order to get the information of data. Then evaluating the Monte Carlo Simulation results by using aggregation with summarizing the mean, summation, minimum and maximum. Next, analyzing the minimum and the maximum of expected value of the portfolio with 95% chance of posssible with different time frames

---

## Technologies

This project leverages [python](https://www.python.org/) 3.7 with the pandas library. Also, using [Jupyter notebook](https://jupyter.org/) in order to organize the code frame.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install pandas
  pip install jupyterlab
```

---


## Usage

To use this application, simply clone the repository and open jupyter lab from git bash by running the following command:

```jupyter lab```

After launching the application, navigate ``financial_planning_tools.ipynb`` notebook in the repository. 

Then in your Jupyter notebook, import the required libraries and dependencies.

```import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
import datetime as datetime
%matplotlib inline
```

### *Example*

*A visulaize chart that show your total investments portfolio*

![Portfolio_pie_chart](https://user-images.githubusercontent.com/94591580/148632707-43709b35-400e-485d-b68d-3a6e8e7acc86.png)

*An example of Monta Carlo Simulation model*

![5-4-monte-carlo-line-plot](https://user-images.githubusercontent.com/94591580/148632706-eeacc5c1-cf0f-4725-94b6-e581c5a44e47.png)

*Histogram chart provide the materials for aggeration process*

![5-4-monte-carlo-histogram](https://user-images.githubusercontent.com/94591580/148632705-7ae51a04-afb1-4bac-85a5-dc273f5156bf.png)


---

## Contributors

[Nguyen Dao](https://www.linkedin.com/in/nguyen-dao-a55669215/)

daosynguyen21@gmail.com


---

## License

MIT
