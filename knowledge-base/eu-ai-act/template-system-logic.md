# Das Vorlagensystem

Nicht jede Pflicht braucht eine eigene Vorlage, und nicht jede Vorlage braucht alle Felder. Hier steht, wie das System aufgebaut ist und was bewusst weggelassen wurde.

## Die vier Schichten

```
  1 Register     Inventar, Anbieter          -> was es gibt
  2 Bewertung    Einstufung, DSFA            -> wie es eingeordnet wird
  3 Nachweis     Nachweisregister, Anhang IV -> womit es belegt wird
  4 Prüfung      Freigabe, Turnus, Audit     -> ob der Zustand steht
```

Jede Schicht verwendet Angaben der darüberliegenden und erzeugt eigene. Eine Vorlage, die Angaben aus Schicht 1 neu abfragt, ist falsch geschnitten.

## Reihenfolge beim Aufbau

| # | Vorlage | Warum hier |
|---|---|---|
| 1 | **Inventareintrag** | liefert die Felder für alles Weitere |
| 2 | **Praktikenprüfung (Art. 5)** | kurz, heute fällig, und ein Treffer macht alles Weitere gegenstandslos |
| 3 | **Kennzeichnungsnachweis (Art. 50)** | heute fällig, technisch klein |
| 4 | **Schulungsnachweis (Art. 4)** | heute fällig, und Voraussetzung für brauchbare Aufsicht |
| 5 | **Einstufungsbogen** | braucht 1 |
| 6 | **Nachweisregister** | braucht 5, weil die Pflichten aus der Klasse folgen |
| 7 | **Prüflisten** | braucht 5 und 6 |
| 8 | **Anhang IV** | nur bei Hochrisiko und Anbieterrolle |

Die Positionen 2 bis 4 stehen bewusst vor der Einstufung: Sie brauchen keine Klasse, sind heute anwendbar, und sie sind in zwei Tagen erledigt. Wer mit der Einstufung beginnt, verschiebt sie auf unbestimmt.

## Was bewusst weggelassen ist

| Nicht enthalten | Warum |
|---|---|
| eine KI-Richtlinie | regelt einen unbekannten Bestand; kommt nach dem Register, nicht davor |
| Beispieltexte für Dokumentationsabschnitte | werden abgeschrieben, und abgeschriebene Abschnitte fallen als Füllsätze auf |
| ein Reifegradmodell | misst, wie viel erfasst ist, nicht wie richtig es ist |
| Vorlagen für die Konformitätsbewertung | das Verfahren richtet sich nach Art. 43: bei Anhang III Nr. 2–8 interne Kontrolle nach Anhang VI, bei Nr. 1 ggf. eine benannte Stelle nach Anhang VII — in beiden Fällen kein Vorlagenthema |
| eine Mustererklärung „AI-Act-konform" | Konformität bezieht sich auf ein System in einer Verwendung, nicht auf ein Unternehmen |

Die zweite Zeile ist eine Entscheidung, über die man streiten kann. Der Grund: Ein ausformulierter Beispielabschnitt wird übernommen, und in einer Prüfung erkennt man übernommene Abschnitte daran, dass sie nichts über das konkrete System sagen. Die Vorlagen hier sagen deshalb, **was** gefragt ist und **wer** es liefert.

## Wie viele Felder eine Vorlage haben darf

| Zweck | Richtwert |
|---|---|
| Aufnahmeformular für den Fachbereich | **8** |
| Inventareintrag, vollständig | 25 bis 35, in Abschnitte geteilt |
| Einstufungsbogen | 20 bis 30 |
| Prüfliste | 40 bis 80 Punkte, nach Abschnitten |
| Anhang IV | folgt dem Anhang, nicht einem Richtwert |

Die erste Zeile ist die wichtigste Zahl des ganzen Repositories. Ein Aufnahmeformular mit vierzig Feldern wird umgangen, und dann entsteht genau das, was das Register verhindern soll. Alles über die acht Felder hinaus wird **nachträglich** ergänzt, von Leuten, die es beschaffen können.

## Zwei Regeln für jedes Feld

**Jedes Feld hat eine Begründung, wofür es gebraucht wird.** Steht sie nicht in der Felderklärung, kann sie auch nicht genannt werden, wenn jemand fragt — und dann wird das Feld nicht gepflegt. Ein Register mit vierzig Feldern, von denen zwölf gefüllt sind, ist schlechter als eines mit achtzehn, die stimmen.

**„Nicht bewertet" ist zulässig, mit Person und Termin.** Das ist kein Schlupfloch, sondern die Voraussetzung dafür, dass eine Erstaufnahme überhaupt abgeschlossen werden kann. Ein offener Punkt mit Namen ist in einer Prüfung besser als eine geratene Angabe, weil eine falsche Angabe die anderen in Zweifel zieht.

## Was jede Vorlage im Kopf trägt

| Feld | Warum |
|---|---|
| Gegenstand und **Version** | sonst belegt sie einen Zeitpunkt, nicht einen Zustand |
| Stand des Eintrags | |
| vorherige Fassung | frühere Fassungen bleiben erhalten |
| erstellt durch | |
| geprüft durch, **nicht die erstellende Person** | sonst ist die Prüfung formal |

Die letzte Zeile ist der häufigste Mangel. In kleinen Organisationen ist die Trennung nicht immer möglich — dann gilt die abgeschwächte Form **ausdrücklich dokumentiert**, nicht die behauptete Trennung.

## Format

Markdown. Nicht aus Vorliebe, sondern weil bei Compliance-Unterlagen die **Änderungsgeschichte** der eigentliche Nachweis ist: Die Reihe der Fassungen belegt, dass fortlaufend gearbeitet wurde, und ein Diff zeigt, was sich geändert hat.

Wer die Vorlagen in Word oder einem Wiki führt, verliert genau das. Eine Fachanwendung löst es besser, weil sie zusätzlich Freigabezustände und Verknüpfungen führt — Markdown ist der Weg dorthin, nicht der Gegenentwurf.

## Weiter

[Feldkonsistenz](./field-consistency-logic.md) · [Vorlagenkarte](../../templates/template-map.md) · [Kernbündel](../../templates/core-template-bundle.md)
