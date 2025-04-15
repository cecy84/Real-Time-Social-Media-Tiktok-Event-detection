# 📈 Real-Time Social Media Event Detection (TikTok)

A work-in-progress machine learning project that analyzes TikTok-style social media posts to detect emerging events, viral hashtags, and sentiment shifts in real-time. This project simulates how AI can be used for social listening and event detection in a Kenyan or global context.

---

## 🔍 Project Overview

The goal is to monitor simulated TikTok data streams and extract patterns using Natural Language Processing (NLP) and clustering techniques. The system identifies trending conversations, sentiment patterns, and potential events (e.g., activism spikes, political shifts, public health alerts) using hashtags, time-series analysis, and engagement metrics.

---

## 🧪 Current Capabilities

- ✅ Ingest mock TikTok data (text + timestamp + likes/shares)
- ✅ Clean and tokenize text data
- ✅ Extract and rank hashtags
- ✅ Visualize keyword frequency and engagement trends
- ✅ Clustering text by topic (e.g. KMeans / DBSCAN – in progress)
- ✅ Simulate event tagging (manual + semi-automated)
- ⚙️ [Work in Progress] Sentiment analysis using VADER or BERT
- 📈 [Planned] Real-time trend spike detection
- 📍 [Planned] Regional tagging for geospatial analysis
- 🚨 [Planned] Alert system for emerging trends

---

## 📁 Dataset

- `mock_tiktok_data.csv`: Simulated dataset with posts, timestamps, likes, shares, and hashtags
- `events.csv`: Optional labeled file to mark known events for evaluation
- `main notebook.ipynb`: Core data pipeline and experiment notebook

---

## 🛠 Tools & Stack

- Python · Pandas · NLTK · Matplotlib · Scikit-learn
- Jupyter Notebook
- [Planned] Streamlit dashboard
- [Planned] BERT embeddings for contextual clustering

---

## 🌍 Potential Use Cases

- Detecting activism trends (e.g., #EndFemicideKE)
- Early signals for public health alerts (#MentalHealth)
- Real-time trend intelligence for marketing & policy
- Sentiment-aware dashboards for NGOs or media teams

---

## 🚧 Status

This is an active personal project currently under development. The dataset is mocked using Python generators and `Faker`, and functionality is being expanded weekly.

---

## 📌 Next Steps

- [ ] Implement topic clustering with DBSCAN
- [ ] Integrate sentiment analysis (VADER or BERT)
- [ ] Build Streamlit dashboard prototype
- [ ] Detect trend spikes based on hashtag frequency
- [ ] Tag and evaluate simulated events

---

## 🤝 Contributions

This project is solo-developed as part of my AI portfolio. I'm open to feedback and collaboration — feel free to open issues or reach out!

---

## 📂 Repository

> https://github.com/cecy84/Real-Time-Social-Media-Tiktok-Event-detection

---

## 📣 License

MIT License (feel free to fork, build, and adapt with credit!)

