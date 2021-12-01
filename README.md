# Android Weather App

Introduction
This application is written in Kotlin and uses Clean Architecture based on MVVM and Repository pattern. Android Jetpack is used as an Architecture glue. This application does network HTTP requests via Retrofit, OkHttp and GSON.

This application consist of two screen, the first screen show at the very first time the user is opening the App notifying them that the App requires permissions and the second screen is the actual weather updates which display the current weather and well as the weekly weather forecast.

Libraries Used
[Foundation] - Components for core system capabilities.
[AppCompat] - Degrade gracefully on older versions of Android.
[Android KTX] - Write more concise, idiomatic Kotlin code.
[Architecture] - A collection of libraries that help with robust design, testable, and maintainable code.
[ViewModel] - Store UI-related data that isn't destroyed on app rotations. Easily schedule asynchronous tasks for optimal execution.
[WorkManager] - Manage your Android background jobs.
[Jetpack Compose] - Toolkit for building native UI.
[Material] - Material Components.
Third party
[Kotlin Coroutines] for managing background threads with simplified code and reducing needs for callbacks.
[Hilt] A fast dependency injector.
[Retrofit 2] A configurable REST client.
[OkHttp 3] A type-safe HTTP client.
[GSON] A Json - Object converter using reflection.