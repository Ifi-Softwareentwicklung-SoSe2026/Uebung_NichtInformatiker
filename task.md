# KI-Bewertung -- Aufgabe 03

<!-- agent-assignment-part:{"kind":"python","required_checks":["workflow:.github/workflows/python-run.yml"]} -->

## Aufgabenbeschreibung

Die Studierenden implementieren in `aufgabe.py` ein Python-Programm zur
Verwaltung und Sortierung von Bohrkernproben. Das Programm soll in klar
getrennte Funktionen gegliedert sein und aus einer `main()`-Funktion
heraus gesteuert werden.

Die Aufgabe umfasst: 1. Initialisierung einer Liste von Bohrkernproben
als Tupel. 2. Berechnung der durchschnittlichen Dichte mit NumPy. 3.
Implementierung eines Bubble-Sort-Algorithmus zur Sortierung nach Dichte
(optional mit Rückgabe der Anzahl der Vertauschungen). 4. Formatierte
Ausgabe der sortierten Daten mit `enumerate()` und f-Strings. 5.
Visualisierung der Dichteverteilung mit Matplotlib als Balkendiagramm.
6. Aufbau eines Dictionaries zur Suche nach Proben anhand ihrer Dichte
sowie eine interaktive Benutzereingabe über `input()`.

Neben der Programmlogik wird auf eine saubere funktionale Struktur und
den GitHub-Workflow (Branch, Pull Request, Review) Wert gelegt.

## Akzeptanzkriterien

### Programmstruktur

-   [ ] Das Programm befindet sich in `aufgabe.py`.
-   [ ] Eine `main()`-Funktion existiert und steuert den Programmablauf.
-   [ ] Jede Teilaufgabe ist in einer eigenen Funktion implementiert.
-   [ ] Das Programm lässt sich ohne Fehler mit `python aufgabe.py`
    ausführen.

### Datenmodell

-   [ ] Die Bohrkernproben werden als Liste von Tupeln angelegt.
-   [ ] Jedes Tupel enthält ID, Name, Dichte und Tiefe.

### Durchschnittliche Dichte

-   [ ] NumPy wird importiert.
-   [ ] Die Dichten werden in ein NumPy-Array überführt.
-   [ ] Die durchschnittliche Dichte wird mit `np.mean()` berechnet.

### Bubble Sort

-   [ ] Eine Funktion `bubble_sort(proben)` ist implementiert.
-   [ ] Die Liste wird aufsteigend nach der Dichte sortiert.
-   [ ] Es werden ausschließlich benachbarte Elemente vertauscht.
-   [ ] Der Algorithmus beendet sich, sobald kein Tausch mehr notwendig
    ist.
-   [ ] (Bonus) Die Funktion liefert zusätzlich die Anzahl der
    Vertauschungen zurück.

### Ausgabe

-   [ ] Die sortierten Proben werden formatiert mit f-Strings
    ausgegeben.
-   [ ] `enumerate()` wird zur Positionsnummerierung verwendet.

### Visualisierung

-   [ ] Es wird ein Balkendiagramm mit Matplotlib erzeugt.
-   [ ] Die X-Achse zeigt die Probennamen.
-   [ ] Die Y-Achse zeigt die Dichte.
-   [ ] Der Plot besitzt einen aussagekräftigen Titel.
-   [ ] Die X-Beschriftungen sind lesbar (z. B. Rotation).

### Interaktive Suche

-   [ ] Ein Dictionary ordnet jeder Dichte die zugehörigen Probennamen
    zu.
-   [ ] Die Benutzereingabe erfolgt über `input()`.
-   [ ] Vorhandene Dichten liefern alle passenden Proben.
-   [ ] Nicht vorhandene Dichten werden sinnvoll behandelt.

### GitHub-Workflow

-   [ ] Die Entwicklung erfolgt auf einem separaten Branch.
-   [ ] Es existieren nachvollziehbare Commits.
-   [ ] Ein Pull Request wurde erstellt.
-   [ ] Review-Kommentare wurden eingearbeitet.
