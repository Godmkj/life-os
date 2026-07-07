# LIFE OS

LIFE OS is an all-in-one daily life operating system built with Flutter. It combines productivity, daily tasks, calendar scheduling, fitness, goals, missions, study planning, glow-up routines, business tracking, analytics, and local backup tools in one app.

The app is designed with a clean light fantasy style: pure white surfaces, soft gray gradients, elegant shadows, smooth Material 3 controls, and a calm premium dashboard experience.

## Author

Created by **MONISH K JAYAN**

- GitHub: [Godmkj](https://github.com/Godmkj)
- X / Twitter: [@MONISHKJAYAN](https://x.com/MONISHKJAYAN)

## Current Status

- Flutter project generated for Android, Windows, and Web.
- App source code is implemented in `lib/main.dart`.
- `flutter analyze` passes with no issues.
- `flutter test` passes.
- Web build has been generated in `build/web`.
- Windows build needs Windows Developer Mode enabled.
- Android APK build needs Android Studio / Android SDK installed.

## Main Features

- Onboarding with name, age, gender, weight, height, main goal, and arc selection.
- Dashboard with daily schedule, XP, level, completed items, skipped exercises, and arc rules.
- Task manager with add, edit, delete, complete, categories, priorities, date, and time.
- Calendar view that combines tasks, workouts, goals, exams, glow-up items, and business items.
- Fitness section with exercise levels, sets/reps, muscle groups, complete and skip tracking.
- Skip analysis that detects which muscle/exercise area is skipped most.
- Goals and missions with progress, target milestones, XP, and completion.
- Study and exams with subjects, revision topics, date tracking, and countdown.
- Glow-up section for sleep, skincare, mood, meditation, hygiene, and confidence missions.
- Business section for tasks, income, expenses, clients, content, and projects.
- Analytics with completion stats, productivity insights, XP, and skipped exercise patterns.
- Settings with profile editing, local JSON export, JSON import, and reset.

## No Dummy Buttons Rule

Every visible action is connected to real app behavior. Buttons either:

- save data
- edit data
- delete data
- complete an item
- skip/unskip an exercise
- import/export data
- reset local data
- open a real working dialog

There are no fake placeholder buttons.

## Tech Stack

- Flutter
- Dart
- Material 3
- Shared Preferences for local storage
- Local-only data model

## Flutter Version Used

Tested with:

```powershell
Flutter 3.44.5
Dart 3.12.2
```

Flutter SDK path on this machine:

```powershell
C:\Users\monis\Downloads\flutter
```

## Run The App

From the project folder:

```powershell
cd "C:\Users\monis\OneDrive\Documents\life goal\life_os_flutter"
C:\Users\monis\Downloads\flutter\bin\flutter.bat pub get
C:\Users\monis\Downloads\flutter\bin\flutter.bat run
```

## Web Build

Build web:

```powershell
C:\Users\monis\Downloads\flutter\bin\flutter.bat build web
```

Output folder:

```text
build/web
```

Upload everything inside `build/web` to a static web host such as GitHub Pages, Netlify, Vercel, or any normal web server.

## Windows Build

Before building Windows, turn on Developer Mode:

```powershell
start ms-settings:developers
```

Then build:

```powershell
C:\Users\monis\Downloads\flutter\bin\flutter.bat build windows
```

Output folder:

```text
build/windows/x64/runner/Release
```

That folder contains the Windows `.exe` and required files. Keep the files together when sharing the app.

## Android APK Build

Install Android Studio and Android SDK first. Then run:

```powershell
C:\Users\monis\Downloads\flutter\bin\flutter.bat doctor
C:\Users\monis\Downloads\flutter\bin\flutter.bat doctor --android-licenses
C:\Users\monis\Downloads\flutter\bin\flutter.bat build apk --release
```

APK output:

```text
build/app/outputs/flutter-apk/app-release.apk
```

## Verification Commands

```powershell
C:\Users\monis\Downloads\flutter\bin\flutter.bat analyze
C:\Users\monis\Downloads\flutter\bin\flutter.bat test
```

Expected result:

- Analyze: no issues found.
- Tests: all tests passed.

## GitHub Upload Steps

1. Create a new repository on GitHub.
2. Open PowerShell inside this project folder.
3. Run these commands:

```powershell
git init
git add .
git commit -m "Initial LIFE OS Flutter app"
git branch -M main
git remote add origin https://github.com/Godmkj/YOUR_REPOSITORY_NAME.git
git push -u origin main
```

Replace `YOUR_REPOSITORY_NAME` with the repository name you created.

If Git asks for login, use GitHub browser login or a GitHub personal access token.

## Suggested Repository Description

```text
LIFE OS is a Flutter all-in-one productivity, fitness, goals, calendar, study, glow-up, business, and analytics app with local storage.
```

## Suggested GitHub Topics

```text
flutter
dart
productivity
task-manager
calendar
fitness
goals
android
windows
web
life-os
```

## Folder Guide

```text
lib/main.dart      Main LIFE OS app source code
android/           Android platform project
windows/           Windows platform project
web/               Web platform project
test/              Flutter widget tests
build/web/         Generated web release files
```

## Future Improvements

- Better calendar day/week/month interaction.
- Drag-and-drop scheduling.
- More exercise illustrations.
- Notification reminders.
- More advanced analytics.
- Optional cloud sync.
- AI exercise camera form checker after the base app is stable.
