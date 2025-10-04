# 🎬 FilminGo – Movie Recommendation System  

A **movie recommendation system** built with **Flask** that combines **collaborative filtering** and **NLP-based sentiment analysis** to provide personalized film suggestions.  
The project includes both the **backend logic** (Flask, machine learning models) and a **web interface** (HTML/CSS/JS).  

---

## 📌 Description  
FilminGo est une application de recommandation de films basée sur l’**apprentissage automatique** et le **traitement du langage naturel**.  
Elle utilise principalement le **Content-Based Filtering** (filtrage par contenu) enrichi par l’analyse des sentiments pour fournir des recommandations personnalisées aux utilisateurs.  

L’objectif est d’aider les utilisateurs à découvrir des films correspondant à leurs goûts tout en offrant une expérience fluide et interactive.  

---

## 🚀 Fonctionnalités principales  
- 🔎 **Recherche intelligente** avec auto-complétion des titres.  
- 🎥 **Recommandations personnalisées** basées sur le contenu des films.  
- 😊 **Analyse des sentiments** des critiques utilisateurs (positif, neutre, négatif).  
- 👨‍🎤 **Informations détaillées** sur les acteurs, réalisateurs et synopsis.  
- 🔄 **Boucle de recommandations** permettant de découvrir de nouveaux films en continu.  

---
## ⚙️ Pile technologique  

- **Langage de programmation** : Python  
- **Framework** : Flask  
- **Apprentissage automatique** : scikit-learn, pickle (modèles sauvegardés)  
- **Manipulation des données** : Pandas, NumPy  
- **Frontend** : HTML, CSS, JavaScript  
- **Notebooks** : Jupyter (pour le prétraitement, le filtrage collaboratif, l’analyse des sentiments et la visualisation)  


---
## 🗂️ Jeux de données utilisés  
- **IMDB 5000 Movie Dataset** (Kaggle)  
- **The Movies Dataset** (Kaggle)  
- **TMDB API** pour enrichir les métadonnées  
- **Listes annuelles de films (2018-2024)** via Wikipédia  

Les données incluent : titres, genres, acteurs, réalisateurs, notes, votes, durée, etc.
1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset)  
2. [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)  
3. [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data?select=tmdb_5000_movies.csv)  
4. [List of American Films of 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)  
5. [List of American Films of 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)  
6. [List of American Films of 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)  
7. [List of American Films of 2021](https://en.wikipedia.org/wiki/List_of_American_films_of_2021)  
8. [List of American Films of 2022](https://en.wikipedia.org/wiki/List_of_American_films_of_2022)  
9. [List of American Films of 2023](https://en.wikipedia.org/wiki/List_of_American_films_of_2023)  
10. [List of American Films of 2024](https://en.wikipedia.org/wiki/List_of_American_films_of_2024)

---

## 🧠 Modèles de Machine Learning  
- **Filtrage collaboratif** (testé mais moins performant dans notre cas)  
- ✅ **Content-Based Filtering** (modèle final choisi)  
  - Extraction de caractéristiques avec **TF-IDF**  
  - Calcul de similarité cosinus entre films  
  - Fonction de recommandation retournant les films les plus proches  
- **Analyse des sentiments** sur les reviews avec **Naïve Bayes Multinomial** (accuracy ~98%)  

---

## 📷 Aperçu de l’application  
- 🏠 Page d’accueil avec recherche et suggestions.  
- 🎬 Page de similarité : recommandations basées sur un film choisi.  
- ⭐ Page de détails : affichage du casting, des critiques et films similaires.  


**Home Page of the Application**  
![Home Page](static/screenshots/Home%20Page.png)

**Movie Suggestions (Autocomplete)**  
![Movie Suggestions](static/screenshots/Movie%20Suggestions.png)

**Description of the Searched Movie**  
![Movie Description](static/screenshots/Movie%20Description.png)

**Actors of the Movie**  
![Actors](static/screenshots/Actors.png)

**Actor Information**  
![Actor Info](static/screenshots/Actor%20Info.png)

**User Reviews Analysis**  
![Reviews Analysis](static/screenshots/Reviews%20Analysis.png)

**Recommendation Result**  
![Recommendation Result](static/screenshots/Recommendation%20Result.png)

---
## Contributors
- [Bnyiche Mouna](https://github.com/itsmawna) 
- [Ahnin Chaimaa](https://github.com/chaimaa-101) 
- [Eddaoudy Aya](https://github.com/EddaoudyAya) 
- [El Alami Nihad](https://github.com/nihadel7) 

---
## 🎉 Amusez-vous bien !

Amusez-vous en testant le projet !  
N’hésitez pas à me contacter si vous avez des questions, des suggestions ou si vous voulez simplement discuter du projet.  


