---
layout: single
title: "Projects Portfolio"
permalink: /projects/
author_profile: true
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/bg3.jpg
  actions:
    - label: "View My CV"
      url: "/cv/"
excerpt: "Data science, machine learning, and optimization projects focused on energy systems, power grids, and renewable energy integration."
---

Welcome to my projects portfolio! Here you'll find a collection of my work in data science, machine learning, and software engineering. Each project demonstrates different aspects of my technical skills and problem-solving approach.

---

<div class="project-grid">

<!-- GridGEN Project -->
<div class="project-item">
  <h1>GridGEN: Synthetic Distribution Grid Data Generation</h1>
  <div class="project-thumbnail">
    <figure>
      <img src="/assets/images/projects/gridgen-thumbnail.jpg" alt="GridGEN Thumbnail" />
      <figcaption><a href="https://doi.org/10.1016/j.patcog.2021.108202" target="_blank" rel="noopener noreferrer">Image Source</a></figcaption>
    </figure>
  </div>
  <div class="project-content">
    <p>Developed a Variational Graph Autoencoder (VGAE) model to generate synthetic distribution grid datasets for power system research and benchmarking.</p>
    
    <h4>Key Features:</h4>
    <ul>
      <li>Graph-based generative model using PyTorch Geometric</li>
      <li>Variational autoencoder architecture for distribution grids</li>
      <li>Comprehensive evaluation on real-world grid topologies</li>
      <li>Published research with open-source implementation</li>
    </ul>
    
    <h4>Tech Stack:</h4>
    <p><strong>Languages:</strong> Python<br>
    <strong>Libraries:</strong> PyTorch, PyTorch Geometric, NetworkX, Pandas, NumPy, PyPSA<br>
    <strong>Tools:</strong> Jupyter, Git, LaTeX</p>
    
    <div class="project-buttons">
      <a href="https://arxiv.org/abs/2509.02469" class="btn btn--primary" target="_blank">
        <i class="fas fa-external-link-alt"></i> arXiv Paper
      </a>
      <a href="https://github.com/syedzainabbas/gridgen" class="btn btn--info" target="_blank">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
  </div>
</div>
<br>

<!-- Time Series Forecasting Project -->
<div class="project-item">
  <h1>Time Series Forecasting: Electricity Price Prediction</h1>
  <div class="project-thumbnail">
    <figure>
      <img src="/assets/images/projects/electricity-price-forecasting-thumbnail.jpg" alt="Electricity Price Prediction Thumbnail" />
      <figcaption><a href="https://energygain.co.uk/uk-electricity-prices-double-in-a-year/" target="_blank" rel="noopener noreferrer">Image Source</a></figcaption>
    </figure>
  </div>
  <div class="project-content">
    <p>This project focuses on forecasting day-ahead electricity prices using various machine learning and deep learning approaches. The goal is to predict 24-hour electricity prices (D+1) based on historical price data, demand forecasts, and generation forecasts, using strictly causal features up to D 23:00.</p>
    
<h4>Key Features:</h4>
<ul>
  <li><strong>Multi-Architecture Neural Network Comparison:</strong> Comprehensive evaluation of LSTM and GRU architectures with configurable hidden units (24) and single-layer design optimized for 24-hour electricity price forecasting</li>
  <li><strong>Advanced Feature Engineering Pipeline:</strong> Sophisticated temporal feature creation including lag variables (1, 24, 48, 168 hours), rolling statistics (24, 168-hour windows), and time-based features for comprehensive market signal capture</li>
  <li><strong>Ensemble Methods Integration:</strong> Implementation of Random Forest and XGBoost algorithms alongside neural networks for robust performance comparison and model selection under operational constraints</li>
  <li><strong>Explainable AI Framework:</strong> Dual interpretability approach using Captum Integrated Gradients and SHAP values for feature attribution analysis, enabling transparent model decisions and regulatory compliance</li>
  <li><strong>Time Series Cross-Validation Strategy:</strong> 10-fold walk-forward validation with 168-hour input windows and daily increment progression, ensuring temporal integrity and realistic performance evaluation for day-ahead market operations</li>
  <li><strong>Operational Deployment Considerations:</strong> Real-world constraint modeling with noon deadline submissions for day-ahead markets, comparing model performance under complete vs. limited data availability scenarios</li>
  <li><strong>Multi-Modal Data Integration:</strong> Fusion of historical electricity prices, demand forecasts, and generation mix data with automated preprocessing and feature scaling for robust market prediction</li>
</ul>
    
    <h4>Tech Stack:</h4>
    <p><strong>Languages:</strong> Python<br>
    <strong>Libraries:</strong> Pytorch, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn<br>
    <strong>Tools:</strong> Jupyter Notebook, Git</p>
    
    <div class="project-buttons">
      <a href="https://github.com/SyedZainAbbas/Time-Series-Forecasting-Electricity-Price-Prediction" class="btn btn--info" target="_blank">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
    
    <div class="project-results">
      <figure>
        <img src="/assets/images/projects/gru_forecast_10_10.png" alt="Electricity Price Prediction Results" />
        <figcaption><strong>Electricity Price Prediction Results using GRU</strong></figcaption>
      </figure>
    </div>
  </div>
