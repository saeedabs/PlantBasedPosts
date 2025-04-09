# PlantBasedPosts
This project presents a data science research analyzing discussions around veganism on Reddit. We apply transformer-based BERTopic models (PLMs) for topic modeling, and use both soft and hard variants of the Louvain community detection algorithm to explore thematic structures and clustering patterns in Reddit posts and comments.

# Vegan Reddit Insights

**Exploring the discourse on veganism across Reddit using topic modeling and community detection.**

This project investigates how vegan-related topics are discussed across Reddit subreddits. By combining transformer-based topic modeling (BERTopic) with graph clustering techniques (soft and hard Louvain), we analyze post and comment structures, emotional sentiment, and the roles of users and subreddits in shaping online vegan conversations.

---

## Project Goals

- Collect Reddit posts and comments related to veganism, carnivorism, and general food.
- Clean and preprocess text data for NLP analysis.
- Model topics using BERTopic (with PLMs).
- Detect communities using hard and soft Louvain algorithms.
- Perform sentiment analysis with VADER.
- Visualize relationships between users, posts, and subreddits using 2D and 3D graphs.
- Analyze centrality, engagement, and topic-based user activity.

---

## Tools & Techniques

| Purpose              | Tools Used                         |
|----------------------|------------------------------------|
| Data Collection      | `PRAW` (Python Reddit API Wrapper) |
| NLP & Preprocessing  | `spaCy`, `nltk`, `contractions`    |
| Topic Modeling       | `BERTopic` with transformer models |
| Clustering           | Soft & Hard `Louvain` algorithms   |
| Sentiment Analysis   | `VADER`                            |
| Graph Analysis       | `networkx`, `igraph`, `sknetwork`  |
| Visualization        | `matplotlib`, `plotly`, `pyvis`, `py3Dmol` |

