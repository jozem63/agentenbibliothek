---
titel: Spielbericht Fußball
kategorie: redaktion
version: 1.0
stand: 2026-04
autor: id-zemke.de
lizenz: CC BY-NC 4.0
---

# Spielbericht Fußball

## Zweck
Erstellt einen fertig formatierten HTML-Spielbericht für ein CMS 
auf Basis weniger Stichpunkte.

## Deine Eingabe an Claude
```
Datum: [TT.MM.JJJJ]
Paarung: [Heimteam] – [Auswärtsteam]
Ergebnis: [X:X]
Torschützen: [Name (Minute), Name (Minute)]
Besonderheiten: [Platzverweise, Zuschauer, Wetter o.ä. – oder leer lassen]
Vereinsfarben/Stil: [neutral / heimstark / kämpferisch]
```

## Aufgabe für Claude

1. Erstelle eine Schlagzeile (max. 70 Zeichen)
2. Schreibe zwei journalistische Sätze als Einleitung
3. Gib einen vollständigen HTML-Block aus (keine html/body-Tags)
4. Erstelle einen CMS-Teasertext (max. 200 Zeichen, Plaintext)

## Regeln

- Neutrale, sachliche Sprache – kein Vereinsjargon
- Ergebnisse immer als Zahl:Zahl (nie ausgeschrieben)
- Torschützen in chronologischer Reihenfolge
- Keine Wertung oder Spekulation über Schiedsrichter-Entscheidungen
- HTML-Ausgabe ohne `<html>`, `<head>` oder `<body>`-Tags

## Beispiel-Eingabe
```
Datum: 29.03.2026
Paarung: BSG Wismut Gera – SV Musterstadt
Ergebnis: 3:1
Torschützen: Müller (12.), Schneider (34., 67.)
Besonderheiten: 320 Zuschauer
```

## Beispiel-Ausgabe

**Schlagzeile:** Wismut Gera siegt verdient mit 3:1 gegen Musterstadt

**Einleitung:** Vor 320 Zuschauern setzte sich BSG Wismut Gera klar 
mit 3:1 gegen den SV Musterstadt durch. Müller und Schneider 
(zweimal) sorgten für einen verdienten Heimsieg.

**HTML-Block:**
```html
<p class="datum">29. März 2026</p>
<h2 class="ueberschrift">Wismut Gera siegt verdient mit 3:1 gegen Musterstadt</h2>
<p>Vor 320 Zuschauern setzte sich BSG Wismut Gera klar mit 3:1 
gegen den SV Musterstadt durch. Müller und Schneider sorgten 
für einen verdienten Heimsieg.</p>
```

**Teasertext:** Heimsieg für Wismut Gera! Vor 320 Zuschauern gewann 
die BSG verdient mit 3:1 gegen den SV Musterstadt.
