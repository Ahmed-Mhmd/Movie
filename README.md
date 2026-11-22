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
2. Get a free TMDB API key at https://www.themoviedb.org/settings/api
3. Copy `lib/core/utils/api_keys.example.dart` to `lib/core/utils/api_keys.dart` and paste your key in it. That file is gitignored, so your key stays on your machine and never gets committed.
4. Install dependencies:
   ```
   flutter pub get
   ```
5. Run the app:
   ```
   flutter run
   ```
