---
titel: Termin-Aktualisierung Website
kategorie: website-pflege
version: 1.0
stand: 2026-04
autor: id-zemke.de
lizenz: CC BY-NC 4.0
---

# Termin-Aktualisierung Website

## Zweck
Erstellt einen fertig formatierten HTML-Terminblock für ein CMS – 
aus einfachen Stichpunkten.

## Deine Eingabe an Claude
```
Veranstaltung: [Name der Veranstaltung]
Datum: [TT.MM.JJJJ]
Uhrzeit: [HH:MM Uhr]
Ort: [Adresse oder Ortsangabe]
Zielgruppe: [Mitglieder / Öffentlich / Mannschaft etc.]
Anmeldung nötig: [Ja / Nein]
Kontakt: [Name, E-Mail oder Telefon – oder leer]
Hinweis: [Besondere Infos – oder leer lassen]
```

## Aufgabe für Claude

1. Erstelle einen HTML-Terminblock (kein html/body)
2. Erstelle einen kurzen Ankündigungstext (2 Sätze)
3. Optional: Social-Media-Kurzversion (max. 280 Zeichen)

## Regeln

- Datum immer ausgeschrieben: „Samstag, 12. April 2026"
- Uhrzeit mit Uhr: „14:00 Uhr"
- Bei Anmeldepflicht immer Kontakt prominent nennen
- Kein Fülltext, keine Floskeln

## Beispiel-Eingabe
```
Veranstaltung: Jahreshauptversammlung
Datum: 15.05.2026
Uhrzeit: 19:00 Uhr
Ort: Vereinsheim, Musterstraße 1, Gera
Zielgruppe: Alle Mitglieder
Anmeldung nötig: Nein
Kontakt: vorstand@verein.de
Hinweis: Wahl des neuen Vorstands
```

## Beispiel-Ausgabe

**HTML-Block:**
```html
<p class="datum">Donnerstag, 15. Mai 2026 · 19:00 Uhr</p>
<h2 class="ueberschrift">Jahreshauptversammlung 2026</h2>
<p>Alle Mitglieder sind herzlich eingeladen. 
Auf der Tagesordnung steht u.a. die Wahl des neuen Vorstands.</p>
<p><strong>Ort:</strong> Vereinsheim, Musterstraße 1, Gera</p>
<p><strong>Kontakt:</strong> vorstand@verein.de</p>
```
```

---

## Reihenfolge beim Anlegen
```
1. README.md                              ← zuerst, gibt dem Repo eine Startseite
2. redaktion/spielbericht-fussball.md     ← Unterordner wird automatisch angelegt
3. website-pflege/termin-aktualisierung.md