</div>

<!-- Time Series Forecasting Project -->
<div class="project-item">
  <h1>Time Series Forecasting: Wind Power Prediction</h1>
  <div class="project-thumbnail">
    <figure>
      <img src="/assets/images/projects/wind-forecasting-thumbnail.png" alt="Wind Power Prediction Thumbnail" />
      <figcaption><a href="https://www.resourceliving.org/blog/why-wind-turbines-are-beautiful" target="_blank" rel="noopener noreferrer">Image Source</a></figcaption>
    </figure>
  </div>
  <div class="project-content">
    <p>Built an LSTM-based deep learning model for accurate wind power forecasting to support renewable energy integration and grid planning.</p>
    
    <h4>Key Features:</h4>
    <ul>
      <li><strong>Long Short-Term Memory (LSTM) Neural Network Architecture:</strong> Deep learning model with 2 stacked LSTM layers (128 hidden units each) and dropout regularization for robust wind power forecasting</li>
      <li><strong>Multi-variate Time Series Analysis:</strong> 8-feature input including wind speed, direction, temperature (external/internal), nacelle direction, and blade pitch angles for comprehensive turbine state modeling</li>
      <li><strong>Advanced Data Pipeline with Sliding Window Approach:</strong> Automated preprocessing with 18-timestep sequences (3-hour windows) and configurable forecast horizons for temporal pattern extraction</li>
      <li><strong>Comprehensive Model Validation Framework:</strong> Three-phase training strategy with separate validation, hyperparameter tuning, and unbiased test evaluation using multiple regression metrics (MSE, MAE, RMSE, R²)</li>
      <li><strong>Real-time Grid Management Applications:</strong> 10-minute ahead forecasting capabilities with robust performance monitoring and visualization tools for practical renewable energy integration</li>
    </ul>
    
    <h4>Tech Stack:</h4>
    <p><strong>Languages:</strong> Python<br>
    <strong>Libraries:</strong> Pytorch, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn<br>
    <strong>Tools:</strong> Jupyter Notebook, Git</p>
    
    <div class="project-buttons">
      <a href="https://github.com/SyedZainAbbas/Time-Series-Forecasting-Wind-Power-Prediction" class="btn btn--info" target="_blank">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
    
    <div class="project-results">
      <figure>
        <img src="/assets/images/projects/wpp_lstm_results.png" alt="Wind Power Prediction Results" />
        <figcaption><strong>Wind Power Prediction Results</strong></figcaption>
      </figure>
    </div>
  </div>
</div>

<!-- Energy System Sizing Project -->
<div class="project-item">
  <h1>Energy System Sizing: Optimal PV & Battery Configuration</h1>
  <div class="project-thumbnail">
    <figure>
      <img src="/assets/images/projects/pv-sizing-thumbnail.gif" alt="Energy System Sizing Thumbnail" />
      <figcaption><a href="https://ultimatesolarenergy.com.au/solar-battery-storage/" target="_blank" rel="noopener noreferrer">Image Source</a></figcaption>
    </figure>
  </div>
  <div class="project-content">
    <p>Developed an optimization framework for residential photovoltaic systems and battery storage to maximize long-term economic benefits and energy independence.</p>
    
    <h4>Key Features:</h4>
    <ul>
      <li><strong>Multi-Algorithm Optimization Framework:</strong> Highlights the sophisticated SciPy-based optimization engine that compares multiple algorithms and automatically selects the best performer</li>
      <li><strong>Comprehensive Techno-Economic Modeling:</strong> Emphasizes the integrated approach combining PV generation physics, battery dynamics, and 20-year financial analysis</li>
      <li><strong>High-Resolution Energy System Simulation:</strong> Showcases the detailed temporal modeling capabilities for accurate energy balance calculations</li>
      <li><strong>Advanced Battery Energy Storage System (BESS) Integration:</strong> Focuses on the sophisticated battery modeling with SOC management and efficiency considerations</li>
      <li><strong>Automated Results Analysis and Visualization:</strong> Highlights the clean reporting system with comparison tools and visualization capabilities</li>
    </ul>
    
    <h4>Tech Stack:</h4>
    <p><strong>Languages:</strong> Python<br>
    <strong>Libraries:</strong> SciPy, Pandas, NumPy, Matplotlib, Seaborn<br>
    <strong>Tools:</strong> Jupyter Notebook, Git</p>
    
    <div class="project-buttons">
      <a href="https://github.com/syedzainabbas/pv-battery-sizing" class="btn btn--info" target="_blank">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
    
    <div class="project-results">
      <figure>
        <img src="/assets/images/projects/system_sizing_results.png" alt="Energy System Sizing Results" />
        <figcaption><strong>Energy System Sizing Results</strong></figcaption>
      </figure>
    </div>
  </div>
</div>

</div>

<!-- ---

<div class="notice--primary">
  <h4>💡 Interested in Collaborating?</h4>
  <p>I'm always excited to work on challenging projects and explore new technologies. If you have an interesting project or opportunity, <a href="/contact/">let's connect</a>!</p>
</div> -->
