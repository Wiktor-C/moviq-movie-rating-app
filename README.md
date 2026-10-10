# Moviq - movie rating app
Full-stack web application for rating and reviewing movies and TV series, featuring a neural network-based module that predicts user ratings based on their previous ratings and activity.

## Features

* **Movie and TV Series Catalog** - browse and search for movies and TV series, with filtering by genre, streaming platform, country, release year, and rating.
* **Movie and TV Series Details** - view production descriptions, trailers, images, and other related information.
* **Popular Titles and Rankings** - explore popular productions, rankings, upcoming releases, and featured titles.
* **Ratings and Reviews** - rate movies and TV series, write reviews, and browse ratings and reviews submitted by other users.
* **Community Interaction** - comment on reviews and rate reviews written by other users.
* **Personalized Lists and History** - create watchlists and favorite lists, and browse rating and review history.
* **Content Management** - moderator panel for adding, editing, and deleting movies, TV series, seasons, episodes, and information about actors, directors, and other people involved in productions.
* **Personalized Recommendations** - recommend movies and TV series based on individual user preferences.
* **Machine Learning-Based Rating Prediction** - predict user ratings using a neural network based on previous ratings and user activity.

## Technologies

* **Backend:** Java, Spring Boot, Spring Security, Hibernate, JPA
* **Frontend:** React, JavaScript, Vite, Tailwind CSS
* **Database:** PostgreSQL
* **Machine Learning:** Python, TensorFlow, Keras, scikit-learn
* **Testing:** JUnit, Mockito, Postman

## Architecture

The application is divided into three components:

* **Frontend:** A React-based web application that provides the user interface and communicates with the backend through a REST API.
* **Backend:** A Spring Boot application that handles business logic, user authentication and authorization, and database operations. It exposes REST endpoints used by the frontend.
* **Machine Learning Service:** A Python-based service responsible for training a neural network and predicting user ratings based on users' previous ratings and activity.

The backend uses PostgreSQL for data storage, while the machine learning module provides rating predictions used by the application.

## Screenshots

The following screenshots showcase selected features and key parts of the application.

**Login Page**

<img width="1715" alt="auth" src="https://github.com/user-attachments/assets/e07f3e50-efd4-4d6c-b682-827689d923ba" />

<br><br>

**Home Page**

<img width="1715" alt="home_page" src="https://github.com/user-attachments/assets/f3fcf26e-a768-4588-be8f-ad713aa44951" />

<br><br>

**Details Page**

<img width="1715"  alt="details" src="https://github.com/user-attachments/assets/c1b8db81-9d3f-4b0d-8faf-b509f7a63d8e" />

<br><br>

**Catalog Page**

<img width="1715" alt="catalog" src="https://github.com/user-attachments/assets/21962e9d-0900-45d2-9e6a-a81c36c33831" />

<br><br>

**Review Page**

<img width="1715" alt="review" src="https://github.com/user-attachments/assets/bab86c05-8f3d-4dea-86cc-b4564e83d95c" />

<br><br>

**Search Page**

<img width="1715" alt="search" src="https://github.com/user-attachments/assets/1dd9f221-9851-467d-8152-e36445ab7ce8" />

<br><br>

**Profile Page**

<img width="1715" alt="profile" src="https://github.com/user-attachments/assets/3fe53a50-bb79-4e39-8dd9-44c3ea64f7a4" />

## Project Information

This project was developed as part of my master's thesis in Computer Science, specializing in Information Systems.

The source code is not publicly available.
