Author: Andre Veit

LinkedIn: https://www.linkedin.com/in/andreveit/

E-mail: andrev.veit@gmail.com

PRODUCT DEMAND FORECASTING
Time-Series Forecasting
demand_forecasting-3.jpg

About this notebook:
  Demand forecasting is the process of predict the future demand of products or services over a certain period of time to make intelligent business decisions. From inventory or production planning, warehouses and supply-chain, to price optimization and recommendations systems, it is crucial for the business to understand what is likely to happen in the near future.

  The goal behind this notebook is to solve the demand forecasting of products problem using different approaches. The data to be used throughout this study is from a manufacturing company and was available on Kaggle website. More information can be found below. The objective is to obtain between one and three months up front forecast, in order to provide the company with valuable intelligence to plan their production and supply-chain processes.

  This notebook is subdivided in 5 main parts. Firstly, a data cleaning, exploration and preparation was conducted in order to obtain a consistent time series be studied. The warehouse and product category having more data available were selected to be analyzed. On the next stages, forecasting values for order demand were generated through the SARIMA model, the Facebook Prophet package and a LSTM Recurrent Neural Network. Lastly, the results of the three methods plus a baseline model were compared through different metrics against the held out set (test set).

Dataset
The dataset analyzed was provided by FelixZhao on Kaggle website.

https://www.kaggle.com/felixzhao/productdemandforecasting

Below, FelixZhao's data description:

Data Context
  The dataset contains historical product demand for a manufacturing company with footprints globally. The company provides thousands of products within dozens of product categories. There are four central warehouses to ship products within the region it is responsible for. Since the products are manufactured in different locations all over the world, it normally takes more than one month to ship products via ocean to different central warehouses. If forecasts for each product in different central with reasonable accuracy for the monthly demand for month after next can be achieved, it would be beneficial to the company in multiple ways.

Acknowledgements
  This dataset is all real-life data and products/warehouse and category information encoded.
