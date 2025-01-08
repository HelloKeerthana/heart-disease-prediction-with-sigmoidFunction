<h1>Heart Disease Prediction using Logistic Regression with Sigmoid Function</h1>

<h2>Dataset</h2>
<p>The dataset used is the <strong>Heart Disease dataset</strong> from <strong>sklearn.datasets</strong>, 
  which contains various medical attributes related to heart disease. The features include age, sex, chest pain type,
  blood pressure, cholesterol levels, and others, while the target variable is a binary classification label (0 or 1), 
  indicating whether the patient has heart disease or not.</p>

<h2>Modules Used</h2>
<ul>
    <li><strong>sklearn.datasets</strong>: To load the Heart Disease dataset.</li>
    <li><strong>sklearn.model_selection</strong>: For splitting the dataset into training and testing sets using <code>train_test_split</code>.</li>
    <li><strong>sklearn.preprocessing</strong>: For scaling the feature data using <code>StandardScaler</code>.</li>
    <li><strong>sklearn.linear_model</strong>: To apply <code>LogisticRegression</code> for binary classification using the sigmoid activation function.</li>
    <li><strong>sklearn.metrics</strong>: For evaluating model performance, including the use of accuracy, confusion matrix, and classification reports.</li>
    <li><strong>matplotlib.pyplot</strong>: For visualizing the performance of the model, including plotting confusion matrices and scatter plots comparing predicted vs. true labels.</li>
</ul>

<h2>Process</h2>
<p>The dataset is loaded and split into training and testing sets using <strong>train_test_split</strong>. 
  The features are standardized using <strong>StandardScaler</strong> to improve the performance of the Logistic Regression model. 
  A <strong>Logistic Regression</strong> model is then trained using the sigmoid function, which maps the output to probabilities between 0 and 1. 
  The model is evaluated using accuracy and a confusion matrix to visualize how well it classifies heart disease occurrences.</p>

<h2>Output</h2>
<p>The output includes the accuracy of the Logistic Regression model, as well as the predictions on the test data. 
  A confusion matrix is displayed to visualize the model's performance, and a plot comparing true vs. predicted labels 
is generated to show how well the model identifies heart disease.</p>

<h2>Plot</h2>
<p>The plot displays a scatter plot comparing the true labels of the test set against the predicted labels from the Logistic 
  Regression model using the sigmoid function. This visualizes how closely the model's predictions align with the actual outcomes for heart disease.</p>

<p>The <strong>x-axis</strong> represents the sample index in the test set, while the <strong>y-axis</strong> represents the label values. 
  The true labels are shown using blue circles (o) and the predicted labels are displayed using pink crosses (x), with a slight offset applied to the x-values of the predicted labels to prevent overlap.</p>

<p>The plot provides a visual indication of the model's performance. 
  If the model is performing well, the pink crosses (predicted labels) should align closely with the blue circles (true labels). 
  Large deviations indicate misclassifications or inaccuracies in the predictions.</p>
