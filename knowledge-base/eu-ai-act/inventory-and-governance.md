# Pflege

Vorlagen veralten anders als Register: nicht, weil Werte falsch werden, sondern weil die Rechtslage sich bewegt und weil Felder sich als unbrauchbar erweisen. Beides braucht einen Verantwortlichen.

## Wer die Vorlagen pflegt

| Rolle | Aufgabe |
|---|---|
| **Vorlagenverantwortlicher** | hält Feldverzeichnis und Namenskonventionen, prüft Rechtsstände |
| **Fachbereiche** | melden Felder, die niemand ausfüllen kann |
| **Datenschutz** | hält die Verzahnung mit den DSGVO-Vorlagen |
| **Leitung** | entscheidet, wenn eine Vorlage gekürzt wird |

Die zweite Zeile ist die wichtigste Rückmeldung im System. Ein Feld, das dreimal nicht ausgefüllt wurde, ist kein Disziplinproblem — es ist entweder schlecht erklärt oder überflüssig.

Die vierte Zeile steht hier, weil Kürzen eine Entscheidung ist: Jemand muss verantworten, dass eine Angabe künftig nicht mehr erhoben wird.

## Wann eine Vorlage geändert wird

| Anlass | Folge |
|---|---|
| **Rechtsänderung** | betroffene Felder anpassen, Datum im Kopf hochsetzen |
| neue Leitlinien oder harmonisierte Normen | Prüfpunkte nachziehen |
| ein Feld bleibt systematisch leer | erklären oder streichen |
| in einer Prüfung wurde etwas gefragt, das nicht erfasst war | Feld ergänzen, mit Begründung |
| zwei Vorlagen widersprechen sich | Quelle festlegen, die andere auf Verweis umstellen |

Die vierte Zeile ist die wertvollste Quelle für Vorlagenarbeit überhaupt — und sie entsteht nur, wenn jemand nach einer Prüfung aufschreibt, was gefragt wurde.

## Was bei einer Änderung passieren muss

Eine geänderte Vorlage macht ausgefüllte Exemplare nicht ungültig. Aber sie erzeugt Arbeit:

| Schritt | Warum |
|---|---|
| Vorlagenversion hochsetzen | sonst ist nicht erkennbar, nach welcher Fassung ein Eintrag entstand |
| bestehende Einträge **nicht** rückwirkend ändern | sie belegen den damaligen Stand |
| neues Feld als „nicht bewertet" in bestehende Einträge | mit Person und Termin, sonst entsteht eine unsichtbare Lücke |
| Felderklärung mitführen | ein neues Feld ohne Erklärung wird nicht gepflegt |
| Namenskonvention prüfen | heißt die neue Angabe anders als dieselbe Angabe woanders? |

Der dritte Schritt wird übersehen. Wer ein Feld ergänzt, ohne es in bestehenden Einträgen zu markieren, hat ein Register, in dem alte und neue Einträge unterschiedlich vollständig sind — und niemand sieht, welche.

## Rechtsstand

Jede Vorlage trägt im Kopf ein Datum. Ein Compliance-Formular ohne Stand ist nach zwölf Monaten unbrauchbar, weil niemand weiß, welche Rechtslage es abbildet.

| Prüfung | Turnus |
|---|---|
| Fristen und Anwendungsdaten | halbjährlich |
| Anhang I und Anhang III auf Änderungen | halbjährlich |
| neue Leitlinien, Durchführungsrechtsakte, Normen | laufend, abonniert |
| Feldverzeichnis auf Widersprüche | jährlich |

Zur dritten Zeile gilt dasselbe wie für Anbieterangaben: Ein Änderungsverlauf, den niemand liest, ist keine Maßnahme. Die Quelle gehört einer Person zugewiesen.

## Die vier Abfragen, die Widersprüche finden

| Prüfung | Findet |
|---|---|
| Einstufungen, die eine andere Modellversion nennen als das Inventar | abgetippte Felder |
| Einstufungen ohne Verweis auf einen Inventareintrag | verwaiste Bewertungen |
| Inventareinträge ohne Einstufung und ohne „nicht bewertet" | Lücken |
| Nachweise, deren Version nicht in der Änderungstabelle vorkommt | falsche Versionsangaben |

Die dritte ist die schnellste und wichtigste: Sie beantwortet, wie groß die offene Menge wirklich ist. Ausführlich: [Feldkonsistenz](./field-consistency-logic.md)

## Wo die Vorlagen liegen sollten

| Ort | Taugt | Problem |
|---|---|---|
| Textdokumente auf einem Laufwerk | nein | keine Versionierung, keine Verknüpfung, Kopien driften |
| Wiki | teilweise | Verknüpfungen schwach, Änderungsverlauf unzuverlässig |
| Repository, in Markdown | ja | braucht Zugang für Nicht-Entwickler |
| Fachanwendung | ja, mit Freigabezuständen | Einführungsaufwand |

Entscheidend ist weniger der Ort als zwei Eigenschaften: Die **Änderungsgeschichte** muss erhalten bleiben, und eine Angabe muss **adressierbar** sein, damit andere Vorlagen darauf verweisen können statt sie abzutippen.

Kopien auf Laufwerken scheitern an beidem — und sie sind der häufigste Ausgangszustand.

## Weiter

[Feldkonsistenz](./field-consistency-logic.md) · [Das Vorlagensystem](./template-system-logic.md) · [Vorlagenkarte](../../templates/template-map.md)
