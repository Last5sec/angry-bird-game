# angry-bird-game
# libGDX Project (gdx-liftoff)

This project was generated using **gdx-liftoff**, the official project setup tool for **libGDX**.  
It includes simple application launchers and a main class extending `Game` that sets the first screen.

---

## 📁 Project Structure

- **core**  
  Main module containing all shared game/application logic.

- **lwjgl3**  
  Primary desktop platform using **LWJGL3** (previously called `desktop` in older docs).

---

## 🛠 Build System

This project uses **Gradle** for dependency management and builds.  
The **Gradle Wrapper** is included, so no separate Gradle installation is required.

- Windows: `gradlew.bat`
- Linux/macOS: `./gradlew`

---

## 🚀 Running the Project

Run the desktop application:
```bash
./gradlew lwjgl3:run
