# Minilektion: Meine eigene Website mit Google AI Studio

Material für eine SVEB-Minilektion (Micro-Teaching, 20–25 Min.) für **absolute Einsteiger:innen**.
Kernstück ist ein **Prompt-Baukasten**: eine einzelne HTML-Datei, in der die Teilnehmenden per
geführten Fragen einen Website-Auftrag («Prompt») zusammenstellen, kopieren und in
[Google AI Studio](https://aistudio.google.com/apps) (Build-Modus) einfügen.

🔗 **Live:** https://criseone.github.io/meine-website-ai-studio/

## Ordnerstruktur

```
meine-website-ai-studio/
├── index.html          ← Prompt-Baukasten (Startseite der Website)
├── qr.png              ← QR-Code, der auf die Live-Adresse zeigt
├── README.md           ← diese Übersicht
└── unterlagen/         ← Material rund um die Lektion
    ├── feinplanung.md  ← schriftliche Vorbereitung (Abgabe via myLWO)
    ├── feinplanung.pdf
    ├── handout.md      ← einseitiges Handout für Teilnehmende
    ├── handout.pdf
    ├── slides.pptx     ← Präsentationsfolien (10 Folien, ARIVA)
    └── slides.pdf
```

> `index.html` muss im Hauptordner bleiben – GitHub Pages nutzt sie als Startseite.

## Auf GitHub Pages veröffentlichen

1. Neues Repository **`meine-website-ai-studio`** (öffentlich) anlegen und diese Dateien
   inkl. Ordner `unterlagen/` hochladen.
2. Im Repository: **Settings → Pages**.
3. Bei **Source** «Deploy from a branch» wählen, Branch `main`, Ordner `/ (root)`, **Save**.
4. Nach ~1 Minute ist die Seite live unter:
   **https://criseone.github.io/meine-website-ai-studio/**
5. Dieser Link und der QR-Code `qr.png` stecken bereits im Handout und in der Feinplanung.

## Lokal testen

`index.html` per Doppelklick im Browser öffnen — es ist kein Server nötig.

## Technisches

- Reines HTML/CSS/JavaScript, **keine externen Bibliotheken**, kein Tracking, kein Netzwerkzugriff.
- Eingaben werden nur im `localStorage` des Browsers zwischengespeichert (bleiben auf dem Gerät).
- Funktioniert auf Smartphone und Computer.
