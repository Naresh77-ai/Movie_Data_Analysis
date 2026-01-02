🎬 Project Overview

This SQL analytics project analyzes RSVP Movies’ past 3 years of movie data to help the production company plan a global movie release (2022). Using SQL, I explored multiple tables to extract insights on movie performance, genres, ratings, contributors (directors/actors), and production trends, and then converted those insights into data-driven recommendations for the upcoming project.

🎯 Problem Statement

RSVP Movies wants to expand from primarily Indian releases to a global audience, and needs to make key production decisions backed by data. The objective is to use SQL-based analysis on historical movie datasets to answer business questions (across multiple segments of analysis) and provide recommendations such as:

- what types of movies perform best (genre, ratings, runtime patterns)

- which contributors (actors/directors) are associated with strong outcomes

- what trends from past releases can guide the strategy for a successful global launch

🗂️ Dataset Overview

The analysis is performed on a relational movie database consisting of 6 interconnected tables, covering movie details, ratings, genres, and people involved (cast/crew):

- movie: Core movie metadata — title, year, release date, duration, country, languages, production company, worldwide gross income.

- ratings: Movie performance signals — average rating, median rating, total votes (linked via movie_id).

- genre: Genre tags for each movie (many-to-one / many-to-many style mapping via movie_id).

- names: Master table of people — name, height, date of birth, known-for movies.

- director_mapping: Links movies to directors using movie_id ↔ name_id.

- role_mapping: Links movies to cast/crew roles using movie_id ↔ name_id along with a category (e.g., actor/actress/supporting, etc.).

director_mapping: Links movies to directors using movie_id ↔ name_id.

role_mapping: Links movies to cast/crew roles using movie_id ↔ name_id along with a category (e.g., actor/actress/supporting, etc.).
