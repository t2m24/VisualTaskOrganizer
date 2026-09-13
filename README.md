# Visual Task Organizer

Semester project for the Mobile Application Development course (2026).

An Android application for task and project management built around the Kanban methodology (Trello style). It allows users to create custom boards, manage columns, and move tasks using Drag & Drop gestures.

## Features
* Creation and management of boards, columns, and tasks
* Drag & Drop task movement between columns
* Task attributes (descriptions, deadlines, priority, color tags)
* Local data persistence (offline support)

## Architecture & Tech Stack
* **Language:** Kotlin
* **UI Framework:** Jetpack Compose
* **Architecture:** MVVM (Model-View-ViewModel) with Repository Pattern
* **Database:** Room (SQLite) with Kotlin Flows
* **Navigation:** Jetpack Navigation Component

## Requirements
* Android Studio
* Android SDK (compileSdk 36)
* Device or Emulator running Android 15 (API 35) or higher

---
Note: Academic project focused on native Android development using Kotlin and Jetpack Compose.
