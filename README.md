# 📝 CookieNotes - Persistent Vanilla JavaScript Notes App

A lightweight note-taking application built using **HTML, CSS, and Vanilla JavaScript**. CookieNotes allows users to create, edit, organize, pin, search, and manage notes while automatically saving data using browser cookies.

---

## 📖 Overview

CookieNotes is a browser-based notes manager that demonstrates modern JavaScript concepts without using any external libraries or frameworks. The application provides real-time editing, automatic persistence, intelligent filtering, sorting, and dynamic UI updates through client-side state management.

---

## ✨ Features

### 📒 Note Management

* Create new notes
* Edit existing notes
* Delete notes to Trash
* Restore deleted notes
* Permanently delete notes
* Pin and unpin notes

### 💾 Persistent Storage

* Automatic cookie-based storage
* JSON serialization
* Base64 encoding for safe cookie storage
* Automatic loading of saved notes
* Cookie size validation

### 🔍 Search & Filtering

* Live search
* Case-insensitive searching
* Search by title
* Search by content
* Active Notes view
* Trash view

### 📌 Smart Sorting

* Pinned notes appear first
* Recently updated notes appear first
* Automatic ordering after every change

### ⚡ Live Editing

* Real-time note updates
* Automatic saving
* Dynamic word count
* Instant UI synchronization

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript (ES6+)
* Browser Cookies
* JSON
* Base64 Encoding

---

## 📂 Project Structure

```text
CookieNotes/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
```

---

## ⚙️ Core JavaScript Concepts

* DOM Manipulation
* Event Listeners
* State Management
* Cookie Management
* JSON Serialization
* Base64 Encoding & Decoding
* Array Methods

  * `find()`
  * `filter()`
  * `sort()`
* String Methods
* Date Objects
* Exception Handling

---

## 🚀 Application Workflow

```text
Create/Edit Note
        │
        ▼
Update Application State
        │
        ▼
Save Notes to Cookies
        │
        ▼
Refresh User Interface
        │
        ▼
Apply Filtering & Sorting
```

---

## 📌 Key Functionalities

* Persistent cookie-based storage
* Dynamic note rendering
* Live search filtering
* Pin/Unpin notes
* Trash management
* Automatic sorting
* Word count tracking
* Timestamp updates
* Real-time synchronization

---

## 🎯 Learning Objectives

This project demonstrates practical implementation of:

* Client-side state management
* Browser cookie persistence
* Dynamic DOM updates
* Event-driven programming
* JavaScript array manipulation
* Real-time user interface updates
* Modular JavaScript architecture

---

## 📷 Preview

> Add screenshots or a GIF of your application here.

```
assets/
├── home.png
├── editor.png
└── search.png
```

---

## 🔧 Future Improvements

* Local Storage / IndexedDB support
* Dark Mode
* Categories and Labels
* Rich Text Editor
* Markdown Support
* Drag & Drop Notes
* Export / Import Notes
* Note Color Themes
* Keyboard Shortcuts
* Responsive Mobile Layout

---

## 🏃 Getting Started

1. Clone the repository.

```bash
git clone https://github.com/your-username/cookie-notes-js.git
```

2. Open the project folder.

```bash
cd cookie-notes-js
```

3. Launch `index.html` in your browser.

No installation or external dependencies are required.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

