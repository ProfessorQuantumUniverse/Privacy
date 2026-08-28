<div align="center">

# 🔒 Privacy Policies

### Zentrale Datenschutzerklärungen für meine Google-Play-Apps & Projekte.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![License](https://img.shields.io/badge/License-GPL%20v3-blue?style=for-the-badge)

[**🔗 Live Site**](https://privacy.lorenzobaymueller.me/)

</div>

---

Eine schlichte, statische Seite, die die Datenschutzerklärungen aller Apps bündelt, die unter dem
Google-Play-Entwicklernamen **Universe Lab** (Lorenzo Bay-Müller) veröffentlicht sind, und sie unter einer
eigenen Domain bereitstellt.

## 📄 Seiten

| URL | Inhalt |
| --- | --- |
| `/` | Sammel-Datenschutzerklärung für alle Apps (Englisch) |
| `/de/` | Sammel-Datenschutzerklärung für alle Apps (Deutsch) |
| `/apps/rereminder/` | reReminder (`com.olaf.rereminder`) |
| `/apps/gsearch14/` | Gsearch14 – Search without AI (`com.olafsapp.gsearch14`) |
| `/apps/phantaland-queue-times/` | Phantaland Queue Times (`com.quantum_prof.phantalandwaittimes`) |

Für den Play-Store-Eintrag kann entweder die Sammelseite (`https://privacy.lorenzobaymueller.me/`) oder die
app-spezifische Seite hinterlegt werden – beide nennen App-Titel, Paketname, Entwicklernamen und Rechtssubjekt
genau so, wie sie im Play-Eintrag stehen.

## ✅ Google-Play-Anforderungen

Google verlangt, dass die verlinkte Datenschutzerklärung die App **und** das im Play-Eintrag genannte
Rechtssubjekt eindeutig benennt. Jede Seite hier enthält deshalb oben einen Identitätsblock mit:

- Entwicklername laut Play-Eintrag: **Universe Lab**
- Kontoinhaber laut Play-Eintrag: **Theresa de Wet Bay Mueller**, Deutschland
- Entwickler/Autor: **Lorenzo Bay-Müller**
- Kontakt-E-Mail der Play-Einträge: **makerlab.fffm@gmail.com**
- exakter App-Titel und Anwendungs-ID (Paketname)

## ➕ Neue App hinzufügen

1. `apps/<slug>/index.html` anlegen (eine bestehende App-Seite als Vorlage kopieren).
2. App-Titel und Paketname **exakt** aus dem Play-Eintrag übernehmen.
3. Abschnitte 3–5 (lokale Daten, Internetverbindungen, Berechtigungen) an die App anpassen.
4. Die App in die Tabelle in `index.html` **und** `de/index.html` eintragen und dort einen `app-block` ergänzen.
5. Datum in der Fußzeile aller geänderten Seiten aktualisieren.

## 🛠️ Tech-Stack

`HTML5` · `CSS3` · `GitHub Pages` · eigene Domain via `CNAME`

---

<div align="center">

Teil meiner Projektsammlung · [**Alle Projekte ansehen →**](https://professorquantumuniverse.github.io/My-Projects/)

Made with ☕ & curiosity by **Lorenzo Bay-Müller** ([@ProfessorQuantumUniverse](https://github.com/ProfessorQuantumUniverse))

</div>
