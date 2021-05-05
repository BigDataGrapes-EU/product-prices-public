# Product Prices
A visualisation for the price evolution of European products with price predictions.

![Screenshot of the visualisation without uncertainty fans](https://github.com/BigDataGrapes-EU/product-prices/blob/Jeroen/screenshotNoUncertainty.png)

In order to make the prediction model more transparent, uncertainty fans can be enabled.

![Screenshot of the visualisation with uncertainty fans](https://github.com/BigDataGrapes-EU/product-prices/blob/Jeroen/screenshotUncertainty.png)

## Installation
Execute the following steps to run the visualisation on your machine.

1. Execute the following commands:
```
git clone https://github.com/BigDataGrapes-EU/product-prices.git
git checkout user-study-docker
cd product-prices
docker-compose up -d --build
```
2. The visualisation is now running on http://localhost:3541/.

The databases are hosted externally at [MongoDB Atlas](https://cloud.mongodb.com).
