<h1>Machine Learning Models for Breast Cancer Classification</h1>

<h2>Overview</h2>
<p>The Breast Cancer Wisconsin (Diagnostic) dataset is a widely used dataset for binary classification tasks in machine learning. 
It contains features extracted from digitized images of breast tumor cell nuclei, which help
    predict whether a tumor is malignant (cancerous) or benign (non-cancerous).</p>

<h2>Dataset Details</h2>
<ul>
    <li><strong>Source:</strong> UCI Machine Learning Repository (hosted on Kaggle)</li>
    <li><strong>Samples:</strong> 569</li>
    <li><strong>Features:</strong> 30 numerical attributes (computed from cell nuclei images)</li>
    <li><strong>Target Variable:</strong> Diagnosis (<code>M</code> for malignant, <code>B</code> for benign)</li>
    <li><strong>Missing Values:</strong> None</li>
</ul>

<h2>Features</h2>
<p>The dataset includes 10 real-valued features for each cell nucleus, computed for three different aspects (mean, standard error, and worst case):</p>
<ul>
    <li>Radius (mean of distances from center to perimeter)</li>
    <li>Texture (variance of gray-scale values)</li>
    <li>Perimeter</li>
    <li>Area</li>
    <li>Smoothness (local variation in radius)</li>
    <li>Compactness</li>
    <li>Concavity</li>
    <li>Concave Points</li>
    <li>Symmetry</li>
    <li>Fractal Dimension</li>
</ul>

<h2>Target Variable</h2>
<ul>
    <li><strong>M (Malignant):</strong> Cancerous tumor (212 cases)</li>
    <li><strong>B (Benign):</strong> Non-cancerous tumor (357 cases)</li>
</ul>

<h2>Usage</h2>
<p>This dataset is commonly used for classification tasks in machine learning and deep learning. 
    Models such as Logistic Regression, SVM, Random Forest, and Neural Networks can be trained to differentiate between malignant and benign tumors.</p>

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
<p>Each model was evaluated based on accuracy.</p>

<h2>Visualization</h2>
<ul>
    <li>Bar charts were used to compare model accuracies.</li>
    <li>Broken Y-axis was implemented to highlight small accuracy differences.</li>
</ul>
