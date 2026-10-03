# Vorlagen für den EU AI Act — Volltext

Dieses Dokument fasst das Repository in einem Stück zusammen.

## Das eigentliche Problem

Es fehlen keine Vorlagen. Es fehlt, dass dieselbe Angabe in allen Vorlagen dasselbe heißt und von einer Stelle kommt.

Ein typischer Verlauf: Das Inventar trägt eine Modellversion ein. Der Einstufungsbogen übernimmt sie — abgetippt. Der Anbieter wechselt, die Entwicklung aktualisiert das Inventar, die Einstufung bleibt stehen, und die technische Dokumentation nennt eine dritte Version, weil sie älter ist.

In einer Prüfung lautet der Befund dann nicht „eine Angabe ist falsch". Er lautet: **Die Organisation kann nicht sagen, welcher Stand in Betrieb war.** Das ist der schwerere Befund, und er entsteht nicht aus Nachlässigkeit, sondern aus dem Entwurf.

## Die Regel

> **Jede Angabe hat genau eine Quelle. Alle anderen Vorlagen verweisen darauf.**

Verweisen heißt: Die Angabe wird nicht abgetippt, sondern über eine Kennung adressiert — ein Link in Markdown, eine Verknüpfung in einer Fachanwendung, wenigstens eine Spalte mit der Kennung des Quelldatensatzes.

Fünf Angaben werden in der Praxis mehrfach gepflegt und sind deshalb die kritischen: **Einsatzzweck** und **Betroffenenkreis** (Quelle: Inventar), **Modell und Version** (Inventar, aus Anbieterangaben), **rechtliche Klasse** (Einstufungsbogen) und der **Verantwortliche** (Inventar). Wer diese fünf durchhält, hat das meiste gewonnen.

Dazu gehören Namenskonventionen, die unglamouröse Hälfte: „Zweck" allein ist kein Feldname, weil Zweckbestimmung des Anbieters und eigener Einsatzzweck zwei Felder sind. „Risiko" allein ist keiner, weil rechtliche Klasse und interne Risikoeinschätzung zwei Felder sind — und zwar zwei, die nie zusammengelegt werden dürfen: Ein System kann rechtlich minimal und betrieblich riskant sein.

## Die vier Schichten

Register (was es gibt) → Bewertung (wie es eingeordnet wird) → Nachweis (womit es belegt wird) → Prüfung (ob der Zustand steht). Jede Schicht verwendet Angaben der darüberliegenden und erzeugt eigene. Eine Vorlage, die Angaben der Registerschicht neu abfragt, ist falsch geschnitten.

## Die Aufbaureihenfolge

Inventareintrag; dann Praktikenprüfung nach Art. 5; dann Kennzeichnungsnachweis nach Art. 50; dann Schulungsnachweis nach Art. 4; dann Einstufungsbogen, Nachweisregister, Prüflisten; und Anhang IV nur bei Hochrisiko und Anbieterrolle.

Die Positionen zwei bis vier stehen bewusst vor der Einstufung. Sie brauchen keine Risikoklasse, sie sind seit Februar 2025 bzw. August 2026 anwendbar, und sie sind in zwei Tagen erledigt. Wer mit der Einstufung beginnt, verschiebt sie auf unbestimmt — und das ist die Lage, in der die meisten Organisationen sind: Die Aufmerksamkeit liegt bei Anhang IV, das erst ab 2.12.2027 gilt.

Die Praktikenprüfung steht direkt nach dem Inventar, weil ein Treffer alles Weitere gegenstandslos macht.

## Die drei Vorlagen für das, was heute gilt

**Praktikenprüfung** (Art. 5, seit 2.2.2025): zehn Zeilen mit Ergebnis und Datum. Besonders zu prüfen sind die zwei, die in gekaufter Software vorkommen — Emotionserkennung am Arbeitsplatz und in Bildungseinrichtungen, und ungezieltes Auslesen von Gesichtsbildern. Bei Nr. 6 ist die Unterscheidung wesentlich: Analyse von Kundentexten ist nicht erfasst, Bewertung von Beschäftigten oder Lernenden schon.

