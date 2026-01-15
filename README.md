# 📰 Fake News Detector  
### Analyse NLP, Machine Learning & Deep Learning pour la détection de fausses informations

---

##  Description du projet

Ce projet vise à concevoir un **système intelligent de détection de fake news** basé sur des techniques avancées de **Traitement du Langage Naturel (NLP)**, de **Machine Learning** et de **Deep Learning (BERT)**.

L’objectif est de classifier automatiquement un article de presse comme :
- ✅ **Vrai**
- ❌ **Faux**

Le projet couvre **l’ensemble du cycle Data Science** :
- Analyse exploratoire
- Prétraitement linguistique
- Feature engineering
- Modélisation classique & deep learning
- Explicabilité (SHAP / LIME)
- Déploiement avec Streamlit

---

##  Structure du projet

```text
fake-news-detector/
│
├── data/
│   ├── raw/                # Données brutes (True.csv, Fake.csv)
│   └── processed/          # Données nettoyées
│
├── notebooks/
│   └── exploration.ipynb   # Analyse exploratoire et modélisation
│
├── src/
│   ├── preprocessing/      # Nettoyage et prétraitement du texte
│   ├── training/           # Entraînement des modèles
│   └── inference/          # Prédiction / inférence
│
├── models/
│   ├── fake_news_pipeline.pkl
│   ├── random_forest_model.pkl
│   ├── tfidf_vectorizer.pkl
│   └── feature_names.pkl
│
├── app.py                  # Application Streamlit
├── requirements.txt        # Dépendances Python
├── .gitignore
└── README.md

Marwane HOUNGNON
Chercheur en Intelligence Artificielle
Spécialisé en NLP, Machine Learning et Smart Systems

Data Science & IA
Afrique / Maroc
