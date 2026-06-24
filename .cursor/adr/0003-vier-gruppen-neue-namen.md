# ADR 0003: Vier Gruppen mit neuen GitHub-Namen

## Status

Angenommen (2026-06-24)

## Kontext

Die Gruppenaufteilung wurde vom Whiteboard aktualisiert: 4 Gruppen mit je 2
Personen (8 Studierende). Die bisherige 5-Gruppen-Aufteilung (je 20 Aufgaben)
entspricht nicht mehr dem Kurs-Setup.

## Entscheidung

- **4 Gruppen**, je **25 Aufgaben** (100 Aufgaben gesamt).
- Gruppen und GitHub-Namen:
  - Gruppe 1: `dbudb`, `lindaEbbert` (Aufgaben 001–025)
  - Gruppe 2: `Harangason`, `ThorKel1202` (Aufgaben 026–050)
  - Gruppe 3: `maro-101`, `HGKlemp` (Aufgaben 051–075)
  - Gruppe 4: `Aylin65`, `jugomit` (Aufgaben 076–100)
- Branch-Schema: `gruppe-x/github-name/aufgabe-xxx` (ein Branch pro Aufgabe).
- Merge in `master`/`main` als Standard; Pull Request optional.

## Konsequenzen

- `aufgaben.py`: Gruppenkommentare über jeder Funktion aktualisiert.
- `README.md` und `PROJECT.md`: Gruppenliste, Workflow und Beispiele angepasst.
