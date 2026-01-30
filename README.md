<h1>Sales Transaction Analysis Using PCA, UMAP & K-Means Clustering</h1>

<h3>Customer Segmentation and Pattern Discovery Using Unsupervised Machine Learning</h3>

<hr>

<h2> Project Overview</h2>
<p>
This project applies <strong>unsupervised machine learning</strong> and 
<strong>dimensionality reduction techniques</strong> to analyse sales transaction data
and uncover hidden customer behaviour patterns.
</p>

<p>
Using <strong>Principal Component Analysis (PCA)</strong>, 
<strong>Uniform Manifold Approximation and Projection (UMAP)</strong>,
and <strong>K-Means clustering</strong>, the study identifies distinct customer segments
based on purchasing behaviour, transaction value, and product interaction.
</p>

<p>
The project demonstrates how high-dimensional transactional data can be transformed
into interpretable structures that support <strong>data-driven marketing</strong>,
<strong>customer targeting</strong>, and <strong>strategic business decision-making</strong>.
</p>

<hr>

<h2> Aim and Objectives</h2>

<h3>Aim</h3>
<p>
To identify meaningful customer segments within sales transaction data using
dimensionality reduction and clustering techniques.
</p>

<h3>Objectives</h3>
<ul>
  <li>Clean and preprocess raw sales transaction data</li>
  <li>Standardise numerical features for machine learning</li>
  <li>Reduce dimensionality using PCA and UMAP</li>
  <li>Apply K-Means clustering to identify customer segments</li>
  <li>Visually interpret cluster structures and behaviour patterns</li>
  <li>Evaluate cluster quality and business relevance</li>
</ul>

<hr>

<h2>Dataset Description</h2>
<p>
The dataset contains transactional-level sales data including customer purchasing behaviour,
transaction frequency, monetary value, and product-related attributes.
</p>

<hr>

<h2>Data Preparation & Feature Engineering</h2>
<ul>
  <li>Missing value handling and outlier inspection</li>
  <li>Aggregation of transaction-level data into customer-level features</li>
  <li>Feature scaling using StandardScaler</li>
  <li>Removal of redundant and highly correlated variables</li>
</ul>

<p>
Feature engineering was performed to ensure the dataset was suitable for
distance-based algorithms such as K-Means.
</p>

<hr>

<h2>Methodology</h2>

<h3>1. Principal Component Analysis (PCA)</h3>
<p>
PCA was applied to reduce the dimensionality of the dataset while preserving
maximum variance. The resulting components enabled efficient noise reduction
and improved clustering performance.
</p>

<h3>2. UMAP (Uniform Manifold Approximation and Projection)</h3>
<p>
UMAP was used for non-linear dimensionality reduction, allowing complex
customer behaviour patterns to be visualised in two-dimensional space.
This technique preserves local structure and enhances cluster separation.
</p>

<h3>3. K-Means Clustering</h3>
<p>
K-Means clustering was applied to the reduced feature space to segment customers
into distinct groups. The optimal number of clusters was selected using
the Elbow Method and Silhouette Score.
</p>

<hr>

<p>
PCA and UMAP visualisations demonstrated strong separation between clusters,
confirming the effectiveness of the segmentation approach.
</p>

<p>
These insights can be used to inform targeted marketing strategies,
customer retention initiatives, and personalised recommendations.
</p>

<hr>

<h2>Tools & Technologies</h2>
<ul>
  <li>Python</li>
  <li>Pandas & NumPy</li>
  <li>Scikit-learn</li>
  <li>UMAP-learn</li>
  <li>Matplotlib & Seaborn</li>
</ul>

<hr>

<h2>Project Structure</h2>
<pre>
sales-transaction-analysis/
│
├── data/                 → Sales_Transactions_Dataset_Weekly.csv
├── python scripts/       → sales_transactions_pca_umap_k_means.py
└── README.md
</pre>

<hr>

<h2>How to Run the Project</h2>
<ol>
  <li>Clone the repository</li>
  <li>Install required dependencies:</li>
</ol>

<pre>
pip install pandas numpy scikit-learn umap-learn matplotlib seaborn
</pre>

<ol start="3">
  <li>Run the Python script:</li>
</ol>

<pre>
python sales_transactions_pca_umap_k_means.py
</pre>

<hr>

<h2>Business Applications</h2>
<ul>
  <li>Customer segmentation and profiling</li>
  <li>Targeted marketing campaigns</li>
  <li>Sales strategy optimisation</li>
  <li>Customer lifetime value estimation</li>
</ul>

<hr>

<h2>Future Enhancements</h2>
<ul>
  <li>Integration of temporal purchasing behaviour</li>
  <li>Comparison with DBSCAN or HDBSCAN clustering</li>
  <li>Deployment as an interactive dashboard</li>
  <li>Incorporation of demographic or geographic features</li>
</ul>

<hr>

<h2>Author</h2>
<p>
<strong>Shikha Tyagi</strong><br>
MSc in Business Analytics<br>
</p>
