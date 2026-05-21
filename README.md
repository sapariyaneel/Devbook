<div align="center">

<br />

<img src="https://devbook.neelsapariya.in/icon-512.png" alt="DevBook Logo" width="96" height="96" />

<br />
<br />

# DevBook

### The system for your engineering mind.

Log, organize, and instantly retrieve your technical notes, command snippets, and error resolutions. A personal knowledge base built for developers — not productivity enthusiasts.

<br />

[![Web App](https://img.shields.io/badge/Web_App-Live-black?style=for-the-badge&logo=vercel&logoColor=white)](https://devbook.neelsapariya.in)
[![Android](https://img.shields.io/badge/Android-APK_Download-black?style=for-the-badge&logo=android&logoColor=white)](https://github.com/sapariyaneel/devbook/releases/latest)
[![Extension](https://img.shields.io/badge/Browser-Extension-black?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/sapariyaneel/devbook/releases/latest)
[![CLI](https://img.shields.io/badge/CLI-npm-black?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/devbook-cli)

<br />

---

</div>

<br />

## What is DevBook?

DevBook is a **personal knowledge base for developers**. Every time you debug an error, figure out a config, write a useful snippet, or document an architecture decision — DevBook is where it lives.

No more losing context in scattered Notion pages, random text files, or Slack history. DevBook gives you one fast, searchable vault that you actually use.

> Built by a developer, for developers. The goal is zero friction between having a thought and capturing it.

<br />

## Platform

DevBook is available across all your environments:

| Platform | Status | Download |
|----------|--------|----------|
| **Web App** | Live | [devbook.neelsapariya.in](https://devbook.neelsapariya.in) |
| **Android App** | Available | [Latest Release →](https://github.com/sapariyaneel/devbook/releases/latest) |
| **Browser Extension** | Available | [Latest Release →](https://github.com/sapariyaneel/devbook/releases/latest) |
| **CLI** | Available | `npm install -g devbook-cli` |

<br />

---

## Features

### Notes & Errors
Capture two types of entries built for different situations:

- **Notes** — markdown documents with code blocks, tags, categories, commands, and reference links
- **Errors** — structured entries with error message, root cause, solution, and reproduction steps

### Command Palette
Press `Ctrl+K` anywhere in the app. Search your entire vault by title, content, tags, or category instantly.

### Structured Hierarchy
Organize with categories and subcategories. Drag to reorder. Tag everything atomically. Filter by type, favorite, or trash.

### Markdown Editor
GitHub-flavored markdown with syntax highlighting, live preview side-by-side, and one-click code copy.

### Public Sharing
Make notes public or unlisted. Share a URL to any note. Unlisted notes are accessible only via direct link — not indexed.

### Community Solutions
Browse and upvote public notes from other developers. Discover real solutions to real problems.

<br />

---

## Mobile App

The native **Android app** brings your vault to your pocket.

- Full-text search across every note, error, and snippet
- Offline-first — your vault is cached locally, works without internet
- Quick-capture via the Android share menu from any app
- Instant sync — changes reflect on all platforms in real time
- Favorites, filters, and tags — find anything in seconds

**[Download APK →](https://github.com/sapariyaneel/devbook/releases/latest)**

<br />

---

## Browser Extension

Capture from anywhere on the web without switching tabs.

- Highlight any text on a page and save it directly to DevBook
- Works on all major browsers (Chrome, Firefox, Edge, Brave, Arc)
- One-click capture with automatic source URL attached
- Authorize once via your DevBook account — no manual token needed

**[Download Extension →](https://github.com/sapariyaneel/devbook/releases/latest)**

### Setup

1. Download the extension `.zip` from the [Releases](https://github.com/sapariyaneel/devbook/releases/latest) page
2. Open your browser's extension manager (`chrome://extensions` or equivalent)
3. Enable **Developer Mode**
4. Click **Load unpacked** and select the extracted folder
5. Click **Connect to DevBook** in the extension popup — you'll be redirected to authorize in one click

<br />

---

## CLI

```bash
npm install -g devbook-cli
```

```bash
# Authenticate with your account
devbook login

# Search your vault from the terminal
devbook search "docker build"

# Add a quick note
devbook add "nginx upstream timeout fix"

# List recent entries
devbook list --type error

# Copy a snippet to clipboard
devbook copy <slug>
```

The CLI uses API tokens from your [Settings → API & CLI](https://devbook.neelsapariya.in/settings#api-cli) page.

<br />

---

## API

DevBook has a public REST API. Generate a token from the web app and authenticate all requests with it.

```bash
Authorization: Bearer dvbk_your_token_here
```

```bash
# List your notes
curl https://devbook.neelsapariya.in/api/notes \
  -H "Authorization: Bearer dvbk_your_token"

# Create a new note
curl -X POST https://devbook.neelsapariya.in/api/notes \
  -H "Authorization: Bearer dvbk_your_token" \
  -H "Content-Type: application/json" \
  -d '{"title":"My note","description":"Content here","type":"note"}'
```

<br />

---

## Releases

All downloads — APK, extension, and CLI — are published to the [Releases](https://github.com/sapariyaneel/devbook/releases) page of this repository.

| Asset | Description |
|-------|-------------|
| `devbook-android.apk` | Android app — sideload directly |
| `devbook-extension.zip` | Browser extension — load unpacked |
| Changelog | What changed in each version |

<br />

---

<br />

<div align="center">

## Developer

<br />

<img src="https://avatars.githubusercontent.com/sapariyaneel" alt="Neel Sapariya" width="100" height="100" style="border-radius:50%" />


<h3>Neel Sapariya</h3>

*Software Engineer · Mobile App Developer*

<br />

Designed, built, and shipped every part of this — web app, mobile app, browser extension, CLI, and API. DevBook started as a personal tool to stop losing engineering context. It became something worth sharing.

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-neelsapariya.in-black?style=flat-square&logo=safari&logoColor=white)](https://neelsapariya.in)
[![GitHub](https://img.shields.io/badge/GitHub-sapariyaneel-black?style=flat-square&logo=github&logoColor=white)](https://github.com/sapariyaneel)
[![Twitter](https://img.shields.io/badge/Twitter-@sapariyaneel__-black?style=flat-square&logo=x&logoColor=white)](https://twitter.com/sapariyaneel_)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-neelsapariya-black?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/neelsapariya)

<br />

---

<sub>All source code is private. This repository serves as the public-facing home for releases and documentation.</sub>

<br />

</div>
