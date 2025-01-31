<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <header>
    <h1>Calorie Prediction Model</h1>
    <p>A machine learning model to predict calorie burn based on user activity features.</p>
  </header>

  <nav>
    <h2>Table of Contents</h2>
    <ul>
      <li><a href="#overview">Overview</a></li>
      <li><a href="#features">Features</a></li>
      <li><a href="#dataset">Dataset</a></li>
      <li><a href="#model">Model</a></li>
      <li><a href="#results">Results</a></li>
    </ul>
  </nav>

  <section id="overview">
    <h2>Overview</h2>
    <p>The Calorie Prediction Model leverages supervised machine learning techniques to estimate calorie burn rates based on user-provided features such as heart rate, duration of activity, and other physiological parameters.</p>
  </section>

  <section id="features">
    <h2>Features</h2>
    <ul>
      <li>Data preprocessing and feature engineering</li>
      <li>Model training and evaluation</li>
      <li>Prediction API interface</li>
      <li>Performance evaluation metrics</li>
      <li>Easily customizable for other datasets</li>
    </ul>
  </section>

  <section id="dataset">
    <h2>Dataset</h2>
    <p>Ensure your dataset contains relevant features such as:</p>
    <ul>
      <li>Age</li>
      <li>Weight</li>
      <li>Duration of activity</li>
      <li>Heart rate</li>
      <li>Gender</li>
    </ul>
    <p>Place the dataset in the <code>data/</code> folder. Update paths in the configuration files as needed.</p>
  </section>

  <section id="model">
    <h2>Model</h2>
    <p>The repository implements various machine learning algorithms including:</p>
    <ul>
      <li>Linear Regression</li>
      <li>Random Forest</li>
      <li>Gradient Boosting</li>
    </ul>
    <p>You can switch between models by updating the configuration in <code>model_config.json</code>.</p>
  </section>

  <section id="results">
    <h2>Results</h2>
    <p>The model achieves high accuracy in predicting calorie values with minimal error. See <code>results/</code> for detailed evaluation metrics and performance plots.</p>
  </section>


</body>
</html>
