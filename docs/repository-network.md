# Das Netz der Repositories

Dieses Repository ist die **Klammer um die Vorlagen**. Es hält kein Thema, sondern das Feldverzeichnis, die Karte und die vier Vorlagen, die sonst nirgends liegen.

## Wo welche Vorlage liegt

```
  Inventar -> Einstufung -> Prüfung -> Dokumentation -> Audit -> Betrieb
      |            |            |            |            |         |
      +------------+------------+------------+------------+---------+
                                |
                        [Vorlagenkarte, Feldverzeichnis]
```

| Schritt | Repository | Vorlagen dort |
|---|---|---|
| Inventar | [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) | Inventareintrag, Felderklärung, Beispielregister, Zuständigkeitsmodell, Prüfablauf |
| Inventar | [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) | Registereintrag, Anbieterfragebogen |
| Einstufung | [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) | Einstufungsbogen, Auslöserliste |
| Prüfung | [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) | Freigabeprüfung, Turnusprüfung |
| Dokumentation | [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) | Anhang-IV-Vorlage, Dokumentationsprüfung |
| Audit | [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness) | Nachweispaket, Lückenprotokoll |
| Betrieb | [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) | Meldevorlagen, Vorfallregister |
| Governance | [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) | Inventar, Einstufung, Anhang IV, Art.-72-Bericht |
| Governance | [Governance-Playbook](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-playbook) | RACI, Prüfturnus |
| Besondere Lage | [AI Act für SaaS](https://github.com/SimpleAct-Compliance/simpleact-ai-act-for-saas) | Funktionsregister, Releaseprüfung |
| Einstieg | [Einstieg EU AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-compliance-guide) | Fahrplan |

## Was nur hier liegt

| Vorlage | Pflicht | Warum sonst nirgends |
|---|---|---|
| **Praktikenprüfung** | Art. 5, seit 2.2.2025 | braucht keine Klasse und gehört zu keinem Schritt — sie kommt vor allen |
| **Schulungsnachweis** | Art. 4, seit 2.2.2025 | klassenunabhängig |
| **Kennzeichnungsnachweis** | Art. 50, seit 2.8.2026 | gilt zusätzlich zu jeder Klasse |
| **Nachweisregister** | — | verbindet alle Pflichten, gehört deshalb keinem Schritt |

Die ersten drei sind die Pflichten mit Frist in der Vergangenheit. Dass sie in keiner schrittbezogenen Sammlung lagen, war die Lücke, die dieses Repository schließt.

## Die Regel, die das Netz zusammenhält

**Ein Thema, ein Ort. Eine Angabe, eine Quelle.**

Die erste Hälfte gilt für die Repositories: Derselbe Inhalt an zwei Stellen veraltet an einer von beiden. Die zweite gilt für die Felder: Dieselbe Angabe in zwei Vorlagen widerspricht sich nach einem halben Jahr.

Dieses Repository hält das Feldverzeichnis, mit dem die zweite Hälfte überprüfbar wird. Siehe [Feldkonsistenz](../knowledge-base/eu-ai-act/field-consistency-logic.md).

## Datenschutzseite

| Repository | Vorlagen |
|---|---|
| [DSGVO-Grundlagen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-compliance-workspace) | Verarbeitungsverzeichnis, Rechtsgrundlagen, Betroffenenrechte |
| [DSFA und FRIA](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow) | DSFA nach Art. 35 DSGVO, Grundrechte-Folgenabschätzung nach Art. 27 AI Act |
| [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management) | Meldevorlagen, 72-Stunden-Fristenlauf |

Für die Feldkonsistenz ist diese Seite besonders wichtig: Datenarten, Zweck, Empfänger und Verarbeitungsort werden von beiden Regelwerken gebraucht. Wer sie zweimal erhebt, hat sie nach einem halben Jahr an einer von beiden Stellen falsch.

## Anbindung

[Integrationen](https://github.com/SimpleAct-Compliance/simpleact-integrations-apis) — Register, die sich aus vorhandenen Systemen füllen. Für das Vorlagensystem die wirksamste Maßnahme überhaupt: Jede Angabe, die automatisch entsteht, kann nicht abgetippt werden.

## Tarifgenaue Anbieterangaben

Für die Felder zu Trainingsnutzung, Verarbeitungsort und Unterauftragsverarbeitern: ein öffentliches Register mit tarifgenauen Angaben, jede mit Quelle und Prüfdatum — **[actcomp.de](https://actcomp.de)**
