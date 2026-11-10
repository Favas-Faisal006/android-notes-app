# Persistent Notes App 📝

A modern Android application built to demonstrate local data persistence using **Room Database**, **Kotlin Symbol Processing (KSP)**, and **Jetpack Compose** following **MVVM (Model-View-ViewModel)** architecture.

---

## 🚀 Features
* **Create & Save Notes:** Add notes with a custom **Title** and **Content** using a clean Material 3 dialog interface.
* **Persistent Storage:** All notes are safely stored locally in an embedded SQLite database via Room, ensuring data survives app restarts.
* **Real-Time UI Updates:** Uses Kotlin **Flow** and `StateFlow` to automatically update the Jetpack Compose UI whenever database records change.
* **Delete Functionality:** Easily remove unwanted notes with a single tap.
* **Pre-populated Data:** Automatically seeds initial starter notes on first app installation.

---

## 🏗️ Architecture & Database Design

This project follows a clean **MVVM architecture** separating concerns into distinct layers: