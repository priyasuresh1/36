# Jatre Namma

Jatre Namma is an Android application built for the village fair use case described in the PRD. The project uses a mixed `Kotlin + Java` setup:

- `Kotlin` powers the Compose UI and screen flow
- `Java` holds the shared domain models and repository data

## Features

- Live schedule with active-event highlighting
- Lost & found flow with resolved-state toggle
- Parking and safety guidance with a fairground snapshot
- Cultural story cards for festival context

## Build

The project is configured for:

- Android SDK `34`
- Min SDK `26`
- Kotlin `1.9.24`
- Android Gradle Plugin `8.5.2`

From the project folder:

```powershell
.\gradlew.bat assembleDebug
```

The debug APK is generated at:

`app\build\outputs\apk\debug\app-debug.apk`
