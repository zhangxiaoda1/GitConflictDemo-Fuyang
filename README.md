# GitConflictDemo-Fuyang

Android Studio project for **Practical 4: Collaborating with Git and Resolving Merge Conflicts** (using **GitHub** instead of GitLab).

## About

This application contains a simple user interface with two buttons. Initially both buttons have the same default colour (grey).

In later parts of the practical:

- the `feature-red-button` branch changes the button colour to red (`#F44336`);
- the `feature-green-button` branch changes the button colour to green (`#4CAF50`);
- merging both branches produces an intentional merge conflict, which the group must resolve.

## Build

Open the project in Android Studio, or build from the command line:

```
gradlew assembleDebug
```

## Tech stack

- Android Gradle Plugin 9.4.1 / Gradle 9.6.0
- compileSdk 37, minSdk 24
- Java, AndroidX AppCompat, Material Components
