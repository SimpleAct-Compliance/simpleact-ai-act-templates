# Klassen und Vorlagen

Welche Vorlage je Klasse nötig ist — und welche Vorlage die Klasse überhaupt feststellt.

## Die Klasse stellt der Einstufungsbogen fest

Nicht eine Prüfliste, nicht die Dokumentation. Der Einstufungsbogen liegt in der [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) und arbeitet in dieser Reihenfolge:

```
  1 KI-System?        Art. 3 Nr. 1
  2 Ausnahme?         Art. 2
  3 Verboten?         Art. 5    <- Treffer beendet alles
  4 Hochrisiko?       Anhang I / III
  5 Transparenz?      Art. 50   <- unabhängig von 4
```

**Für das Vorlagensystem folgt daraus eine Besonderheit:** Die Prüfung nach Art. 5 steht so früh, dass sie eine **eigene Vorlage** verdient — die [Praktikenprüfung](../../templates/core-template-bundle.md). Sie braucht keine Klasse, ist seit 2.2.2025 anwendbar, und ein Treffer macht alle weiteren Vorlagen gegenstandslos.

## Welche Vorlagen je Klasse

| Klasse | Vorlagen |
|---|---|
| **Verboten** | Praktikenprüfung mit Treffer, plus Entscheidungsdokumentation: Betrieb eingestellt, durch wen, wann, Alternativen geprüft |
| **Hochrisiko, Anbieter** | alles aus minimal, plus Anhang IV, Risikomanagement, Qualitätsmanagement, Betriebsanleitung, Konformitätserklärung, Art.-72-Bericht, Meldevorlage Art. 73 |
| **Hochrisiko, Betreiber** | alles aus minimal, plus Protokollführung, Freigabeprüfung, ggf. Grundrechte-Folgenabschätzung nach Art. 27 |
| **Transparenzpflicht** | alles aus minimal, plus Kennzeichnungsnachweis |
| **Minimal** | Inventareintrag, Praktikenprüfung, Schulungsnachweis, Einstufungsbogen, Wiedervorlage |

Die erste Zeile wird übersehen. Ein Werkzeug abzuschalten ist die richtige Reaktion auf einen Art.-5-Treffer — und ohne Dokumentation ist später nicht erkennbar, dass eine Prüfung stattgefunden und zu einer Entscheidung geführt hat.

## Art. 50 ist keine Klasse, sondern eine Zusatzebene

Deshalb steht der Kennzeichnungsnachweis in jeder Zeile der Tabelle, in der er greift — auch bei Hochrisiko. Ein Hochrisikosystem mit Chatfunktion braucht Anhang IV **und** den Kennzeichnungsnachweis.

Für die Vorlagenarbeit ist das wichtig, weil Vorlagensammlungen Art. 50 häufig als unterste Stufe behandeln und damit nur Systemen mit minimalem Risiko zuordnen.

## Die Ausnahme nach Art. 6 Abs. 3 braucht ein Dokument

Wer sich darauf beruft, hat nicht weniger zu dokumentieren, sondern **anderes**: statt Anhang IV eine nachvollziehbare Bewertung, warum die Ausnahme trägt.

Was sie enthalten muss:

| Feld | Inhalt |
|---|---|
| welcher der vier Tatbestände | eng begrenzte Verfahrensaufgabe / Verbesserung eines menschlichen Ergebnisses / Mustererkennung ohne Ersetzen der Bewertung / vorbereitende Tätigkeit |
| Begründung | konkret, bezogen auf diesen Einsatzzweck |
| **Wird profiliert?** | ein Ja schließt die Ausnahme aus, unabhängig von allem anderen |
| **Übernahmequote**, falls Mustererkennung | gemessen, nicht geschätzt |
| bewertet durch, Datum | Person |

Die dritte Zeile steht in der Verordnung nach der Aufzählung der Tatbestände und wird beim Lesen oft übersprungen. In der Vorlage steht sie deshalb als eigene Zeile, nicht als Unterpunkt.

Die vierte Zeile entscheidet den dritten Tatbestand: Wird ein Vorschlag in 98 von 100 Fällen übernommen, ersetzt er die menschliche Bewertung praktisch.

## Was in jeder Klasse gleich ist

| Vorlage | Warum klassenunabhängig |
|---|---|
| Inventareintrag | Voraussetzung für die Einstufung selbst |
| Praktikenprüfung (Art. 5) | anwendbar seit 2.2.2025, keine Klasse nötig |
| Schulungsnachweis (Art. 4) | anwendbar seit 2.2.2025, keine Klasse nötig |
| Auslöserliste | jede Einstufung kann veralten |
| Nachweisregister | verbindet Pflichten mit Belegen, welche auch immer |

Diese fünf werden gebraucht, bevor die Klasse feststeht. Das ist der Grund für die Aufbaureihenfolge in [template-system-logic.md](./template-system-logic.md).

## GPAI erzeugt eine Beschaffungsvorlage, keine eigene Klasse

Pflichten für Modelle mit allgemeinem Verwendungszweck treffen den **Modellanbieter**. Für Betreiber folgt daraus keine eigene Vorlage, sondern ein Abschnitt im **Anbieterfragebogen**: Welche GPAI-Dokumentation stellt er bereit, und wo steht das?

Ein Nein gehört als Befund gegen den Anbieter dokumentiert — mit Datum der Anfrage.

## Weiter

[Welche Vorlage für welche Rolle](./scope-and-actors.md) · [Vorlagenkarte](../../templates/template-map.md)
