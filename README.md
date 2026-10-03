# Vorlagen für den EU AI Act

**Das Problem ist nicht, dass Vorlagen fehlen. Es ist, dass dieselbe Angabe in vier Vorlagen anders heißt.** Dann steht die Modellversion im Inventar, in der Einstufung und in der Dokumentation — dreimal gepflegt, nach einem halben Jahr dreimal verschieden.

Dieses Repository behandelt die Vorlagen als **System**: welche Felder es überhaupt gibt, wo sie herkommen, und welche Vorlage sie weiterverwendet statt neu abzufragen.

*Templates as a system: a shared field dictionary, one owner per field, and the consistency rules that keep four registers from contradicting each other.*

---

## Die Regel, auf die alles hinausläuft

> **Jede Angabe hat genau eine Quelle. Alle anderen Vorlagen verweisen darauf.**

Was das praktisch bedeutet:

| Angabe | Quelle | Verweist darauf |
|---|---|---|
| Einsatzzweck | Inventar | Einstufung, Dokumentation, Prüfungen |
| Modell und Version | Inventar | Einstufung, Dokumentation, Vorfall |
| rechtliche Klasse | Einstufungsbogen | Prüflisten, Dokumentation |
| Betroffenenkreis | Inventar | Einstufung, DSFA, Vorfall |
| Verantwortlicher | Inventar | alle |

Wer diese fünf Zeilen durchhält, hat das meiste gewonnen. Wer sie nicht durchhält, pflegt vier Register und kann in einer Prüfung keines davon belegen, weil sie sich widersprechen.

Ausführlich: [Feldkonsistenz](./knowledge-base/eu-ai-act/field-consistency-logic.md)

## Welche Vorlage für welche Pflicht

| Pflicht | Vorlage | Wo sie liegt |
|---|---|---|
| Bestand kennen | Inventareintrag | [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) |
| Anbieterzusagen | Registereintrag, Anbieterfragebogen | [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) |
| Einstufung | Einstufungsbogen, Auslöserliste | [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) |
| Prüfung | Freigabeprüfung, Turnusprüfung | [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) |
| Anhang IV | technische Dokumentation | [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) |
| Art. 50 Transparenz | **Kennzeichnungsnachweis** | hier |
| Art. 4 KI-Kompetenz | **Schulungsnachweis** | hier |
| Art. 5 Prüfung | **Praktikenprüfung** | hier |
| Vorfälle | Meldevorlagen | [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) |
| Marktbeobachtung | Art.-72-Bericht | [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) |

Die drei mit **hier** markierten Zeilen sind die, die bisher in keiner Sammlung standen — obwohl alle drei **heute** fällig sind. Sie liegen im [Kernbündel](./templates/core-template-bundle.md).

Vollständige Zuordnung: [Vorlagenkarte](./templates/template-map.md)

## Die drei Vorlagen für das, was heute gilt

| Vorlage | Pflicht | Seit |
|---|---|---|
| **Praktikenprüfung** | Art. 5, zehn verbotene Praktiken | 2.2.2025 |
| **Schulungsnachweis** | Art. 4 KI-Kompetenz | 2.2.2025 |
| **Kennzeichnungsnachweis** | Art. 50 Transparenz | 2.8.2026 |

Alle drei sind kurz. Alle drei brauchen keine Risikoklasse. Und alle drei fehlen in den meisten Ablagen, weil die Aufmerksamkeit bei Anhang III liegt — das erst ab **2.12.2027** gilt.

## Was eine Vorlage brauchbar macht

Vier Eigenschaften, an denen sich die Vorlagen hier messen lassen:

| Eigenschaft | Gegenbeispiel |
|---|---|
| **ausfüllbar ohne Beratungsgespräch** | Felder, die niemand ohne Erklärung versteht |
| **je Feld eine Begründung**, wofür es gebraucht wird | vierzig Felder, zwölf gefüllt |
| **„nicht bewertet" zulässig**, mit Person und Termin | Leerfelder, die wie Erfüllung aussehen |
| **versionierbar** | Word-Dokument ohne Änderungsgeschichte |

Die zweite ist die, die am meisten weglässt: Ein Feld ohne Begründung wird nicht gepflegt, und ein Register mit vierzig Feldern, von denen zwölf gefüllt sind, ist schlechter als eines mit achtzehn, die stimmen.

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Was wann gilt](./knowledge-base/eu-ai-act/overview.md) | Fristen, und welche Vorlage heute gebraucht wird |
| [Begriffe](./knowledge-base/eu-ai-act/definitions.md) | die Begriffe, die in mehreren Vorlagen vorkommen |
| [Rollen](./knowledge-base/eu-ai-act/scope-and-actors.md) | welche Vorlage für Anbieter, welche für Betreiber |
| [Klassen und Vorlagen](./knowledge-base/eu-ai-act/risk-logic.md) | welche Vorlage je Klasse nötig ist |
| [Das Vorlagensystem](./knowledge-base/eu-ai-act/template-system-logic.md) | Aufbau, Reihenfolge, was weggelassen gehört |
| [Feldkonsistenz](./knowledge-base/eu-ai-act/field-consistency-logic.md) | eine Quelle je Angabe, Namenskonventionen, Widersprüche |
| [Pflege](./knowledge-base/eu-ai-act/inventory-and-governance.md) | wer Vorlagen pflegt, wann sie geändert werden |

### Vorlagen

| Vorlage | Inhalt |
|---|---|
| [Kernbündel](./templates/core-template-bundle.md) | Praktikenprüfung, Schulungsnachweis, Kennzeichnungsnachweis, Nachweisregister |
| [Vorlagenkarte](./templates/template-map.md) | welche Vorlage für welche Pflicht, und wo sie liegt |

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt die Register verbunden, sodass eine Angabe einmal erfasst und überall verwendet wird: **[AI Act Software](https://simpleact.de/ai-act-software)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
