# Movie

A Flutter app for browsing movies, powered by the [TMDB API](https://www.themoviedb.org/).

## Features

- **Home** — browse popular, upcoming, and top-rated movies
- **Search** — find any movie by title
- **Details** — overview, rating, genres, and similar movies
- **Watch list** — save movies locally (Hive) to watch later

## Tech stack

- Flutter & Dart
- BLoC / Cubit for state management
- get_it + injectable for dependency injection
- Hive for local storage
- Clean architecture (data / domain / presentation per feature)

## Getting started

1. Install Flutter (Dart SDK ^3.11.0)
2. Clone the repo and install dependencies:
   ```
   flutter pub get
   ```
3. Run the app:
   ```
   flutter run
   ```
