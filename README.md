# 🚗 FL-FZV - Fahrzeug-Zulassungsverordnung Editor

**Fahrlehrer-Ausbildung FL-BE_07/25**  
Justin Lee Probis

---

## 📚 Über dieses Repository

Dieses Repository enthält die Daten für den **FZV Editor** - ein professionelles Werkzeug zur systematischen Aufbereitung der Fahrzeug-Zulassungsverordnung (FZV) für die Fahrlehrer-Ausbildung.

Der Editor ermöglicht die strukturierte Erfassung von Gesetzestexten zu Zulassungsverfahren, Fahrzeugpapieren, Kennzeichen, Praxisbeispielen und deren Synchronisation über GitHub.

---

## 📂 Repository-Struktur

```
FL-FZV/
├── README.md       (diese Datei - Projektbeschreibung)
└── data.json       (FZV-Daten, automatisch synchronisiert vom Editor)
```

---

## 🔄 Daten-Synchronisation

Die Datei `data.json` wird **automatisch** vom FZV Editor synchronisiert:

- ✅ Jedes Speichern im Editor aktualisiert diese Datei
- ✅ Änderungen werden mit Zeitstempel versioniert
- ✅ Team-Kollaboration möglich (mehrere Nutzer, ein Repository)

**⚠️ WICHTIG:** Die `data.json` sollte **nicht manuell bearbeitet** werden!  
Alle Änderungen bitte nur über den FZV Editor vornehmen.

---

## 🛠️ Verwendung

### 1. Repository-Setup (einmalig)
- Repository erstellt: ✅ `710Deckel/FL-FZV`
- README.md hochgeladen: ✅

### 2. Editor-Verwendung
- HTML-Datei lokal öffnen (`fzv-editor.html`)
- GitHub Token eingeben (einmalig, gleicher Token wie andere Tools!)
- Paragraphen hinzufügen und speichern
- Automatische Synchronisation erfolgt

### 3. Token-Anforderungen
Der verwendete Token benötigt folgende Berechtigungen:
- ✅ `repo` (Full control of private repositories)

**Hinweis:** Du kannst denselben Token für alle Fahrlehrer-Tools verwenden!

---

## 📋 Datenstruktur

Die `data.json` enthält alle FZV-Paragraphen im folgenden Format:

```json
{
  "paragraphen": [
    {
      "id": "timestamp",
      "gesetz": "FZV",
      "nummer": "§ 3",
      "titel": "Zulassungsverfahren",
      "gesetzestext": "...",
      "quelle": "https://...",
      "praxisbeispiele": [
        {
          "titel": "Beispiel",
          "klasse": "ALLE",
          "beschreibung": "...",
          "wichtigkeit": "HIGH"
        }
      ]
    }
  ]
}
```

---

## 🎯 Features des Editors

- **2-Spalten-Layout:** Gesetzestext | Praxisbeispiele
- **GitHub Auto-Sync:** Automatische Synchronisation
- **Template-System:** Vordefinierte Beispiele für Zulassungsverfahren, Fahrzeugpapiere
- **Badge-System:** CRITICAL (rot) | HIGH (orange) | BANAL (grün)
- **PDF-Export:** Professionelle Druckausgabe
- **Import/Export:** JSON-Backup-System
- **Keyboard Shortcuts:** Strg+S zum Speichern
- **Cyan Theme:** Speziell für Zulassungsthemen

---

## 🚗 Wichtige FZV-Bereiche

Der Editor deckt alle wichtigen Bereiche der Fahrzeug-Zulassungsverordnung ab:

- **§ 3 - Zulassungsverfahren:** Erst-, Um-, Wiederzulassung
- **§ 11 - Zulassungsbescheinigung Teil I:** Fahrzeugschein, Mitführpflicht
- **§ 12 - Zulassungsbescheinigung Teil II:** Fahrzeugbrief, Eigentumsnachweis
- **§ 16 - Kennzeichen:** Nummernschild, Beschaffenheit, Anbringung
- **§ 27 - Außerbetriebsetzung:** Stilllegung, Abmeldung
- **§ 16a - Wechselkennzeichen**
- **§ 42 - Kurzzeitkennzeichen**

---

## 🔗 Weitere Fahrlehrer-Tools

Dieses Repository ist Teil einer systematischen Tool-Suite für die Fahrlehrer-Ausbildung:

- [📘 FL-StVO](https://github.com/710Deckel/stvo-teleprompter) - StVO Teleprompter mit Erläuterungen
- [🚛 FL-FPersV-EG-VO](https://github.com/710Deckel/FL-FPersV-EG-VO) - Fahrpersonalverordnung & EU-Verordnung
- [⚖️ FL-StVG](https://github.com/710Deckel/FL-StVG) - Straßenverkehrsgesetz
- [🔧 FL-StVZO](https://github.com/710Deckel/FL-StVZO) - Straßenverkehrs-Zulassungs-Ordnung
- [📋 FL-FeV](https://github.com/710Deckel/FL-FeV) - Fahrerlaubnis-Verordnung
- [🚗 FL-FZV](https://github.com/710Deckel/FL-FZV) - Fahrzeug-Zulassungsverordnung (dieses Repository)

---

## 📝 Lizenz & Verwendung

**Projekt:** Fahrlehrer-Ausbildung FL-BE_07/25  
**Ersteller:** Justin Lee Probis  
**Zweck:** Ausbildung und Podcast "Fahrlehrer Inside"

Dieses Tool und die Daten sind für **Ausbildungszwecke** erstellt.

---

## 📞 Kontakt & Feedback

Bei Fragen, Problemen oder Verbesserungsvorschlägen:
- GitHub Issues in diesem Repository
- Feedback über das Tool (Thumbs Down Button)

---

**Erstellt mit ❤️ für die Fahrlehrer-Ausbildung**

*Letzte Aktualisierung: Dezember 2024*
