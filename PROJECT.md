# ProjectX – Projektübersicht

Single Source of Truth für Struktur, Gruppen und Aufgabenbereiche.

## Repository-Inhalt

| Datei | Beschreibung |
|-------|--------------|
| [`aufgaben.py`](aufgaben.py) | 100 Übungsfunktionen (Stubs mit Docstrings) |
| [`README.md`](README.md) | Anleitung für Studierende |

## Gruppenaufteilung (4 Gruppen, je 25 Aufgaben)

Zuordnung laut Board. Jede Gruppe hat zwei Personen.

| Gruppe | Personen | GitHub-Handles | Aufgaben |
|--------|----------|----------------|----------|
| 1 | Dennis, Linda | `dbudb`, `lindaEbbert` | `aufgabe_001` – `aufgabe_025` |
| 2 | Martin, Thorsten | `Harangason`, `ThorKel1202` | `aufgabe_026` – `aufgabe_050` |
| 3 | Marcel, Hans-Günter | `maro-101`, `HGKlemp` | `aufgabe_051` – `aufgabe_075` |
| 4 | Aylin, Jugo | `Aylin65`, `jugomit` | `aufgabe_076` – `aufgabe_100` |

## Branch-Schema

`gruppe-x/github-name/aufgabe-xxx` — ein Branch pro Aufgabe.

Beispiel: `gruppe-1/dbudb/aufgabe-001`

## Workflow

Siehe [`README.md`](README.md): Branch anlegen → Aufgabe implementieren → in `master`/`main` mergen (PR optional).

## Regeln für Studierende

- Nur den eigenen Aufgabenbereich in `aufgaben.py` bearbeiten.
- Gruppenkommentare (`# Gruppe: ...`) nicht ändern.
- Ein Branch und ein Merge pro Aufgabe.

## Änderungshistorie

- **2026-06-24**: 4 Gruppen mit neuen GitHub-Namen, 25 Aufgaben pro Gruppe, Branch pro Aufgabe. Siehe [ADR](.cursor/adr/0003-vier-gruppen-neue-namen.md).
- **2026-06-22**: Gruppenaufteilung nach Board. Siehe [ADR](.cursor/adr/0001-neue-gruppenaufteilung.md).
