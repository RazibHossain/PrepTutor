# PrepForge 🔥

> A lightweight, local-first interview preparation tool built with Vanilla JavaScript, HTML, and Tailwind CSS.

PrepForge helps developers and students organize, manage, and practice technical interview questions without requiring a backend or user account. Everything runs directly in your browser, and all data is stored locally using the browser's `localStorage`.

---

## ✨ Features

### 📝 Question Management
- Add, edit, and delete interview questions
- Organize questions by:
  - Topic
  - Subtopic
  - Difficulty (Easy, Medium, Hard)
  - Revision Type (Quick, Regular)
- Mark important questions as favorites

### ⚡ Custom Practice Sessions
- Generate practice sessions using custom filters
- Practice with interactive flip cards
- Track practice time
- Focus on specific topics or difficulty levels

### 📊 Interactive Dashboard
- Visualize your preparation progress
- Donut charts for:
  - Difficulty distribution
  - Revision type distribution
- Track mastery rates
- View recent activity

### 📁 Topics Overview
- Browse all topics in a clean grid layout
- View difficulty distribution for each topic
- Monitor practice completion progress

### 🔍 Powerful Search & Filtering
Filter questions by:
- Keyword search
- Topic
- Subtopic
- Difficulty
- Revision type
- Favorites

### 💾 Local-First & Private
- No account or login required
- No server or database
- Data remains in your browser
- Works completely offline after loading

### 📤 Import & Export
- Export your entire question bank as a JSON file
- Import previously exported backups
- Merge or overwrite existing data

### 📱 Responsive Design
- Modern dark-themed interface
- Optimized for desktop, tablet, and mobile devices

---

## 🛠️ Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript (ES6+)
- Font Awesome
- Google Fonts (Space Grotesk & DM Sans)
- Browser Web APIs
  - `localStorage`
  - `FileReader`

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/PrepForge.git
```

### 2. Navigate to the project

```bash
cd PrepForge
```

### 3. Run the application

Simply open `index.html` in your preferred web browser.

For a better development experience, use the **Live Server** extension in VS Code.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + N` | Open the **Add Question** dialog |
| `Space` | Flip the practice card |
| `Esc` | Close active modal or overlay |

---

## 📂 Data Management

### Automatic Saving
Every change is automatically saved to your browser's local storage.

### Export
Download your complete question bank as a JSON backup.

### Import
Import a previously exported JSON file and choose to:

- Merge with existing data
- Replace existing data

---

## 📸 Screenshots

> Add screenshots here.

```
screenshots/
├── dashboard.png
├── questions.png
├── practice.png
└── topics.png
```

Example:

```md
![Dashboard](screenshots/dashboard.png)
![Practice Mode](screenshots/practice.png)
```

---

## 📁 Project Structure

```
PrepForge/
│
├── index.html
├── css/
├── js/
├── assets/
├── screenshots/
└── README.md
```

---

## 🌟 Why PrepForge?

- ✅ No backend required
- ✅ Completely private
- ✅ Fast and lightweight
- ✅ Works offline
- ✅ Easy backup & restore
- ✅ Mobile-friendly
- ✅ Perfect for interview preparation

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push to GitHub

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute it.

---

## ⭐ Support

If you find this project useful, consider giving it a **⭐ Star** on GitHub. It helps others discover the project and motivates future improvements.