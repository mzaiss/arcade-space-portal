# Arcade Space Portal 🚀

Ein actionreiches Raumschiff-Spiel, bei dem du durch schwarze Löcher navigierst, Monster bekämpfst und durch Wurmlöcher zu neuen Leveln springst!

## 🎮 Spielen

**Live auf GitHub Pages:** [Spiel starten](https://mzaiss.github.io/arcade-space-portal/)

Oder öffne einfach `index.html` in deinem Browser.

## 🎯 Spielziel

- Navigiere dein Raumschiff durch das Universum
- Zerstöre alle Monster, bevor du das Wurmloch betrittst
- Vermeide schwarze Löcher - sie sind tödlich!
- Sammle Power-Ups für stärkere Waffen
- Überlebe so viele Level wie möglich

## 🕹️ Steuerung

### Desktop
- **Pfeiltasten**: Raumschiff steuern
- **Strg**: Raketen abfeuern (kontinuierlich)
- **B**: Bombe abfeuern (5 Sekunden Cooldown)
- **1-9**: Zu Level 1-9 springen (Cheat)

### Mobile (Neigungssensor)
- **Gerät neigen**: Raumschiff steuern
- **Bildschirm tippen**: Raketen abfeuern
- Tippe auf "Neigung aktivieren" und erlaube die Berechtigung

### Gamepad
- **Linker Stick**: Steuerung
- **A-Taste**: Raketen abfeuern
- **B-Taste**: Bombe abfeuern

## 🎁 Power-Ups

Sammle Power-Ups von besiegten Monstern:
- **2️⃣**: Doppelschuss
- **3️⃣**: Dreifachschuss
- **4️⃣**: Vierfachschuss
- **5️⃣**: Fünfschuss
- **9️⃣**: Neunschuss (alle Richtungen)

Power-Ups halten 15 Sekunden.

## 🚀 GitHub Pages Deployment

### Automatisches Deployment

1. **Repository erstellen** auf GitHub
2. **Repository-Name**: `arcade_space_portal` (oder dein gewählter Name)
3. **Dateien hochladen**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/arcade_space_portal.git
   git push -u origin main
   ```

4. **GitHub Pages aktivieren**:
   - Gehe zu Repository Settings → Pages
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
   - Klicke auf "Save"
   - Deine Seite ist verfügbar unter: `https://YOUR_USERNAME.github.io/arcade_space_portal/`

### Manuelles Deployment

Falls du einen anderen Branch oder Ordner verwenden möchtest:
- Erstelle einen `gh-pages` Branch
- Oder verwende den `docs/` Ordner

## 📱 Mobile Unterstützung

Das Spiel unterstützt vollständig mobile Geräte:
- **Responsive Design**: Passt sich an verschiedene Bildschirmgrößen an
- **Touch-Steuerung**: Tippen zum Schießen
- **Neigungssensor**: Gerät neigen zum Steuern (erfordert HTTPS auf GitHub Pages)
- **Optimierte Performance**: Läuft flüssig auf modernen Smartphones

### Neigungssensor aktivieren

1. Öffne das Spiel auf deinem Handy
2. Tippe auf "Neigung aktivieren"
3. Erlaube die Berechtigung für Bewegungssensoren
4. Neige dein Gerät zum Steuern

**Hinweis**: Auf iOS 13+ ist eine explizite Berechtigung erforderlich. Auf Android funktioniert es meist automatisch.

## 🛠️ Technische Details

- **Reine HTML/CSS/JavaScript**: Keine Build-Schritte erforderlich
- **Canvas-basiert**: Flüssige 60 FPS Animationen
- **Gamepad API**: Unterstützung für Xbox/PlayStation Controller
- **Device Orientation API**: Mobile Neigungssensor-Unterstützung
- **Touch Events**: Native Touch-Unterstützung für mobile Geräte

## 📂 Projektstruktur

```
arcade-space-portal/
├── index.html          # Hauptspiel
└── README.md           # Diese Datei
```

## 📝 Lizenz

Dieses Projekt ist frei verfügbar. Nutze es für eigene Projekte!

## 🎨 Features

- ✨ Dynamische Partikeleffekte
- 🌟 Animierte Sterne
- 💥 Explosionen mit Screen-Shake
- 🎯 Verschiedene Waffentypen
- 👾 Verschiedene Monster-Typen mit HP-System
- 🌌 Schwarze Löcher mit Gravitation
- 🌀 Wurmlöcher als Level-Ziele
- 📊 Level-System mit steigendem Schwierigkeitsgrad

Viel Spaß beim Spielen! 🎮
