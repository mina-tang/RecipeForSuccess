---
layout: default
title: Movie Prediction
permalink: /movie-prediction/
---

# Predict Movie Rating and Box Office Revenue

Fill in the details below to predict the rating and box office revenue of the movie.

<form id="movie-form">
  <label for="movie-name">Movie Name:</label>
  <input type="text" id="movie-name" name="movie-name" required><br><br>

  <label for="genre">Genre:</label>
  <select id="genre" name="genre">
    <option value="action">Action</option>
    <option value="comedy">Comedy</option>
    <option value="drama">Drama</option>
    <option value="horror">Horror</option>
    <option value="romance">Romance</option>
  </select><br><br>

  <label for="runtime">Runtime (minutes):</label>
  <input type="number" id="runtime" name="runtime" required><br><br>

  <label for="budget">Budget ($):</label>
  <input type="number" id="budget" name="budget" required><br><br>

  <label for="release-year">Release Year:</label>
  <input type="number" id="release-year" name="release-year" required><br><br>

  <input type="submit" value="Predict">
</form>

<p id="prediction-result"></p>
