# Trio- Monorepo

This repository is organized as a portfolio-style monorepo containing 5 independent women-safety related projects.

## Included Projects

1. **sheguard**  
   Source: https://github.com/Mahmud0808/SheGuard
2. **safeguardher**  
   Source: https://github.com/fariaislam04/SafeGuardHer-Women-Safety-App
3. **ladybuddy**  
   Source: https://github.com/Moheeeetgupta/LadyBuddy-A-woman-safety-app
4. **wsafe**  
   Source: https://github.com/SuriyaaVijay/WSafe-Women-Safety-Application
5. **shesecure**  
   Source: https://github.com/karthiikJR/SheSecure

## Monorepo Structure

```text
projects/
   01-sheguard/
   02-safeguardher/
   03-ladybuddy/
   04-wsafe/
   05-shesecure/
```

## Independence Rules

- Each project remains self-contained inside its own folder.
- Dependencies are **not merged** across projects.
- Each app should be run from its own directory.
- Inner `.git` directories were removed so this repo has a single Git history at the root.

## Run Each Project Individually

> Open a terminal at the root of this repository first.

### 1) sheguard (Android / Gradle)

```powershell
cd projects/01-sheguard
.\gradlew.bat tasks
```

Typical Android Studio workflow:
- Open `projects/01-sheguard` as an Android project.
- Build/run from Android Studio, or use Gradle wrapper commands.

### 2) safeguardher (Flutter)

```powershell
cd projects/02-safeguardher
flutter pub get
flutter run
```

### 3) ladybuddy (Android / Gradle)

```powershell
cd projects/03-ladybuddy
.\gradlew.bat tasks
```

### 4) wsafe (Android / Gradle)

```powershell
cd projects/04-wsafe
.\gradlew.bat tasks
```

### 5) shesecure (Android / Gradle)

```powershell
cd projects/05-shesecure
.\gradlew.bat tasks
```

## Notes

- If Gradle wrapper execution is blocked on Windows, run PowerShell as Administrator once and configure execution policy if needed.
- For Android projects, ensure Android SDK/JDK are installed and configured in Android Studio.
- For Flutter project (`safeguardher`), ensure Flutter SDK is installed and available in PATH.
