FitLife Android Project
This repository contains the FitLife Android application. It is a Kotlin-based project utilizing modern Android development practices, including Jetpack libraries and Dependency Injection.

🚀 Project Overview
The project is structured as a single-module Android application  configured with the following key components:


Language: Kotlin.


Build System: Gradle with Kotlin DSL (.gradle.kts).


Dependency Injection: Hilt (Dagger) version 2.50.


Navigation: AndroidX Navigation with Safe Args.

Architecture: Follows modern Android standards using AndroidX and the official Kotlin code style.

🛠️ Configuration & Tech Stack
Core Dependencies
Based on the gradle.properties and build.gradle.kts files, the project uses:

AndroidX Navigation: 2.7.7.

Room Database: 2.6.1.

Lifecycle Components: 2.7.0.

Kotlin Coroutines: 1.7.3.

Environment Requirements
Java Version: JDK 17.

Android SDK: Configured locally via sdk.dir.

Memory: The Gradle daemon is configured with a max heap size of 2048m.

🛠️ Getting Started
Prerequisites
Ensure you have the following installed:

Android Studio (Latest stable version recommended).

JDK 17.

Building the Project
You can build the project using the included Gradle Wrapper:

For Windows:

Bash
gradlew.bat build
For macOS/Linux:

Bash
./gradlew build
📂 Project Structure

app/: The main application module.


gradle/: Contains the Gradle Wrapper files.


.gitignore: Standard Android exclusions including build artifacts, IDE settings, and local properties.

📄 License
This project includes Gradle Wrapper scripts which are licensed under the Apache License, Version 2.0.
