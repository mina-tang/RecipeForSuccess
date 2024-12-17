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

  <hr>

  <h3>Lead Actor 1</h3>

  <label for="actor-gender-lead-actor1">Gender:</label>
  <select id="actor-gender-lead-actor1" name="actor-gender-lead-actor1">
    <option value="male">Male</option>
    <option value="female">Female</option>
    <option value="other">Other</option>
  </select><br><br>

  <label for="actor-height-lead-actor1">Height (cm):</label>
  <input type="number" id="actor-height-lead-actor1" name="actor-height-lead-actor1" required><br><br>

  <label for="actor-dob-lead-actor1">Date of Birth (YYYY-MM-DD):</label>
  <input type="date" id="actor-dob-lead-actor1" name="actor-dob-lead-actor1" required><br><br>

  <label for="actor-age-at-release-lead-actor1">Age at Release:</label>
  <input type="number" id="actor-age-at-release-lead-actor1" name="actor-age-at-release-lead-actor1" required><br><br>

  <label for="actor-ethnicity-lead-actor1">Ethnicity:</label>
  <select id="actor-ethnicity-lead-actor1" name="actor-ethnicity-lead-actor1" required>
    <option value="asian">Asian</option>
    <option value="black">Black</option>
    <option value="caucasian">Caucasian</option>
    <option value="hispanic">Hispanic</option>
    <option value="other">Other</option>
  </select><br><br>

  <hr>

  <h3>Lead Actor 2</h3>

  <label for="actor-gender-lead-actor2">Gender:</label>
  <select id="actor-gender-lead-actor2" name="actor-gender-lead-actor2">
    <option value="male">Male</option>
    <option value="female">Female</option>
    <option value="other">Other</option>
  </select><br><br>

  <label for="actor-height-lead-actor2">Height (cm):</label>
  <input type="number" id="actor-height-lead-actor2" name="actor-height-lead-actor2" required><br><br>

  <label for="actor-dob-lead-actor2">Date of Birth (YYYY-MM-DD):</label>
  <input type="date" id="actor-dob-lead-actor2" name="actor-dob-lead-actor2" required><br><br>

  <label for="actor-age-at-release-lead-actor2">Age at Release:</label>
  <input type="number" id="actor-age-at-release-lead-actor2" name="actor-age-at-release-lead-actor2" required><br><br>

  <label for="actor-ethnicity-lead-actor2">Ethnicity:</label>
  <select id="actor-ethnicity-lead-actor2" name="actor-ethnicity-lead-actor2" required>
    <option value="asian">Asian</option>
    <option value="black">Black</option>
    <option value="caucasian">Caucasian</option>
    <option value="hispanic">Hispanic</option>
    <option value="other">Other</option>
  </select><br><br>

  <input type="submit" value="Predict">
</form>

<p id="prediction-result"></p>
