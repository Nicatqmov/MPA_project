# Mobile Application Development Project

## Priject Team
- **[Nijat Gasimov]** 
- **[Elcan Khalilzade]**

---

## Our MPA Project

Our project is an Android application designed for discovering music, creating playlists, and managing favorite tracks. The application integrates the Deezer API to provide seamless music streaming and browsing functionality. It adheres to modern Android development practices and implements a robust MVVM architecture with Clean Architecture principles.

---

## Project Screens

The application includes the following key screens:

| Screen Name          | Description                             
|----------------------|-----------------------------------------
| **Home Screen**       | Lists tracks     
| **Library Screen**    | Shows playlists about a specific artist and their albums 
| **Search Screen**     | Displays search results   

---

## Project Tech Stack Overview

The application leverages modern tools and libraries to provide a seamless user experience:

### Languages and Frameworks
- **Kotlin**: For its concise syntax and seamless integration with Android.
- **Kotlin Coroutines**: For structured concurrency and asynchronous operations.
- **Kotlin Flow**: For reactive data stream management.

### Architecture Components
- **ViewModel**: Lifecycle-aware UI data holder.
- **LiveData**: Observables for UI components.
- **Navigation Component**: Simplifies app navigation and deep linking.

### Networking
- **Retrofit**: Type-safe HTTP client for API communication.
- **Glide**: Efficient image loading and caching library.

### Dependency Injection
- **Hilt**: Simplifies dependency management and promotes testable code.

### Domain Design
- **Repository Pattern**: Provides a unified API for accessing data.
- **UseCases**: Encapsulates business logic and ensures modularity.

---

## Architecture Overview

The application is built using **MVVM (Model-View-ViewModel)** with Clean Architecture principles. This ensures separation of concerns, testability, and scalability.

### Modules and Layers

1. **App Module**: Handles UI interactions via Activities and Fragments.
2. **Domain Module**: Encapsulates business logic, processing data from the data layer.
3. **Data Module**: Manages external data sources like APIs or local databases.
4. **Common Module**: Contains reusable utilities like constants and helper functions.

### Diagram: Clean Architecture Overview  asdsadsadsad
## API Integration

The application integrates with the Deezer API, using the following endpoints:

| **Endpoint**                | **Purpose**                              |**Example**                                   |
|-----------------------------|------------------------------------------|-----------------------------------------------|
| `GET /artist/{id}/albums`   | Fetches albums by artist ID              | `https://api.deezer.com/artist/27/albums`     |
| `GET /album/{id}/tracks`    | Fetches tracks by album ID               | `https://api.deezer.com/album/302127/tracks`  |
| `GET /search?q={query}`     | Searches for tracks                      | `https://api.deezer.com/search?q=eminem`      |

---

## What can be added?

3. **Advanced Playback Options**: Controls like pause, resume, and seek are not yet implemented.
1. **Quiz Functionality**: The quiz feature is currently unimplemented.
2. **Offline Data Remain**: Offline editing and playback of playlists remain a challenge.

---


## Contributions in our team

### [Nijat Gasimov]
- Implemented the API layer using Retrofit.
- Designed and implemented the Albums screen UI.
- Developed the navigation structure for the app.

### [Elcan Khalilzade]
- Created data models for Deezer API integration.
- Optimized app performance using Kotlin Coroutines.