**Schulungsnachweis** (Art. 4, seit 2.2.2025): Teilnahmeliste mit Datum **und Inhalt**. Eine Liste ohne Inhaltsangabe belegt Anwesenheit, nicht Kompetenz. Und eine Schulung, die erklärt, wie das alte Modell irrt, passt nach einem Modellwechsel nicht mehr.

**Kennzeichnungsnachweis** (Art. 50, seit 2.8.2026): je Fall und **je Ansicht** — Desktop, Mobil, eingebettet, Benachrichtigungen. Die Mobilansicht ist der häufigste Einzelfehler. Nachweis mit Datum **und Produktversion**; ohne Version belegt eine Bildschirmaufnahme nur, dass es einmal so aussah.

Alle drei liegen im Kernbündel dieses Repositories, weil sie in keiner anderen Sammlung des Netzes stehen.

## Was eine Vorlage brauchbar macht

Ausfüllbar ohne Beratungsgespräch. Je Feld eine Begründung, wofür es gebraucht wird. „Nicht bewertet" zulässig, mit Person und Termin. Versionierbar.

Die zweite Eigenschaft lässt am meisten weg: Ein Feld ohne Begründung wird nicht gepflegt, und ein Register mit vierzig Feldern, von denen zwölf gefüllt sind, ist schlechter als eines mit achtzehn, die stimmen.

Die wichtigste Zahl im ganzen Repository: **acht Felder** im Aufnahmeformular für den Fachbereich. Vierzig werden umgangen, und dann entsteht genau das, was das Register verhindern soll.

## Was bewusst weggelassen ist

Eine KI-Richtlinie — sie regelt einen unbekannten Bestand und kommt nach dem Register, nicht davor. Beispieltexte für Dokumentationsabschnitte — sie werden abgeschrieben, und abgeschriebene Abschnitte fallen in einer Prüfung als Füllsätze auf. Ein Reifegradmodell — es misst, wie viel erfasst ist, nicht wie richtig es ist. Eine Mustererklärung über AI-Act-Konformität — Konformität bezieht sich auf ein System in einer Verwendung, nicht auf ein Unternehmen.

## Pflege

Vorlagen veralten anders als Register: nicht, weil Werte falsch werden, sondern weil die Rechtslage sich bewegt und Felder sich als unbrauchbar erweisen.

Die wertvollste Quelle für Vorlagenarbeit entsteht nach einer Prüfung: aufschreiben, **was gefragt wurde** — und daraus Feldänderungen ableiten. Die zweitwertvollste ist die Rückmeldung aus dem Fachbereich, dass ein Feld nicht ausfüllbar ist. Ein Feld, das dreimal leer blieb, ist kein Disziplinproblem.

Bei einer Änderung: Vorlagenversion hochsetzen, bestehende Einträge **nicht** rückwirkend ändern, und das neue Feld in bestehenden Einträgen als „nicht bewertet" markieren — sonst entsteht ein Register, in dem alte und neue Einträge unterschiedlich vollständig sind und niemand sieht, welche.

## Vier Abfragen, die Widersprüche finden

Einstufungen mit anderer Modellversion als das Inventar; Einstufungen ohne Verweis auf einen Inventareintrag; **Inventareinträge ohne Einstufung und ohne „nicht bewertet"**; Nachweise, deren Version nicht in der Änderungstabelle vorkommt.

Die dritte ist die schnellste und beantwortet, wie groß die offene Menge wirklich ist.

## Weg durch das Repository

1. [Feldkonsistenz](./knowledge-base/eu-ai-act/field-consistency-logic.md) — die Regel und das Feldverzeichnis
2. [Das Vorlagensystem](./knowledge-base/eu-ai-act/template-system-logic.md) — Schichten, Reihenfolge, Weglassungen
3. [Vorlagenkarte](./templates/template-map.md) — welche Vorlage für welche Pflicht, nach Pflicht, Rolle und Zuständigkeit
4. [Kernbündel](./templates/core-template-bundle.md) — die drei heute fälligen Vorlagen plus Nachweisregister
5. [Pflege](./knowledge-base/eu-ai-act/inventory-and-governance.md) — Rechtsstand, Änderungen, Ablage
6. [Prüfliste](./checklist.md) — taugt das System?

---

Keine Rechtsberatung. Stand: Oktober 2026.
