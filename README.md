# 📱 QR Code Generator

<div align="center">

![QR Code Generator](https://img.shields.io/badge/QR%20Code-Generator-blue?style=for-the-badge&logo=qr-code)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**A beautiful, responsive, and lightning-fast QR code generator built with vanilla JavaScript**

[🚀 Live Demo](#live-demo) • [✨ Features](#features) • [📸 Screenshots](#screenshots) • [🛠️ Installation](#installation) • [💻 Usage](#usage) • [🤝 Contributing](#contributing)

</div>

---

## 🌟 Overview

Transform any text, URL, or data into a scannable QR code instantly! This lightweight web application provides a clean, modern interface for generating high-quality QR codes with customizable options.

### 🎯 Perfect For:

- 📝 **Text Sharing** - Convert messages, notes, or any text
- 🌐 **URL Shortening** - Quick website access
- 📞 **Contact Info** - Phone numbers, emails
- 📱 **Social Media** - Profile links, handles
- 🎫 **Event Planning** - Tickets, invitations
- 💼 **Business Cards** - Digital networking

---

## ✨ Features

<div align="center">

| Feature                   | Description                                    | Status |
| ------------------------- | ---------------------------------------------- | ------ |
| 🎨 **Modern UI**          | Beautiful, responsive design with Tailwind CSS | ✅     |
| ⚡ **Instant Generation** | Real-time QR code creation                     | ✅     |
| 📱 **Mobile Responsive**  | Works perfectly on all devices                 | ✅     |
| 🎯 **High Quality**       | 256x256 resolution with error correction       | ✅     |
| 🚀 **Lightweight**        | No backend required, runs entirely in browser  | ✅     |
| 🔒 **Privacy First**      | All processing happens locally                 | ✅     |
| 💡 **Smart Validation**   | Input validation with helpful error messages   | ✅     |
| 🎭 **Smooth Animations**  | CSS transitions for better UX                  | ✅     |

</div>

---

## 📸 Screenshots

<details>
<summary>🖼️ Click to view screenshots</summary>

### Desktop View

```
┌─────────────────────────────────────────┐
│            QR Code Generator            │
├─────────────────────────────────────────┤
│  Enter your text or URL:                │
│  ┌─────────────────────────────────────┐ │
│  │ Hello World!                        │ │
│  │                                     │ │
│  └─────────────────────────────────────┘ │
│                                         │
│     ┌─── Generate QR Code ───┐          │
│     └───────────────────────┘          │
│                                         │
│     ┌─────────────────────┐             │
│     │   ████ ██ ████     │             │
│     │   ██  ████  ██     │             │
│     │   ████ ██ ████     │             │
│     └─────────────────────┘             │
└─────────────────────────────────────────┘
```

### Mobile View

```
┌───────────────────┐
│  QR Code Generator│
├───────────────────┤
│ Enter text:       │
│ ┌───────────────┐ │
│ │ www.google.com│ │
│ └───────────────┘ │
│                   │
│ ┌─ Generate ──┐   │
│ └─────────────┘   │
│                   │
│ ┌─────────────┐   │
│ │ ████ ██ ████│   │
│ │ ██  ████  ██│   │
│ │ ████ ██ ████│   │
│ └─────────────┘   │
└───────────────────┘
```

</details>

---

## 🛠️ Installation

### Quick Start (Recommended)

1. **Clone the repository**

   ```bash
   git clone https://github.com/itsluckysharma01/QR-Code-Generator.git
   cd QR-Code-Generator
   ```

2. **Open in your browser**
   ```bash
   # Simply open index.html in any modern browser
   start index.html  # Windows
   open index.html   # macOS
   xdg-open index.html  # Linux
   ```

### Alternative Methods

<details>
<summary>📦 Download ZIP</summary>

1. Download the ZIP file from GitHub
2. Extract to your desired location
3. Open `index.html` in your browser

</details>

<details>
<summary>🌐 Serve with Local Server</summary>

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

</details>

---

## 💻 Usage

### Basic Usage

1. **Enter your content** in the text area:

   - Text messages
   - URLs (with or without `https://`)
   - Phone numbers
   - Email addresses
   - Any string data

2. **Click "Generate QR Code"**

   - QR code appears instantly
   - Success message confirms generation

3. **Use your QR code**:
   - Right-click to save image
   - Screenshot for sharing
   - Scan with any QR reader

### 📋 Example Inputs

<details>
<summary>💡 Click for input examples</summary>

| Type         | Example                                 | Use Case             |
| ------------ | --------------------------------------- | -------------------- |
| **Website**  | `https://www.google.com`                | Quick website access |
| **Text**     | `Hello, World!`                         | Message sharing      |
| **Phone**    | `+1-555-123-4567`                       | Contact sharing      |
| **Email**    | `mailto:user@example.com`               | Email quick access   |
| **WiFi**     | `WIFI:T:WPA;S:NetworkName;P:password;;` | WiFi sharing         |
| **SMS**      | `sms:+1234567890:Hello there!`          | Pre-filled SMS       |
| **Location** | `geo:37.7749,-122.4194`                 | GPS coordinates      |

</details>

### ⚙️ Advanced Features

- **High Error Correction**: Uses Level H for maximum scanning reliability
- **Optimal Size**: 256x256 pixels for perfect balance of quality and size
- **Smart Input Handling**: Automatically trims whitespace
- **Real-time Feedback**: Instant validation and error messages

---

## 🏗️ Technical Details

### 📁 Project Structure

```
QR-Code-Generator/
├── 📄 index.html          # Main application file
├── 📄 script.js           # (Currently empty - all JS is inline)
├── 📄 README.md           # This file
└── 📄 .gitignore          # Git ignore file
```

### 🔧 Dependencies

| Library          | Version     | Purpose              | CDN                   |
| ---------------- | ----------- | -------------------- | --------------------- |
| **QRCode.js**    | Latest      | QR generation engine | `cdn.rawgit.com`      |
| **Tailwind CSS** | Latest      | Styling framework    | `cdn.tailwindcss.com` |
| **Inter Font**   | 400,500,700 | Typography           | Google Fonts          |

### 🎨 Color Palette

```css
Primary Blue:   #3B82F6 (bg-blue-600)
Hover Blue:     #1D4ED8 (bg-blue-700)
Success Green:  #10B981 (text-green-500)
Error Red:      #EF4444 (text-red-500)
Background:     #F3F4F6 (bg-gray-100)
Card White:     #FFFFFF (bg-white)
Text Dark:      #1F2937 (text-gray-800)
```

---

## 🚀 Live Demo

### Try it now!

1. **Copy this text**: `Hello from the README! 🎉`
2. Open the application
3. Paste the text
4. Click "Generate QR Code"
5. Scan with your phone to see the magic! ✨

### 🎮 Interactive Demo

<details>
<summary>🔥 Click for browser-based demo</summary>

Since this is a static HTML file, you can:

1. **Fork this repo** on GitHub
2. **Enable GitHub Pages** in repository settings
3. **Access via**: `https://yourusername.github.io/QR-Code-Generator`

Or deploy instantly to:

- 🟢 **Netlify**: Drag & drop the folder
- 🔵 **Vercel**: Connect your GitHub repo
- 🟠 **Firebase Hosting**: `firebase deploy`

</details>

---

## 🎯 Browser Compatibility

| Browser    | Version             | Status             |
| ---------- | ------------------- | ------------------ |
| 🌐 Chrome  | 60+                 | ✅ Fully Supported |
| 🦊 Firefox | 55+                 | ✅ Fully Supported |
| 🧭 Safari  | 12+                 | ✅ Fully Supported |
| 📘 Edge    | 79+                 | ✅ Fully Supported |
| 📱 Mobile  | iOS 12+, Android 6+ | ✅ Fully Supported |

---

## 🤝 Contributing

We love contributions! Here's how you can help:

### 🐛 Found a Bug?

1. Check [existing issues](https://github.com/itsluckysharma01/QR-Code-Generator/issues)
2. Create a new issue with:
   - Clear description
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser/OS information

### 💡 Have an Idea?

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

### 🎨 Enhancement Ideas

<details>
<summary>💭 Click to see enhancement ideas</summary>

- [ ] **Color Customization**: Custom QR code colors
- [ ] **Size Options**: Multiple QR code sizes
- [ ] **Download Button**: Direct image download
- [ ] **Batch Generation**: Multiple QR codes at once
- [ ] **QR Code Scanner**: Built-in scanner functionality
- [ ] **History**: Save previously generated codes
- [ ] **Templates**: Pre-defined input templates
- [ ] **API Integration**: Connect to external services
- [ ] **Print Options**: Print-friendly layouts
- [ ] **Dark Mode**: Theme switching

</details>

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Lucky Sharma

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 👨‍💻 Author

<div align="center">

**Lucky Sharma**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/itsluckysharma01)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/itsluckysharma01)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/itsluckysharma01)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://portfolio-website-pearl-zeta.vercel.app/)

_"Code with passion, create with purpose"_

</div>

---

## 🙏 Acknowledgments

- 📚 **QRCode.js** - Excellent QR generation library
- 🎨 **Tailwind CSS** - Beautiful utility-first CSS framework
- 🔤 **Inter Font** - Clean, readable typography
- 🎯 **GitHub** - Hosting and version control
- 💡 **Stack Overflow** - Community support and solutions

---

## 📊 Project Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/itsluckysharma01/QR-Code-Generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/itsluckysharma01/QR-Code-Generator?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/itsluckysharma01/QR-Code-Generator?style=social)

![GitHub repo size](https://img.shields.io/github/repo-size/itsluckysharma01/QR-Code-Generator)
![GitHub language count](https://img.shields.io/github/languages/count/itsluckysharma01/QR-Code-Generator)
![GitHub last commit](https://img.shields.io/github/last-commit/itsluckysharma01/QR-Code-Generator)

</div>

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

**Made with ❤️ by [Lucky Sharma](https://github.com/itsluckysharma01)**

_Happy Coding! 🚀_

---

</div>

<!-- QR Code for this repository -->
<div align="center">
<sub>📱 <em>Generate a QR code for this repository and share it with your friends!</em></sub>
</div>
