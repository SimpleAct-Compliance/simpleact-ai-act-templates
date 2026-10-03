# Feldkonsistenz

Vier Register, die dieselbe Angabe führen, sind nach einem halben Jahr vier Register mit drei verschiedenen Werten. Das ist kein Sorgfaltsproblem, sondern ein Entwurfsproblem.

## Die Regel

> **Jede Angabe hat genau eine Quelle. Alle anderen Vorlagen verweisen darauf.**

Verweisen heißt: Die Angabe wird nicht abgetippt, sondern über eine Kennung adressiert. In Markdown ist das ein Link, in einer Fachanwendung eine Verknüpfung, in einer Tabelle wenigstens eine Spalte mit der Kennung des Quelldatensatzes.

## Das Feldverzeichnis

| Angabe | Quelle | Wer pflegt | Wird verwendet in |
|---|---|---|---|
| Kennung | Inventar | Inventarpflege | allen |
| **Einsatzzweck** | Inventar | Eigentümer im Fachbereich | Einstufung, Dokumentation, Prüfungen, DSFA |
| Werkzeug, Anbieter | Inventar | Eigentümer | Anbieterregister, Dokumentation |
| **Modell und Version** | Inventar, aus Anbieterangaben | Entwicklung oder IT | Einstufung, Dokumentation, Vorfall, Testsatz |
| Datenarten | Inventar | Eigentümer, mit Datenschutz | Verarbeitungsverzeichnis, DSFA, Einstufung |
| **Betroffenenkreis** | Inventar | Eigentümer | Einstufung, DSFA, Art.-27-Prüfung, Vorfall |
| berührter Anhang-III-Bereich | Inventar | Eigentümer | Einstufung, Rollenfrage |
| Rolle (Anbieter/Betreiber) | Einstufung | Compliance | Dokumentation, Prüflisten |
| **rechtliche Klasse** | Einstufungsbogen | Compliance | Prüflisten, Dokumentation, Pflichtenzuweisung |
| interne Risikoeinschätzung | Einstufungsbogen | Compliance mit Fachbereich | Priorisierung |
| Aufsichtsangaben | Inventar | Fachbereich | Einstufung, Dokumentation, Prüfung |
| **Verantwortlicher** | Inventar | Leitung | allen |
| Nachweise | Nachweisregister | je Pflicht | Prüfungen, Dokumentation, Audit |

Die fünf hervorgehobenen Zeilen sind die, die in der Praxis mehrfach gepflegt werden. Sie sind gleichzeitig die, deren Widerspruch in einer Prüfung am schnellsten auffällt.

## Die Wanderung, die nicht stattfinden darf

Ein typischer Verlauf, der zu Widersprüchen führt:

1. Das Inventar trägt „Modell: Anbietermodell, Version 4.1".
2. Die Einstufung wird geschrieben und übernimmt den Wert — abgetippt.
3. Der Anbieter wechselt auf 4.2. Die Entwicklung aktualisiert das Inventar.
4. Die Einstufung sagt weiterhin 4.1.
5. Die technische Dokumentation sagt 4.0, weil sie älter ist.

In einer Prüfung ist der Befund nicht „die Version ist falsch", sondern: **Die Organisation kann nicht sagen, welche Version in Betrieb war.** Das ist der schwerere Befund.

Was es verhindert: Die Einstufung enthält keine Versionsangabe, sondern einen Verweis auf den Inventareintrag — und die technische Dokumentation führt die Version in ihrer eigenen Änderungstabelle, weil **dort** die Frage „was lief wann" beantwortet wird.

## Was in jeder Vorlage verweisen, nicht wiederholen sollte

| In dieser Vorlage | nicht wiederholen | sondern verweisen auf |
|---|---|---|
| Einstufungsbogen | Modellversion, Datenarten, Anbieter | Inventareintrag |
| Prüflisten | Klasse, Rechtsgrundlage | Einstufungsbogen |
| technische Dokumentation | Einsatzzweck, Betroffenenkreis | Inventareintrag |
| Vorfallmeldung | alles außer dem Vorfall selbst | Inventar, Einstufung |
| DSFA | Datenarten, Zweck, Empfänger | Verarbeitungsverzeichnis |
| Verarbeitungsverzeichnis | Modell, Anbieter | Inventar, Anbieterregister |

Die vierte Zeile ist besonders wichtig: Eine Vorfallmeldung, die das System neu beschreibt, kostet im Vorfall Zeit, die niemand hat — und sie beschreibt es dann aus der Erinnerung.

## Namenskonventionen

Weniger glamourös als die Regel oben, und in der Praxis genauso wirksam. Dreimal dasselbe Feld unter drei Namen ist dreimal dasselbe Feld, das niemand zusammenführt:

| Gut | Vermeiden |
|---|---|
| Einsatzzweck | Zweck, Verwendung, Use Case, Anwendungsfall |
| Modell und Version | Modell, KI-Modell, Engine, Version |
| rechtliche Klasse | Risikoklasse, Einstufung, Risiko, Kategorie |
| interne Risikoeinschätzung | internes Risiko, Risikobewertung |
| Betroffenenkreis | Betroffene, Zielgruppe, Nutzer |
| Eigentümer | Verantwortlicher, Owner, Ansprechpartner |

Besonders die dritte und vierte Zeile: „Risiko" allein ist kein Feldname, weil nicht erkennbar ist, welches der beiden Risikofelder gemeint ist.

## Die zwei Felder, die nie zusammengelegt werden dürfen

**Rechtliche Klasse** und **interne Risikoeinschätzung**. Ein System kann rechtlich minimal und betrieblich riskant sein — ein Werkzeug, das Angebotstexte erzeugt, berührt keine Pflicht und kostet bei Halluzinationen Geld.

In einer Spalte vermengt, entsteht eines von zwei Ergebnissen: Überregulierung, weil das betriebliche Risiko rechtliche Pflichten auslöst, die nicht bestehen; oder eine Lücke, weil ein rechtlich riskantes System als betrieblich unkritisch durchgeht.

## Wie man Widersprüche findet

Vier Abfragen, die sich in jeder Umgebung durchführen lassen — auch in Tabellen:

| Prüfung | Findet |
|---|---|
| Einträge, deren Einstufung eine andere Version nennt als das Inventar | abgetippte Felder |
| Einstufungen ohne Verweis auf einen Inventareintrag | verwaiste Einstufungen |
| Inventareinträge ohne Einstufung und ohne „nicht bewertet" | Lücken |
| Nachweise, deren Version nicht in der Änderungstabelle vorkommt | falsche Versionsangaben |

Die dritte ist die wichtigste und die schnellste. Sie beantwortet, wie groß die offene Menge wirklich ist.

## Weiter

[Das Vorlagensystem](./template-system-logic.md) · [Vorlagenkarte](../../templates/template-map.md) · [Pflege](./inventory-and-governance.md)
