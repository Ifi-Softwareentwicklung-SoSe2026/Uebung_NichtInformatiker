<!--
author:   Volker Göhler
version:  0.1.0
language: de
narrator: Deutsch Female
edit: true
comment:  Übung Python für Nicht-Informatiker
-->

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/Ifi-Softwareentwicklung-SoSe2026/Uebung_NichtInformatiker/refs/heads/main/README.md)

> Hinweis: Der Badge-Link zeigt auf den Branch `main`. Für andere Branches einfach `refs/heads/main` in der URL durch `refs/heads/<branch-name>` ersetzen.

# Aufgabe 03 – Python für Nicht-Informatiker

Softwareentwicklung SoSe2026
============================

## Lernziele dieser Übung

In dieser Übung bearbeitest du ein durchgehendes Python-Szenario zur Auswertung einfacher Missions- und Messdaten. Dabei sollen folgende Inhalte aktiv genutzt werden:

- Operationen (`+`, `-`, `*`, `/`, `%`, `**`, logische Operatoren wie `and`/`or`)
- `type()`
- `input()`
- `if`, `elif`, `else`
- `while`, `for` mit `in range(...)`
- Listen inklusive `zip()`, `enumerate()`, `split("-")`, `liste.index(element)`
- Dictionaries inklusive `element in dictionary`
- Tupel
- Funktionen/Methoden (auch mit zwei Rückgabewerten)
- Libraries verwenden (`import ...`)
- NumPy: Arrays, `loadtxt`, `reshape`, `linspace`, `arange`
- Matplotlib (`matplotlib.pyplot`) für einfache Plots

## 📌 Vorbereitung

1. Arbeite in deinem GitHub-Classroom-Repository.
2. Lege einen Branch `integration` an.
3. Erstelle für jede Teilaufgabe kleine, nachvollziehbare Commits.

## 🛠️ Aufgabe 0: Git und GitHub kennenlernen

### Dimensionen

| Dimension | Werkzeuge & Features |
|-----------|----------------------|
| **Lokal** (VS Code + Git) | clone, add/stage, commit, branch/switch, merge, Konflikte lösen |
| **Remote** (GitHub) | push/pull, Pull Requests, Review-Kommentare einarbeiten, Issues |

### 🔧 Lokale Git-Arbeit (kurz)

1. Repository klonen
2. Branch `integration` erstellen
3. Änderungen committen (aussagekräftige Commit-Message)
4. Branch pushen und Pull Request öffnen

### 🌐 Neue Sektion: **Nur GitHub im Webportal (Remote-only)**

Diese Variante nutzt **kein lokales Git**. Alles passiert direkt auf github.com.

1. Öffne dein Repository im Browser.
2. Erstelle über die Branch-Auswahl einen neuen Branch (z. B. `webportal-edit`).
3. Öffne eine Datei und nutze den Web-Editor (Stift-Symbol), um Änderungen vorzunehmen.
4. Committe direkt im Browser auf deinen Branch.
5. Erstelle über **Contribute → Open pull request** einen PR nach `main`.
6. Reagiere auf Review-Kommentare direkt im PR (Antworten + neue Web-Commits).
7. Merge den PR nach Freigabe.

## 🚀 Aufgabe 1: Missionsdaten interaktiv auswerten

### Teil A – Grundlagen

- Lies über `input()` Name und Anzahl von Messwerten ein.
- Prüfe Datentypen mit `type()`.
- Nutze Rechenoperatoren inkl. `%` und `**`.
- Verwende `if/elif/else`, um Messwerte in Klassen einzuteilen.

### Teil B – Schleifen

- Erzeuge mit `for i in range(...)` Testdaten.
- Nutze eine `while`-Schleife für Benutzereingaben bis zu einem Stop-Kriterium.

### Teil C – Listen, Tupel, Dictionaries

- Zerlege Datumseinträge wie `"2026-06-01"` mit `split("-")`.
- Nutze `enumerate()` für indexierte Ausgaben.
- Kombiniere zwei Listen mit `zip()`.
- Finde Positionen mit `liste.index(element)`.
- Speichere feste Messpunktkoordinaten als Tupel.
- Nutze ein Dictionary für Sensorname → letzter Messwert und prüfe mit `in`, ob ein Sensor existiert.

### Teil D – Funktionen und Libraries

- Schreibe mindestens eine Funktion mit **zwei Rückgabewerten** (z. B. Mittelwert und Maximum).
- Verwende mindestens eine Standardbibliothek (`math`, `random`, `statistics` o. ä.).

### Teil E – NumPy & Matplotlib

- Erstelle NumPy-Arrays aus Messwerten.
- Lade Daten aus Datei mit `np.loadtxt(...)`.
- Forme Daten mit `reshape(...)` um.
- Erzeuge Testachsen mit `np.linspace(...)` und `np.arange(...)`.
- Visualisiere mindestens zwei Kurven mit `matplotlib.pyplot` (`plot`, `title`, `xlabel`, `ylabel`, `legend`).

## ✅ Akzeptanzkriterien

- Alle oben genannten Python-Inhalte sind im Code sichtbar verwendet.
- Der Code läuft ohne Fehler.
- Es gibt mindestens einen Plot mit beschrifteten Achsen.
- Der Workflow mit Pull Request und Review ist dokumentiert bzw. durchgeführt.
