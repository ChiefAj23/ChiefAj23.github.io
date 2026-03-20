---
layout: page
title: Movie Recommender System
description: Content-based movie recommendation web application with poster retrieval and interactive Streamlit interface.
img: assets/img/movie-recommender-arch.png
importance: 2
category: Research
---

<p align="justify"> In this project, we present a web-based <b>Movie Recommender System</b> that helps users quickly discover similar movies based on a selected favorite film. The system is designed to reduce decision fatigue and simplify content discovery by generating a curated list of five related movies through a content-based recommendation pipeline. Built with <b>Python</b> and <b>Streamlit</b>, the application combines an interactive user interface with a lightweight backend recommendation engine and external poster retrieval to create a visually engaging movie exploration experience. </p>

<p align="justify"> The recommendation engine is developed using the <b>TMDB 5000 Movie Dataset</b> and a precomputed similarity model stored in a serialized <b>model.pkl</b> file. Once a user selects a movie from the dropdown interface, the backend loads the associated metadata, computes similarity scores using content-based filtering, and retrieves the top five most similar films. To improve presentation and usability, the system also integrates with the <b>TMDB REST API</b> to fetch high-quality movie posters dynamically, with fallback handling for missing poster data. This architecture enables fast inference while keeping the application simple and easy to deploy locally. </p>

<p align="justify"> A key strength of this project is its clear end-to-end design, where the frontend, recommendation logic, and external API integration work together seamlessly. The Streamlit interface provides an intuitive workflow for selecting movies and viewing recommendations, while the backend demonstrates how content similarity models can be operationalized into an accessible user-facing tool. The project also lays the groundwork for future enhancements such as collaborative filtering, genre-based filtering, rating-aware recommendations, user profiles, and trailer previews. Overall, it demonstrates a practical and visually appealing application of machine learning for personalized entertainment discovery. </p>

Implementation of entire project can be found here: <a href="https://github.com/ChiefAj23/Movie-Recommender-System"> Code </a>