Project Overview

📊 Developed an ML-based solution to predict crime hotspots using U.S. crime datasets (2020–2024).

🧠 Applied supervised learning and geospatial analysis to identify patterns in crime occurrences across time and locations.

🚔 Helps law enforcement agencies and city planners anticipate high-risk areas and allocate resources proactively.

🛠 Tech Stack
Component	Tools & Libraries
Data Processing	Pandas, NumPy, Scikit-Learn
ML Algorithms	Logistic Regression, Random Forest, KNN, XGBoost
Visualization	Matplotlib, Seaborn, Folium
Feature Engineering	Geospatial clustering, temporal encoding (sin/cos), scaling
🧠 Key Methodologies

Cleaned and preprocessed historical crime data (2020–2024) to handle duplicates, missing values, and outliers.

Engineered temporal features (e.g., hour of day, day of week, month) using sinusoidal transformations to preserve cyclic patterns.

Clustered locations into geospatial grids to better model crime patterns spatially.

Trained multiple ML classifiers and tuned hyperparameters for optimal performance.

Evaluated using accuracy, precision, recall, and F1-score to ensure balanced results.

🏆 Results

🌟 Random Forest delivered the highest F1-Score (~84%), outperforming other models in both precision and recall.

Clear temporal and spatial crime patterns were observed — especially night-time & urban clusters.

Visualized hotspots using heatmaps & interactive Folium maps for intuitive insights.
