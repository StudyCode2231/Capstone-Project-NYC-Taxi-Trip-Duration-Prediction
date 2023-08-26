# NYC Taxi Trip Duration Prediction - 2023 🚖📊

<details>
<summary>📑 Table of Contents</summary>

1. [About the Project](#about-the-project)
2. [Dataset Description](#dataset-description)
3. [Feature Engineering and Data Pre-processing](#feature-engineering-and-data-pre-processing)
4. [Model Implementation](#model-implementation)
5. [Model Evaluation and Results](#model-evaluation-and-results)
6. [Conclusion](#conclusion)
7. [Libraries Used](#libraries-used)
8. [Contact](#contact)

</details>

## 🚀 About the Project

Welcome to the NYC Taxi Trip Duration Prediction project! 🗽🚕 In collaboration with the NYC Taxi and Limousine Commission, we're diving into a thrilling journey of predicting taxi trip durations. Our goal is to harness the power of data and build a top-notch regression model that accurately forecasts the time it takes for a taxi ride. 📈💡

## 📊 Dataset Description

Let's talk data! 📋 Our dataset is a treasure trove of information about taxi trips:

- **id**: Unique trip identifier
- **vendor_id**: Code for trip provider
- **pickup_datetime**: When the ride started
- **dropoff_datetime**: When the ride ended
- **passenger_count**: Number of passengers
- **pickup_longitude**, **pickup_latitude**: Where the ride began
- **dropoff_longitude**, **dropoff_latitude**: Where the ride concluded
- **store_and_fwd_flag**: Was the trip stored before sending? (Y/N)

And the target we're after:

- **trip_duration**: Duration of the trip in seconds ⏱️

## 🔧 Feature Engineering and Data Pre-processing

We're transforming raw data into gold! ✨ Here's what we've done:

- Extracted meaningful features from pickup/dropoff times 🕒
- Tamed outliers and mapped coordinates within NYC 🗺️
- Crafted specialized datasets by tinkering with features 🧪
- Perfected the art of data scaling and transformation 📈

## 🧠 Model Implementation

Now, the magic happens! 🪄 Our models lineup includes:

1. Linear Regression
2. Lasso & Ridge Regularization
3. Polynomial Regression
4. Light Gradient-Boosting Machine
5. Decision Trees
6. XGBoost

These models are like instruments in a symphony, each adding its own flavor to the prediction masterpiece!

## ⚙️ Model Evaluation and Results

Time to unveil the stars 🌟 Here are the top performers:

| Model                 | Test RMSE | Test R² |
| :-------------------- | :--------: | :------: |
| Linear Regression     | 28.31 | 0.58 |
| Lasso Regression     | 28.31 | 0.58 |
| Ridge Regression     | 28.31 | 0.58 |
| Polynomial Regression | 23.41 | 0.65 |
| Decision Trees        | 18.10 | 0.73 |
| LightGBM              | 13.05 | 0.81 |
| XGBoost               | 12.68 | 0.81 |

## 🎉 Conclusion

Our journey ends with valuable insights 🌆 The XGBoost model steals the spotlight, revealing that distance matters most, while vendor ID isn't a showstopper. 🚀 Feature engineering and smart dataset iterations brought out the best in our predictions.

## 📚 Libraries Used

We owe it all to these libraries:

- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn, Folium for visualization
- Statsmodels, SciPy, Scikit-Learn for analysis
- ELI5 for model explanations

## 📞 Contact

Got questions? Reach out: [📧 Email](mailto:supratikghosh044@gmail.com)

Let's keep predicting and exploring the world, one taxi ride at a time! 🌍🚖🔮
