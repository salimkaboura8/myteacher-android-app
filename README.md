<div align="center">

# 🎓 MyTeacher Android App

**A virtual classroom app where teachers create classes and share lessons with students**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

[📂 Source](app/src/main/java/com/example/thedraft) · [⚙️ Gradle Config](app/build.gradle)

</div>

---

## 📖 Overview

A native **Android** app written in **Java** that works as a simple virtual classroom. Teachers create classes and upload lessons as PDF files. Students join a class with its code and read the lessons inside the app. Accounts, data and files are all handled by **Firebase**.

## 🔄 How It Works

| Step | What happens |
|:---:|---|
| 1️⃣ | Users sign up and log in with **Firebase Authentication** |
| 2️⃣ | A teacher creates a class with a unique code, stored in **Cloud Firestore** |
| 3️⃣ | Students join the class by entering that code |
| 4️⃣ | Lessons (PDFs) are uploaded to **Firebase Storage** and opened in the built-in PDF viewer |

## ✨ Highlights

| 🔐 Accounts | 📚 Classes & Lessons | 📱 UI |
|---|---|---|
| Firebase Auth sign-up and login<br>User profile header | Create / join classes by code<br>Upload PDF lessons<br>In-app PDF viewer | Navigation drawer<br>RecyclerView lists<br>Floating search bar |

## 🚀 Quick Start

```bash
git clone https://github.com/salimkaboura8/myteacher-android-app.git
```

1. Open the project in **Android Studio**.
2. Replace `app/google-services.json` with the file from your own Firebase project.
3. Sync Gradle and run on an emulator or device.

---

<div align="center">
Made with ❤️ by <a href="https://github.com/salimkaboura8">Salim Kaboura</a>
</div>
