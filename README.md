# 🌡️ Temperature Converter Tool (JavaFX Desktop App)

A beginner-friendly JavaFX-based desktop application for converting temperatures. This is a simple yet educational Java project created to demonstrate the JavaFX lifecycle, FXML integration, and basic GUI-based functionality. 

---

## 📂 Project Structure

```
TempTool
|
|── .idea/
|
├── installer/
│      ├── icon.ico
│      └── TempTool.jar                 # Executable JAR file
├── out/                                # IntelliJ output directory
│      ├── artifacts/
│      └── production/
├── src/
│      ├── icon/
│      │     ├── Temp.ico
│      │     └── Temp.png
│      ├── META-INF/
│      │     └── MANIFEST.MF           # Manifest for JAR packaging
│      └── tempToolPackage/
│            ├── Tool.fxml             # FXML UI layout
│            ├── ToolController.java   # Controller logic
│            └── ToolMain.java         # Main application class
└── TempTool.iml                       # IntelliJ module file
```


---


## 🚀 Features

- ✅ Convert temperature units (Celsius ↔ Fahrenheit).
- ✅ Built with **JavaFX** and **FXML** for clean MVC separation.
- ✅ **Menu Bar**:
  - **File → New**: Clears input field.
  - **File → Quit**: Exits application.
  - **Help → About**: Shows motivational dialog.
- ✅ Uses a custom icon for the app window (`Temp.png`).
- ✅ Demonstrates complete **JavaFX Lifecycle**:
  - `init()`, `start()`, `stop()` with console logs.

---

## 🛠️ Technologies Used

| Tool                         | Version       | Download Link                                                                 |
|------------------------------|---------------|-------------------------------------------------------------------------------|
| Java (JDK)                   | 1.8.0_212      | [Download Java 1.8.0_212 (Oracle)](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html) |
| JavaFX                       | Built-in with JDK 8 | *(No separate install needed)*                                                |
| IntelliJ IDEA Community      | 2017.2.7       | [Download IntelliJ 2017.2.7](https://www.jetbrains.com/idea/download/other.html) |

> **Note:** JavaFX is bundled with JDK 8. No additional modules or SDKs are needed.

---

## 📦 How to Run

1. Clone or download this repository.
2. Open the project in **IntelliJ IDEA 2017.2.7**.
3. Ensure **Java 1.8.0_212** is selected in Project SDK.
4. Right-click `ToolMain.java` → **Run**.

---

## 🔧 Build Executable JAR (Optional)

1. In IntelliJ, go to:  
   `File` → `Project Structure` → **Artifacts**
2. Click `+` → **JAR** → *From modules with dependencies*
3. Set **Main Class** to:  
   `tempToolPackage.ToolMain`
4. Include:
   - `Tool.fxml`
   - `Temp.png`
   - `MANIFEST.MF`
5. Apply → OK → `Build` → **Build Artifacts** → `TempTool.jar`

The final `.jar` will be in:
```
out/artifacts/TempTool_jar/TempTool.jar
```



---

## 📥 Download

👉 [Download TempTool.jar](#)  


---


## 🧠 Notes for Learners

- `ToolMain.java` handles lifecycle and stage setup.
- `ToolController.java` processes input/output and events.
- `Tool.fxml` defines the UI using declarative XML.
- Icons (`Temp.png`) must be in the correct resource path (`/icon/`) to appear in the app window.
- Good starting point to explore:
  - JavaFX CSS styling
  - Theme switching
  - More input types

---

## 📄 License

This project is open for educational and personal use.

---

## 👨‍💻 Author

**Kanhaiya Gupta**  
📧 [kanhaiyaguptaksg@gmail.com](mailto:kanhaiyaguptaksg@gmail.com)

[![Website Badge](https://img.shields.io/badge/Visit-Website-blue)](http://officialkanha.epizy.com/)

---

> _"Code. Learn. Build. Repeat."_

