# 📚 Semantic Book Recommender

## 📌 Description du projet
Semantic Book Recommender est une application interactive développée avec Gradio qui permet de recommander des livres à partir d’une requête en langage naturel.
Le projet illustre l’utilisation des LLMs (Large Language Models) et du semantic search appliqués à un cas concret, tout en mettant l’accent sur :

la recherche sémantique via embeddings et base vectorielle,

la classification zero-shot pour distinguer fiction / non-fiction,

l’analyse émotionnelle pour filtrer les recommandations par tonalité,

la simplicité d’utilisation via une interface web.

## ⚙️ Fonctionnalités principales

🔎 Recherche sémantique : retrouver les livres les plus proches d’une description utilisateur (via OpenAI embeddings + ChromaDB).

🏷️ Classification zero-shot : catégoriser automatiquement les livres en Fiction ou Non-Fiction.

🎭 Analyse émotionnelle : associer un score émotionnel (joie, tristesse, peur, colère, surprise, neutralité) aux descriptions.

🖼️ Interface Gradio : saisie d’une requête, choix d’une catégorie et d’un ton émotionnel, affichage des recommandations avec couvertures et résumés.

💾 Gestion des dépendances : requirements.txt fourni pour installer facilement l’environnement.

## 🛠️ Technologies utilisées

- Python 3.11

- LangChain
 (pipeline LLM + text splitters)

- Chroma
 (vector database)

- OpenAI Embeddings
 (représentation sémantique)

- Transformers
 (zero-shot classification & NLP)

- PyTorch
 (backend Transformers)

Gradio
 (interface web)

pandas / numpy (traitement des données)

## 🎯 Objectif pédagogique

Ce projet est conçu à des fins éducatives et démonstratives.
Il illustre les concepts de recherche sémantique, classification zero-shot et analyse des émotions appliqués à la recommandation de contenus.
