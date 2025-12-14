# Elo-Climb Inspo – Zitate Generator mit 101 Zitaten

**Elo-Climb Inspo** ist eine kleine, webbasierte Anwendung, die inspirierende Zitate des High‑Elo‑Beraters **Sparkassen‑Hänno** anzeigt – perfekt für alle, die beim Elo‑Climb noch ein bisschen Extra‑Motivation brauchen.

Die App ist mit **HTML**, **CSS**, **JavaScript** und **JSON** umgesetzt und läuft komplett im Browser.


## Image Preview
![Preview](https://github.com/Florii02/haenno-zitate/blob/e96c2d92191234ce57dbde45d6080d321bada2cf/preview.jpg)

---

## Features

- 🎯 **Zufällige Zitate**  
  Bei jedem Klick wird ein zufälliges Zitat aus einer Liste angezeigt.

- 🔁 **Neues Zitat per Button**  
  Über den Button (z.B. „Gold farmen“) lässt sich jederzeit ein neues Zitat laden.

- 📱 **Responsive Design**  
  Das Layout ist so gestaltet, dass es auf Desktop‑ und Mobilgeräten gut aussieht.

- ⚡ **Einfach & Schnell**  
  Keine Frameworks, keine externen Libraries – nur Vanilla HTML/CSS/JS.

---

## How It Works

1. Beim Laden der Seite wird ein zufälliges Zitat aus der `quotes.json` gelesen.
2. Das Zitat wird im hervorgehobenen Quote‑Bereich angezeigt.
3. Ein Klick auf den Button lädt ein neues, zufälliges Zitat.
4. Die Daten der Zitate (Text, ggf. Autor) liegen in einer separaten JSON‑Datei (`quotes.json`).


## Usage

1. Repository klonen oder herunterladen.
2. `index.html` im Browser öffnen (Doppelklick oder „Open With Live Server“ o.Ä.).
3. Beim Laden der Seite wird automatisch ein zufälliges Zitat angezeigt.
4. Über den Button ein neues Zitat generieren.

Es ist kein Build‑Schritt und kein Backend notwendig.

---

## Project Structure

```text
.
├── index.html   # Hauptseite mit Markup
├── style.css    # Styling im Sparkassen-Look
├── script.js    # Logik für zufällige Zitate & Button
├── quotes.json  # Zitatdaten (Text, optional Autor)
└── Haenno.jpg   # Titelbild mit Sparkassen-Hänno
