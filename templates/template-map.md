# Vorlagenkarte

Welche Vorlage für welche Pflicht, wo sie liegt, und wer sie füllt.

## Nach Pflicht

| Pflicht | Rechtsgrundlage | Anwendbar seit | Vorlage | Wo |
|---|---|---|---|---|
| keine verbotenen Praktiken | Art. 5 | 2.2.2025 | Praktikenprüfung | [hier](./core-template-bundle.md) |
| KI-Kompetenz | Art. 4 | 2.2.2025 | Schulungsnachweis | [hier](./core-template-bundle.md) |
| Transparenz | Art. 50 | **2.8.2026** | Kennzeichnungsnachweis | [hier](./core-template-bundle.md) |
| Nachweise je Pflicht | — | — | Nachweisregister | [hier](./core-template-bundle.md) |
| Bestand kennen | Voraussetzung | — | Inventareintrag, Felderklärung, Beispielregister | [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) |
| Anbieterzusagen | Art. 28 DSGVO, Beschaffung | — | Registereintrag, Anbieterfragebogen | [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) |
| Einstufung | Art. 6, Anhang I/III | — | Einstufungsbogen, Auslöserliste | [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) |
| Prüfung vor Inbetriebnahme | — | — | Freigabeprüfung | [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) |
| wiederkehrende Prüfung | — | — | Turnusprüfung | [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) |
| technische Dokumentation | Art. 11, Anhang IV | 2.12.2027 | Anhang-IV-Vorlage, Dokumentationsprüfung | [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) |
| Marktbeobachtung | Art. 72 | 2.12.2027 | Art.-72-Bericht | [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) |
| Vorfallmeldung | Art. 73 | 2.12.2027 | Meldevorlagen | [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) |
| Datenschutzverletzung | Art. 33, 34 DSGVO | gilt | Meldevorlagen | [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management) |
| Verarbeitungsverzeichnis | Art. 30 DSGVO | gilt | VVT-Vorlagen | [DSGVO-Grundlagen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-compliance-workspace) |
| DSFA und FRIA | Art. 35 DSGVO, Art. 27 AI Act | gilt / 2.12.2027 | DSFA-Vorlagen | [DSFA und FRIA](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow) |
| Zuständigkeiten | — | — | RACI, Prüfturnus | [Governance-Playbook](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-playbook) |
| Prüfungsvorbereitung | — | — | Nachweispaket, Lückenprotokoll | [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness) |
| Produktfunktionen (SaaS) | — | — | Funktionsregister, Releaseprüfung | [AI Act für SaaS](https://github.com/SimpleAct-Compliance/simpleact-ai-act-for-saas) |

Die drei Zeilen mit fettem Datum oder „gilt" sind die mit Frist in der Vergangenheit. Sie stehen oben, weil die Aufmerksamkeit sonst bei den 2027er-Zeilen bleibt.

## Nach Rolle

| Wenn Sie | brauchen Sie |
|---|---|
| **Betreiber** sind, kein Hochrisiko | Inventar, Praktikenprüfung, Schulungsnachweis, Kennzeichnungsnachweis, Einstufungsbogen |
| **Betreiber** eines Hochrisikosystems sind | zusätzlich: Freigabeprüfung, Nachweisregister, Protokollführung, ggf. Art.-27-Folgenabschätzung |
| **Anbieter** sind | zusätzlich: Anhang IV, Risikomanagement, Art.-72-Bericht, Meldevorlagen |
| **Softwareanbieter** sind | Funktionsregister und Releaseprüfung statt Inventareintrag |

Die erste Zeile ist die häufigste Lage und besteht aus fünf Vorlagen. Das ist überschaubar — und es ist der Grund, warum die Karte nach Rolle sortiert nützlicher ist als nach Pflicht.

## Nach Zuständigkeit

| Wer füllt | Vorlagen |
|---|---|
| **Fachbereich** (Eigentümer) | Inventareintrag, Aufsichtsangaben, Schulungsteilnahme |
| **Entwicklung oder IT** | Modell und Version, Testsätze, Kennzeichnungsnachweis, Anhang IV Abschnitt 2 |
| **Compliance oder Recht** | Einstufungsbogen, Praktikenprüfung, Rollenbestimmung |
| **Datenschutz** | Verarbeitungsverzeichnis, DSFA, Rechtsgrundlagen |
| **Beschaffung** | Anbieterregister, Anbieterfragebogen |
| **Leitung** | Zuständigkeitstabelle, Freigaben, Fahrplan |

Keine Vorlage gehört vollständig einer Person. Wer eine Vorlage einer Person gibt, die sie **schreiben** soll, bekommt die Abschnitte, die diese Person beurteilen kann, und den Rest mit Worten gefüllt.

## Reihenfolge beim Aufbau

1. Inventareintrag
2. Praktikenprüfung (Art. 5) — kurz, heute fällig
3. Kennzeichnungsnachweis (Art. 50) — heute fällig
4. Schulungsnachweis (Art. 4) — heute fällig
5. Einstufungsbogen
6. Nachweisregister
7. Prüflisten
8. Anhang IV, nur bei Hochrisiko und Anbieterrolle

Die Positionen 2 bis 4 vor der Einstufung: Sie brauchen keine Klasse und sind in zwei Tagen erledigt. Wer mit der Einstufung beginnt, verschiebt sie auf unbestimmt.

## Was es nicht gibt

| Nicht enthalten | Warum |
|---|---|
| KI-Richtlinie | regelt einen unbekannten Bestand |
| Beispieltexte für Dokumentationsabschnitte | werden abgeschrieben und fallen als Füllsätze auf |
| Reifegradmodell | misst Erfassung, nicht Richtigkeit |
| Mustererklärung „AI-Act-konform" | Konformität bezieht sich auf ein System in einer Verwendung |

## Weiter

[Kernbündel](./core-template-bundle.md) · [Das Vorlagensystem](../knowledge-base/eu-ai-act/template-system-logic.md) · [Feldkonsistenz](../knowledge-base/eu-ai-act/field-consistency-logic.md)
