# ◈ GroqChat

> Ultraschnelle KI-Chat WebApp, powered by the [Groq API](https://groq.com).

![Screenshot](https://img.shields.io/badge/status-ready-52e3a1?style=flat-square) ![HTML](https://img.shields.io/badge/stack-HTML%20%2B%20CSS%20%2B%20JS-7c6af7?style=flat-square) ![No Build](https://img.shields.io/badge/build-none-f76ab4?style=flat-square)

---

## Features

- ⚡ Superschnelle Antworten via Groq Inference API
- 🤖 Mehrere Modelle wählbar (Llama 3.3 70B, Mixtral, Gemma u.a.)
- 💬 Vollständige Chat-History (Gesprächsgedächtnis)
- 🎨 Dunkles, modernes UI – kein Framework nötig
- 📦 Kein Build-Tool, kein npm – einfach `index.html` öffnen

---

## Schnellstart

### 1. Repository klonen

```bash
git clone https://github.com/DEIN_USERNAME/groqchat.git
cd groqchat
```

### 2. Datei öffnen

Einfach `index.html` im Browser öffnen – fertig.

> Oder mit einem lokalen Server:
> ```bash
> npx serve .
> # oder
> python3 -m http.server 8080
> ```

### 3. API-Key eingeben

1. Kostenfreien API-Key holen: [console.groq.com](https://console.groq.com)
2. Key in das Eingabefeld `API KEY` oben in der App einfügen
3. Modell auswählen und loschatten!

---

## Verfügbare Modelle

| Modell | Stärke |
|--------|--------|
| `llama-3.3-70b-versatile` | Beste Qualität, vielseitig |
| `llama-3.1-8b-instant` | Schnellstes Modell |
| `mixtral-8x7b-32768` | Langes Kontextfenster (32k) |
| `gemma2-9b-it` | Googles Gemma 2 |

---

## Sicherheitshinweis

⚠️ **Teile deinen API-Key niemals öffentlich!**
Trage ihn nur lokal im Browser ein. Der Key wird nicht gespeichert oder übertragen.

---

## GitHub Pages Deployment

1. Repository auf GitHub hochladen
2. Settings → Pages → Branch: `main` → Ordner: `/ (root)`
3. Deine App ist live unter: `https://DEIN_USERNAME.github.io/groqchat`

---

## Stack

- **HTML5 / CSS3 / Vanilla JS** — kein Framework
- **Groq OpenAI-kompatible API** — direkter `fetch()`-Aufruf
- **Google Fonts** — Syne + Space Mono

---

## Lizenz

MIT — frei nutzbar und anpassbar.
