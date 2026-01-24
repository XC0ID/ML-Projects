📱🔗 The Vicious Cycle: Decoding Social Media Addiction 🧠🚫

From infinite scrolls to data-driven goals. Unraveling the patterns of digital dependency among students.

🧐 The Mission
Social media is designed to keep us hooked, but what actually drives the addiction? Is it the hours spent? The sleep lost? Or the mental health toll?

This project isn't just about code; it's an investigation. We are diving deep into student data to analyze the "Vicious Cycle of Social Media Addiction"—understanding the triggers, visualizing the conflicts, and building machine learning models to predict the addiction score.

📂 The Evidence (Dataset)
We are working with the Students Social Media Addiction.csv file. The key suspects (features) in our investigation include:

⏳ Avg Daily Usage Hours: The time sunk into the screen.

🛌 Sleep Hours Per Night: The rest sacrificed for the scroll.

🧠 Mental Health Score: The psychological impact.

⚔️ Conflicts Over Social Media: The real-world friction.

📊 Addicted Score: The target variable we are trying to predict.

🛠️ The Detective's Toolkit (Tech Stack)
We are armed with the heavy hitters of the Python data science ecosystem:

🐍 Python: The brain of the operation.

🐼 Pandas & NumPy: For wrestling raw data into submission.

🎨 Seaborn & Matplotlib: To visualize the invisible links (Heatmaps & Distributions).

🤖 Scikit-Learn: The predictive powerhouse.

⚙️ The Pipeline (Methodology)
1. 🧹 Data Cleaning & Preprocessing
Raw data is messy. We convert object types to numerics and handle errors to ensure our models get a clean diet of data.

2. 🔍 Exploratory Data Analysis (EDA)
We don't guess; we look.

Correlation Heatmaps: Visualizing how Sleep battles Usage and how Mental Health ties into Addiction.

3. ⚔️ The Model Battle Royale
We aren't just trying one algorithm; we are throwing them all into the arena to see which one predicts addiction best. Our Pipeline includes:

The Linear Legion: LinearRegression, Ridge, Lasso, ElasticNet, BayesianRidge.
The Tree Titans: DecisionTree, RandomForest, ExtraTrees, GradientBoosting.
The Support Vector Scout: SVR.
The Neighbor: KNeighborsRegressor.
The Brain: MLPRegressor (Neural Network).

📈 Results

Model performance is evaluated using appropriate metrics such as:

*R² Score
*Mean Squared Error (MSE)
*Accuracy (if classification)
