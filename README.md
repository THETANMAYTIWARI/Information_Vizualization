## 🎬 Streaming Content Analytics & Recommendation System

Compact dashboard + recommendation engine analyzing content from Netflix, Hulu, Disney+ and Amazon Prime and recommending similar titles using text embeddings and clustering.

### 🧾 Project Summary

This project cleans and merges four OTT datasets (~23k rows total), visualizes platform trends (ratings, countries, genres, yearly additions), generates semantic text embeddings from descriptions, and builds a content-based recommendation engine using K-Means clustering and FastText (with TF-IDF as an alternative). Outputs are presented as charts and dashboard screenshots for exploration.

### 🧭 Methodology (high level)

* Load & clean: normalize dates, fill missing values, cast types, standardize text.

* Feature engineering: add platform column, merge datasets, preprocess descriptions for NLP.

* Text representation: train FastText embeddings on descriptions (alternatively TF-IDF).

* Clustering & recommendations: apply K-Means to embeddings, assign cluster_id, and rank intra-cluster titles by similarity for top-N suggestions.

* Visualization: platform distributions, rating trends, country choropleth, genre analysis, word cloud, and timeline plots.

### 📈 Key Insights & Results

* Netflix and Amazon hold the largest volumes; Disney is movie-heavy.

* Content additions spiked post-2014 (notably Netflix).

* K-Means + FastText produces meaningful cross-platform recommendations; sample queries return coherent top-5 similar titles.

* Visual analyses reveal platform specializations by country, genre, and audience ratings.

### 🧩 Future Enhancements

* Hybrid recommender combining collaborative filtering with content signals.

* Replace FastText with transformer sentence embeddings for improved semantics.

* Add sentiment analysis on reviews/descriptions and time-aware recommendations.

* Build an interactive web app (Streamlit / Dash / Shiny) and expose an API (ONNX / TorchScript).

### 📷 Visuals Created Using Tableau

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/27dd9d50-0249-434d-82c8-1db31cf3838a" width="450"/></td>
    <td><img src="https://github.com/user-attachments/assets/a4bc36b1-f674-4b70-a141-730c281aaef7" width="450"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ed0e7caf-f21f-4f5e-846d-dd11821bc880" width="450"/></td>
    <td><img src="https://github.com/user-attachments/assets/13fb07e7-bf46-4269-ab82-fdceb0f54697" width="450"/></td>
  </tr>
</table>


## Dashboard 
<img width="1888" height="856" alt="image" src="https://github.com/user-attachments/assets/8fa73b4d-ffff-4bad-a4aa-d367a18e955b" />
<img width="1914" height="860" alt="image" src="https://github.com/user-attachments/assets/a5868845-6ded-4d73-8ec2-8bb266c60667" />
<img width="1919" height="858" alt="image" src="https://github.com/user-attachments/assets/e799e77d-5b78-48f2-8a1d-a5471446066b" />
<img width="1914" height="852" alt="image" src="https://github.com/user-attachments/assets/caadfdf4-4e6d-4a5a-9b2b-dc0fc4d6aa83" />




