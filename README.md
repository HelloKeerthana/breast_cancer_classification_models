<h1>Machine Learning Models for Breast Cancer Classification</h1>

<h2>Dataset: Breast Cancer Wisconsin (Diagnostic) - Kaggle</h2>
<p>This dataset contains features computed from digitized images of breast masses, with the goal of predicting whether a tumor is malignant (M) or benign (B).</p>

<h2>Models Used</h2>

<h3>1. Logistic Regression</h3>
<p>A statistical model that estimates the probability of a binary outcome (malignant vs. benign) using a sigmoid function.</p>

<h3>2. Naive Bayes</h3>
<p>A probabilistic classifier based on Bayes' Theorem, assuming independence between features.</p>

<h3>3. Support Vector Machine (SVM)</h3>
<p>A model that finds the optimal hyperplane for separating the two classes with maximum margin.</p>

<h3>4. k-Nearest Neighbors (k-NN)</h3>
<p>A non-parametric algorithm that classifies a point based on the majority label of its nearest neighbors.</p>

<h3>5. Random Forest</h3>
<p>An ensemble method that builds multiple decision trees and averages their predictions for higher accuracy.</p>

<h2>Performance Metrics</h2>
<p>Each model was evaluated based on accuracy, precision, recall, and F1-score. Standard scaling and MinMax scaling were tested for optimal results.</p>

<h2>Visualization</h2>
<ul>
    <li>Bar charts were used to compare model accuracies.</li>
    <li>Broken Y-axis was implemented to highlight small accuracy differences.</li>
</ul>

<h2>Conclusion</h2>
<p>Among the models, logistic regression and random forest performed best, achieving over 95% accuracy. Feature scaling significantly impacted performance.</p>
