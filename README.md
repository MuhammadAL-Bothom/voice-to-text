# 🎤 Voice to Text App

**Voice to Text App** is a lightweight Android application (Java) that converts **spoken words into text** using Google Speech Services.  
It provides a simple interface: press the button, speak into your device, and see your speech converted instantly into text on the screen.

---

## 📱 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/04c24a09-d164-4f3f-8e5f-7f0dec996a9c" alt="Home Screen" width="250"/>
  <img src="https://github.com/user-attachments/assets/c4681c6a-b789-42b1-bfa8-2a6a5d6b782f" alt="Listening Mode" width="250"/>
  <img src="https://github.com/user-attachments/assets/5917138a-1154-4510-b028-650bb7d49b8c" alt="Converted Speech to Text" width="250"/>
  <img src="https://github.com/user-attachments/assets/2cda4868-b3f6-4ae4-8b9c-e0aee0dcd801" alt="Text Updated on Screen" width="250"/>
</p>


---

## ✨ Features
- 🎙 **Voice Recognition**
  - Uses Google Speech API (`RecognizerIntent`) to recognize speech.
  - Supports free-form natural speech.

- 📝 **Text Output**
  - Converts recognized speech into text and displays it in a `TextView`.
  - Automatically updates when recognition is complete.

- ⚡ **One-Click Action**
  - Just press the button to start voice input.
  - Shows Google’s speech dialog with real-time feedback.

- 🌍 **Multi-language Support**  
  - Default: English (United States).  
  - Can be configured to support other languages.

---

## 🛠 Tech Stack
- **Language:** Java (Android)  
- **UI:** ConstraintLayout, Material Button, TextView  
- **API:** Android `RecognizerIntent` (Speech to Text)  

---

## 📂 Project Structure
```plaintext
app/
 ├─ src/main/java/com/example/voicetotext/
 │   └─ MainActivity.java         # Main activity with speech-to-text logic
 │
 ├─ res/layout/
 │   └─ activity_main.xml         # Layout with TextView + Button
 │
 ├─ res/values/
 │   └─ strings.xml, colors.xml   # App resources
 │
 └─ README.md
