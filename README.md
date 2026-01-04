# 🛡️PatrolIQ — Smart Safety Analytics Platform
Loads patrol datasets, performs PCA/UMAP/t-SNE, applies KMeans, DBSCAN, and Hierarchical clustering, and visualizes crime patterns interactively using Streamlit.
Overview
PatrolIQ is an interactive crime-analytics dashboard built with Streamlit, designed to analyze large-scale patrol datasets and uncover crime patterns using modern clustering and dimensionality-reduction techniques.

The app integrates:

📊 PCA, UMAP, t-SNE for dimensionality reduction

🤖 KMeans, DBSCAN, Agglomerative (Hierarchical) clustering

🌍 Geo-visualization using Folium & PyDeck

📝 MLflow for tracking experiments and models

⚡ Streamlit caching for performance

📡 Ability to load dataset from cloud storage (required for large files)

✨ Features

🔍 Data Exploration
Dataset overview and summary statistics

Top crime categories

Sampling utilities for large datasets

🗺️ Geospatial Analysis
Heatmaps with Folium

Cluster convex hulls

3D hexagonal density visualization with PyDeck

🧠 Clustering Algorithms
KMeans

DBSCAN

Hierarchical (Agglomerative)

Metrics: silhouette score, Davies–Bouldin index

📉 Dimensionality Reduction
PCA (2D, 3D)

UMAP (2D)

t-SNE

📁 MLflow Integration
Track clustering runs

Compare metrics

View best models

Register models in Model Registry

🏗️ Project Structure
PatrolIQ/ │── app.py
│── sample_df.csv
│── requirements.txt │── README.md |-- patroling.py

🧪 Running Locally
Sreamlit App (http://localhost:8501/)
MLFlow Run (http://127.0.0.1:5008/#/)
Added Screenshot
<img width="1883" height="829" alt="Screenshot 2026-01-04 163934" src="https://github.com/user-attachments/assets/c02db691-7952-4716-962e-9f2109ee2fce" />
## Streamlit
<img width="1919" height="1079" alt="Screenshot 2026-01-04 164210" src="https://github.com/user-attachments/assets/b4d55f57-8b30-4b3f-bc3e-922ddbe46a3f" />
<img width="1919" height="1073" alt="Screenshot 2026-01-04 164259" src="https://github.com/user-attachments/assets/7b459681-b904-4272-a43c-2c64e9a993f8" />
<img width="1901" height="1079" alt="Screenshot 2026-01-04 164332" src="https://github.com/user-attachments/assets/684adaf2-b4c0-4de7-98bb-4e22afb166e2" />
<img width="1916" height="1079" alt="Screenshot 2026-01-04 164438" src="https://github.com/user-attachments/assets/730d165b-0bb5-433f-bb2d-f21dc704e908" />
<img width="1919" height="1065" alt="Screenshot 2026-01-04 165148" src="https://github.com/user-attachments/assets/354bb353-9496-4a09-9180-b1cc49851a21" />
<img width="1919" height="1079" alt="Screenshot 2026-01-04 165208" src="https://github.com/user-attachments/assets/a8648ae1-7085-4d8e-b1c7-b8824cab65a8" />






