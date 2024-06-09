# Stock Market Price Prediction(Minor Project)

## Overview
This project aims to predict stock market prices using various machine learning techniques. By analyzing historical stock prices and other relevant financial data, the model can provide insights and forecasts for future stock prices. This can be valuable for traders, investors, and financial analysts.


## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Data](#data)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
To run this project, you need to have Python installed. It is recommended to use a virtual environment to manage dependencies. Follow the steps below to set up the project:

1. Clone the repository:
```
git clone https://github.com/devShivaniP/stock-market-price-prediction.git
cd stock-market-price-prediction
```

2. Create a virtual environment:
```
python -m venv venv
```

3. Activate the virtual environment:
- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```

4. Install the required packages:
```
pip install -r requirements.txt
```

## Data
The data used in this project includes historical stock prices and various financial indicators, such as:
- Open price
- Close price
- High price
- Low price
- Volume
- Other indicators (e.g., Date, Adjacent Close)

## Models
The project explores different machine learning and deep learning models, including:
- Linear Regression
- SVR
- Random Forest

## Evaluation
Model performance is evaluated using various metrics, including:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
I would like to thank the contributors and the open-source community for their valuable resources and support. Special thanks to [Finance Yahoo](https://finance.yahoo.com/) for providing datasets and [Scikit-learn](https://scikit-learn.org/) for the machine learning tools. We are highly indebted to Dr. Swati Verma (Project Guide) and Dr. RAKESH BISHT (Assistant Professor and Project Head) of our college for their guidance and constant supervision as well as for providing necessary information regarding the project & also for their support in completing the project.


## References
1. https://finance.yahoo.com/quote/KO/history?period1=1514937600&period2=1672444800&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
2. https://ieeexplore.ieee.org/abstract/document/8703332/
 https://www.analyticsvidhya.com/blog/2021/05/feature-scaling-techniques-in-python-a-complete-guide/
3. https://towardsdatascience.com/random-forest-regression-5f605132d19d
4. https://towardsdatascience.com/unlocking-the-true-power-of-support-vector-regression-847fd123a4a0#:~:text=Support%20Vector%20Regression%20is%20a,the%20maximum%20number%20of%20points.

5. https://www.researchgate.net/publication/331279199_Stock_Market_Prediction_Using_Machine_Learning
6. Predicting the direction of stock market prices using random forest by [Luckyson Khaidem](khaidem90@gmail.com), [Snehanshu Saha](snehanshusaha@pes.edu) and [Sudeepa Roy Dey](sudeepar@pes.ed)
