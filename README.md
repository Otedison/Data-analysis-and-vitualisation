# Data-analysis-and-vitualisation
Data Analysis and Visualization with Pandas & Matplotlib
📌 Objective

This project demonstrates how to:

Load and explore a dataset using pandas.

Perform basic data analysis (summary statistics, grouping, and insights).

Create visualizations with matplotlib (and Seaborn for styling).

The work follows the assignment requirements to showcase data wrangling, analysis, and visualization skills.

🗂️ Project Structure
Ubuntu_Data_Analysis/
│── assignment.ipynb   # Jupyter Notebook (or assignment.py if script)
│── README.md          # Project documentation
│── dataset.csv        # Dataset used (optional, if using a local CSV)
│── images/            # (Optional) Saved charts or screenshots

⚙️ Requirements

Install the following Python libraries before running the notebook/script:

pip install pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone the repository:

git clone https://github.com/<your-username>/Ubuntu_Data_Analysis.git
cd Ubuntu_Data_Analysis


Open the notebook in Jupyter:

jupyter notebook assignment.ipynb


Or run the script directly:

python assignment.py

📊 Tasks Completed
🔹 Task 1: Load and Explore Dataset

Loaded dataset (Iris dataset via sklearn or CSV file).

Displayed first few rows with .head().

Checked dataset info, missing values, and cleaned data.

🔹 Task 2: Basic Data Analysis

Computed summary statistics with .describe().

Grouped data by species and calculated mean values.

Observed patterns in sepal/petal measurements across species.

🔹 Task 3: Data Visualization

Created 4 different types of plots:

Line Chart – Petal length over index.

Bar Chart – Average petal length per species.

Histogram – Distribution of sepal length.

Scatter Plot – Relationship between sepal length and petal length.

📈 Example Visualizations

(Include screenshots or save plots here if possible)

✅ Findings & Observations

Setosa flowers tend to have smaller petal lengths compared to Virginica and Versicolor.

Clear separation exists in scatter plots, suggesting petal/sepal measurements are good predictors for classification.

Distribution histograms show normal-like spread for some features.

🌍 Ubuntu Principles Applied

Community: Using open datasets accessible to all.

Respect: Handling errors (e.g., missing data, file errors) gracefully.

Sharing: Organizing results and visualizations for reuse.

Practicality: Building a simple, real-world data analysis tool.
