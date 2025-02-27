# 📌 Projet : Chatbot IA pour l'Annotation Automatique et l'Analyse de Textes en NLP

## **1️⃣ Description du Projet**
L'objectif de ce projet est de développer un chatbot intelligent capable d'annoter automatiquement des textes en utilisant un **Large Language Model (LLM)**. Le chatbot pourra également répondre à des questions sur le texte et fournir des résumés.

Ce projet couvre **toutes les notions clés des LLM** :
- **Prétraitement des données NLP** (Nettoyage, Tokenization)
- **Utilisation d’un modèle pré-entraîné** (GPT, BERT, LLaMA…)
- **Fine-tuning sur un dataset personnalisé**
- **Optimisation des prompts (Prompt Engineering)**
- **Vectorisation et recherche sémantique (Embedding, Faiss, ChromaDB)**
- **Déploiement sous forme d’API et d’interface Web (Streamlit, FastAPI, Docker, Kubernetes)**

---

## **2️⃣ Objectifs du Projet**
✅ Créer un **chatbot basé sur un LLM** pour l'annotation NLP.
✅ Fine-tuner un modèle existant sur un dataset spécifique (ex. CLAWS C8).
✅ Intégrer un système de **recherche sémantique** avec des embeddings.
✅ Déployer une **API FastAPI** et une interface Web avec **Streamlit**.
✅ Containeriser et déployer sur **Oracle Kubernetes Engine (OKE)**.

---

## **3️⃣ Technologies Utilisées**
- **Langages** : Python
- **Modèles** : GPT, BERT, LLaMA, Mistral
- **NLP** : Hugging Face, spaCy, NLTK, UDPipe
- **Vectorisation** : Sentence Transformers, Faiss, ChromaDB
- **Développement Web** : FastAPI, Streamlit
- **MLOps & Déploiement** : Docker, Kubernetes, CI/CD (GitHub Actions)

---

## **4️⃣ Plan de Travail**

### **🔹 Étape 1 : Collecte et Prétraitement des Données**
✅ Télécharger le **Brown Corpus** et l'annoter avec **UDPipe**
✅ Appliquer des techniques de **tokenization, lemmatisation, suppression du bruit**

### **🔹 Étape 2 : Utilisation d’un Modèle Pré-entraîné**
✅ Charger un modèle Hugging Face comme `bert-large-cased-finetuned-conll03`
✅ Tester son fonctionnement sur un texte brut

### **🔹 Étape 3 : Fine-tuning sur un Dataset Personnalisé**
✅ Utiliser **LoRA (Low-Rank Adaptation)** pour un fine-tuning efficace
✅ Adapter le modèle au **tagset CLAWS C8**

### **🔹 Étape 4 : Recherche Sémantique avec Embeddings**
✅ Encoder les textes avec `all-MiniLM-L6-v2`
✅ Stocker et rechercher des vecteurs avec **Faiss ou ChromaDB**

### **🔹 Étape 5 : Déploiement API et Interface Web**
✅ Créer une **API FastAPI** pour interagir avec le modèle
✅ Développer une **interface Streamlit** pour une utilisation intuitive

### **🔹 Étape 6 : Containerisation et Déploiement**
✅ Dockeriser l’application avec un `Dockerfile`
✅ Déployer sur **Oracle Kubernetes Engine (OKE)**
✅ Mettre en place un pipeline CI/CD avec **GitHub Actions**

---

## **5️⃣ Résultats Attendus**
🔹 Un **chatbot NLP avancé** capable d’annoter des textes avec un LLM.
🔹 Un **modèle fine-tuné** sur un dataset spécialisé.
🔹 Une **API et interface Web** accessible pour interagir avec le modèle.
🔹 Un **système scalable** utilisant **bases vectorielles et Kubernetes**.

---
