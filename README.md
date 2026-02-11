# Expense Tracker (Android)

A small Android app built with Kotlin + Jetpack Compose to track daily expenses.

## Features
- Add an expense name and amount.
- View all entered expenses for the day.
- See a running total in local currency format.
- Includes a couple of sample expenses on first launch.

## Project structure
- `app/src/main/java/com/example/expensetracker/MainActivity.kt` contains the full UI and state logic.
- `app/src/main/AndroidManifest.xml` configures the launcher activity.
- Gradle Kotlin DSL is used for project/module build configuration.

## Build
From the repo root:

```bash
JAVA_HOME=/path/to/jdk17 gradle :app:assembleDebug
```

> Note: Android Gradle Plugin dependencies are resolved from Google/Maven repositories.
