# PAN Studios — Website

Moderne, statische Website für das Tonstudio **PAN Studios** in Berlin.
Aufgebaut mit HTML, CSS und einem kleinen JavaScript-Snippet — keine
Build-Tools, kein Framework. Einfach hochladen und es läuft.

---

## 📁 Projektstruktur

```
pan-studios/
├── index.html          ← Hauptseite (alle Texte/Inhalte hier)
├── css/
│   ├── base.css        ← Farben, Fonts, Reset
│   ├── layout.css      ← Grids & Sektionen
│   └── components.css  ← Buttons, Karten, Nav
├── js/
│   └── main.js         ← Kleine Interaktionen
├── images/             ← Hier deine Bilder ablegen
│   ├── hero.jpg
│   ├── studio-1.jpg
│   ├── studio-2.jpg
│   └── location.jpg
└── README.md
```

---

## 🖼️ Bilder austauschen

Lege deine Bilder einfach in den `images/`-Ordner und benenne sie:

| Datei                  | Verwendet für              | Empfohlene Größe |
|------------------------|----------------------------|------------------|
| `images/hero.jpg`      | Großes Hero-Bild oben      | 1920 × 1080 px   |
| `images/studio-1.jpg`  | Studio-Galerie links       | 800 × 1067 px    |
| `images/studio-2.jpg`  | Studio-Galerie rechts      | 800 × 1067 px    |
| `images/location.jpg`  | Außenansicht oder Karte    | 1200 × 900 px    |

Solange ein Bild fehlt, wird ein dezenter Platzhalter angezeigt.

> Du kannst die Pfade auch direkt in `index.html` ändern — suche einfach
> nach `images/` und passe sie an.

---

## ✏️ Inhalte ändern

Alle Texte stehen in **`index.html`**. Beispiele:

- **Adresse** → Suche nach `Musterstraße 12`
- **Telefon** → Suche nach `+49 30 123 456 789` (an 2 Stellen — sichtbarer Text und `tel:`-Link)
- **Email** → Suche nach `hello@pan-studios.de` (an 2 Stellen — sichtbarer Text und `mailto:`-Link)
- **Technik** → Im Bereich `<section id="technik">` einfach die `<li>`-Einträge anpassen
- **Öffnungszeiten / Anreise** → Bereich `<section id="location">`

---

## 🎨 Farben anpassen

In `css/base.css` findest du oben alle Farb- und Font-Variablen:

```css
:root {
  --bg:      #0e0d0b;   /* Hintergrund */
  --fg:      #f4ede0;   /* Textfarbe */
  --accent:  #ff5b1f;   /* Akzentfarbe (Orange) */
  ...
}
```

---

## 🚀 Publizieren

Da die Seite komplett statisch ist, kannst du sie überall hosten:

- **Netlify** — Ordner per Drag & Drop auf netlify.com/drop
- **Vercel** — `vercel deploy` im Projektordner
- **GitHub Pages** — Repo erstellen, Pages aktivieren
- **Klassisch FTP** — alle Dateien in den Webroot deines Hosters

Lokal testen: einfach `index.html` im Browser öffnen, oder

```bash
python3 -m http.server 8000
```

---

Viel Erfolg mit PAN Studios! ◐
