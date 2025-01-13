<h1> Bike Sharing Demand Prediction </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus is to With the growing number of customers and an expanding network of bike stations, predicting the number of bike rentals at any given time is crucial. This prediction can help the company optimize bike distribution, reduce operational costs.

## 2. Data Sources
- [Dataset Bike Sharing](https://drive.google.com/drive/folders/17Mw_4wSRiBB5vLLQJN137AlAbyB3CLFx) - The bike-sharing dataset was collected between January 1, 2011, and December 31, 2012.


## 3. Technologies Used
- Programming Language: Python (e.g., Pandas, NumPy)
- Visualization: Matplotlib, Seaborn, Plotly
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight

1. Incorporate an error margin buffer into operational planning to ensure sufficient bikes are available. For example, allocate an additional 25 bikes per location during peak periods to minimize missed revenue opportunities.

1. Combine demand predictions with historical trends and weather data to improve forecasting accuracy further.

1. Consider seasonal inventory adjustments or offering discounts for less popular times to redistribute demand more evenly.

1. Use the model predictions along with real-time monitoring of rental data to dynamically redistribute bike inventory across high-demand locations.

1. Implement a reservation system that allows users to pre-book bikes during busy periods, ensuring availability and improving satisfaction.

### 5.2 Actionable Recommendation
1. **Optimize Resource Allocation** <br>
Given the strong performance of the model, with R² values of 0.970 (seen) and 0.982 (unseen), the business can confidently rely on the model to forecast demand more accurately. To maximize profitability, we recommend optimizing bike allocation based on predicted demand. This could involve adjusting the number of bikes available in specific locations, ensuring sufficient availability during peak demand periods, and reducing excess supply during off-peak times to minimize idle bike costs.

1. **Enhance Operational Efficiency**<br>
The RMSE and MAE values (31.36 and 19.35 for seen data, 23.78 and 14.62 for unseen data) suggest that the model's predictions are fairly accurate but still leave room for improvement. We recommend continuous model refinement, focusing on reducing prediction errors. This can be achieved by integrating additional variables that may influence demand, such as weather conditions, local events, or holidays, to make the model more robust and adaptive to changing circumstances.

1. **Implement Dynamic Pricing Strategy**<br>
The MAPE values (16.2% for seen data and 11.2% for unseen data) indicate that prediction errors are relatively low but still present. A potential business strategy to mitigate the effects of these errors could be the introduction of dynamic pricing. By adjusting rental fees based on predicted demand fluctuations, the business can capitalize on periods of high demand while encouraging rental during less busy times. This strategy could improve both revenue and customer satisfaction.

## 6. Contact
- Name: Elia Samuel
- Email: [samuelelia0907@gmail.com](elikukug34@gmail.com)
- Linkedin: [https://www.linkedin.com/in/elia-samuel-992475324/](https://www.linkedin.com/in/elia-samuel-992475324/)
