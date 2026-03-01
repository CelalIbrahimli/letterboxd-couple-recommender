# 🎬 Letterboxd Couple Recommender

An AI-powered system that blends two Letterboxd profiles and recommends movies both users are likely to enjoy.
The project focuses on **compatibility, joint taste discovery, and diversity-aware recommendations**, which better reflects real-world decision-making compared to traditional single-user recommender systems.

---

## 🚀 Live Demo

👉 Hugging Face Space: **[LINK HERE]**

Upload two Letterboxd export ZIP files and explore:

* Compatibility score
* Shared taste analysis
* Joint genre preferences
* Mood-based movie recommendations

---

## 💡 Motivation

Most recommender systems are built for individuals.
However, in real life, people often choose movies **together**: couples, friends, families.

This project introduces a **couple-aware recommender system** that:

* Measures compatibility
* Models joint preferences
* Balances exploration and exploitation
* Encourages diversity in recommendations

---

## 🧠 Key Features

### ✅ Compatibility Modeling

The system evaluates similarity between two users using:

* Jaccard overlap of watched films
* Pearson correlation of ratings
* Mean absolute rating difference

These are combined into a weighted compatibility score.

---

### 🎭 Genre Preference Modeling

Each user’s taste is learned from:

* Highly rated movies
* Genre distributions
* Joint preference blending

---

### 🎯 Mood-Based Recommendation

Users can select moods such as:

* Romantic
* Fun
* Dark
* Epic

The system dynamically reweights genre preferences.

---

### 🔍 Exploration vs Exploitation

To avoid repetitive mainstream recommendations:

* Popularity-aware scoring
* Novelty bonus for less obvious films

---

### 🌍 Diversity-Aware Ranking

We use **Maximal Marginal Relevance (MMR)** to ensure:

* Genre diversity
* Temporal diversity
* Reduced redundancy

---

### 🎬 IMDb Integration

The model uses real-world movie metadata:

* Genres
* Ratings
* Vote counts
* Runtime
* Release year

This allows higher-quality and more robust recommendations.

---

## 🧪 Methodology

The pipeline includes:

1. Data ingestion from Letterboxd export files
2. IMDb dataset matching and enrichment
3. User profiling
4. Joint preference modeling
5. Ranking optimization
6. Diversity-aware recommendation
7. Mood-based personalization

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Recommender systems
* Ranking algorithms
* Gradio
* Hugging Face Spaces
* IMDb dataset

---

## 📊 Why this project matters

This project demonstrates:

* Real-world recommender system design
* Personalization at the group level
* Product thinking
* Ranking and diversity optimization
* Scalable data pipelines
* Deployment and MLOps mindset

It goes beyond typical ML projects by combining:

* User behavior
* Metadata
* Business logic
* User experience

---

## 🔮 Future Work

Planned upgrades include:

* Semantic NLP embeddings from reviews
* SBERT-based similarity
* Deep learning ranking models
* Collaborative filtering
* Cold-start solutions
* Personality-aware recommendation

---

## 🤝 Contributions

Feel free to fork, experiment, and extend the system.

---

## 📬 Contact

If you find this interesting, feel free to connect with me on LinkedIn.

---

⭐ If you like this project, consider starring the repository!
