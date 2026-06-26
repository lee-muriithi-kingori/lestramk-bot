# lestramk-bot

> Lestramk Bot — Interactive Web-Based Chat Assistant for the Lestramk Ecosystem

[![Website](https://img.shields.io/badge/Bot-Live-success.svg)]()
[![HTML5](https://img.shields.io/badge/Built%20with-HTML5-orange.svg)]()
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue.svg)]()

---

## Overview

**lestramk-bot** is an interactive web-based chat assistant designed to help users navigate the Lestramk ecosystem of tools and services. The bot provides instant answers about products, troubleshooting guidance, and support information — all within a sleek, modern web interface.

**Live Demo:** Available via GitHub Pages

---

## Features

- **Interactive Chat Interface** — Clean, modern chat UI with message history
- **Product Information** — Get details about all Lestramk tools and services
- **Troubleshooting Guide** — Common issues and solutions
- **Support Links** — Direct links to WhatsApp and Telegram support
- **Responsive Design** — Works on desktop and mobile browsers
- **Fast & Lightweight** — Pure HTML/CSS/JS, no backend required

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Chat interface structure |
| CSS3 | Modern styling and animations |
| JavaScript | Chat logic and interactivity |
| GitHub Pages | Free hosting |

---

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or backend required

### Local Usage

```bash
# Clone repository
git clone https://github.com/lee-muriithi-kingori/lestramk-bot.git

# Open in browser
cd lestramk-bot
open index.html
```

### Project Structure

```
lestramk-bot/
├── index.html         # Main chat interface (single-file application)
└── README.md          # This file
```

> **Note:** The entire bot is contained in a single `index.html` file for easy deployment and portability.

---

## Bot Capabilities

### Supported Queries

The bot can respond to questions about:

- **LESTRAMK-TOOLKIT** — Android diagnostic toolkit
- **AnonRoute** — Proxy tunneling module
- **NetBoost** — Network optimization
- **GhostPass** — Authentication utility
- **Lespoof** — Samsung spoofing module
- **HBSend** — Money transfer platform
- **General Support** — Contact information and troubleshooting

### How to Use

1. Open the bot in your web browser
2. Type your question in the chat input
3. The bot will respond with relevant information
4. Use the quick-action buttons for common queries

---

## Customization

### Adding New Responses

Edit the `index.html` file to add new bot responses:

```javascript
// Add to the bot's response dictionary
const responses = {
  "new topic": "Your response here...",
  // ... existing responses
};
```

### Styling Changes

All styles are embedded in the HTML `<style>` tag. Modify CSS variables at the top:

```css
:root {
  --primary-color: #00D27A;
  --background: #020610;
  /* ... */
}
```

---

## Deployment

### GitHub Pages

The bot is automatically deployed via GitHub Pages when changes are pushed to the `master` branch.

### Embedding

To embed the bot on another website:

```html
<iframe src="https://lee-muriithi-kingori.github.io/lestramk-bot/" 
        width="400" height="600" frameborder="0">
</iframe>
```

---

## Roadmap

- [ ] Add more conversational responses
- [ ] Integrate with live API for dynamic data
- [ ] Add dark/light theme toggle
- [ ] Multi-language support
- [ ] Chat history persistence (localStorage)

---

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-responses`)
3. Commit your changes (`git commit -m 'Add new bot responses'`)
4. Push to the branch (`git push origin feature/new-responses`)
5. Open a Pull Request

---

## Author

**Lee Muriithi Kingori**

- GitHub: [@lee-muriithi-kingori](https://github.com/lee-muriithi-kingori)
- Part of the [Lestramk](https://github.com/lee-muriithi-kingori) ecosystem

---

<p align="center">
  <sub>lestramk-bot · Your guide to the Lestramk ecosystem · © 2025-2026</sub>
</p>
