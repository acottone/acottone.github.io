{% include header.html %}

# Projects

A selection of academic and personal projects demonstrating skills in statistics, machine learning, and data analysis.

---

## Machine Learning & Predictive Modeling

### Filmlytics: Movie Audience Score Prediction
- **Tools:** Python, PyTorch, XGBoost, HuggingFace Transformers, Pandas, MongoDB, Plotly, Streamlit
- **Problem:** Predict audience reception for films and compare graph-based learning with tabular ML; integrate heterogenous entertainment data
- **Approach:**  
  - Integrated movie metadata, reviews, and engagement metrics from multiple APIs and scraped sources  
  - Engineered 150+ features (budget, cast/crew composition, sentiment, engagement)  
  - Built film similarity and heterogeneous knowledge graphs  
  - Trained GNN, KGCN, and XGBoost models; combined via stacking ensemble  
  - Deployed predictions using a Streamlit web app  

**Key Skills:** End-to-end ML system design, feature engineering at scale, graph-based learning, NLP integration, model evaluation, deployment

[Github Repo](https://github.com/acottone/film-audience-score/tree/main)

---

## Healthcare & Statistical Modeling

### Predicting Length of Hospital Stay
- **Tools:** R, MASS, glmnet, dplyr, ggplot2, caret
- **Problem:** Predict inpatient hospital LOS, handling overdispersion and maintaining interpretability
- **Approach:**  
  - Compared Poisson, Quasi-Poisson, and Negative Binomial GLMs  
  - Applied Lasso for variable selection (29 → 18 predictors)  
  - Validated models with cross-validation (RMSE/MAE)  

**Key Skills:** Count regression, regularization, cross-validation, interpretable modeling

[Github Repo](https://github.com/acottone/predicting-length-of-hospital-stays)

### Healthcare Network PageRank Analysis
- **Tools:** Python, NumPy, SciPy, Pandas, Matplotlib, Plotly
- **Problem:** Identify influential providers in a million-node referral network; quantify risk propagation
- **Approach:**  
  - Constructed directed referral graph from CMS Physician Shared Patient Patterns  
  - Implemented scalable PageRank with sparse linear algebra  
  - Analyzed network using centrality metrics and risk propagation models

**Key Skills:** Large-scale network analysis, sparse linear algebra, PageRank, risk modeling, performance benchmarking

[Github Repo](https://github.com/acottone/pagerank-shared-patterns)

---

## Statistical & Time Series Analysis

### Time Series Analysis of CAR Economic Data
- **Tools:** R, RStudio, forecast, tseries, ggplot2, R Markdown
- **Problem:** Analyze economic indicators (GDP, exports, population) for CAR; generate reproducible forecasts
- **Approach:**  
  - Preprocessed annual time series and applied log transformations  
  - Tested stationarity using ADF; identified ARIMA models using ACF/PACF and AICc  
  - Validated models via residual diagnostics and cross-correlation analysis  
  - Produced out-of-sample forecasts with 80% & 95% CI  

**Key Skills:** Time series decomposition, ARIMA modeling, forecasting with uncertainty, reproducible reporting

[Github Repo](https://github.com/acottone/time-series-car-economic-data)

---

## Reinforcement Learning & Algorithms

### Mancala Reinforcement Learning
- **Tools:** Python, NumPy, Matplotlib
- **Problem:** Build RL agent for Mancala with effective strategy and stable learning
- **Approach:**  
  - Implemented Q-learning, Double Q-learning, and hybrid softmax + epsilon-greedy strategies  
  - Performed ablation studies on reward shaping and learning rate decay  
  - Applied state aggregation to reduce complexity  
  - Evaluated models via repeated training and win-rate analysis

**Key Skills:** RL experimentation, reward engineering, exploration–exploitation tuning, convergence analysis

[Github Repo](https://github.com/acottone/mancala-reinforcement-learning)

---

## Data Collection & Visualization

### Comparing Academy Graduates
- **Tools:** Python, Pandas, BeautifulSoup, Plotly, Jupyter Notebook
- **Problem:** Compare player development across two football academies
- **Approach:**  
  - Scraped match stats, market values, and performance ratings  
  - Cleaned and aligned longitudinal data; engineered per-90 metrics  
  - Built interactive dashboards for player-level comparisons

**Key Skills:** Web scraping, time series analysis, feature engineering, interactive visualization

[Github Repo](https://github.com/acottone/comparing_academy_graduates)
