# Mitwirken

Dieses Repository beschreibt ein Vorlagensystem, kein Produkt. Es lebt davon, dass Leute aus der Praxis widersprechen.

## Besonders willkommen

- **Felder, die sich als unbrauchbar erwiesen haben** — systematisch leer, oder von niemandem verstanden
- **Felder, die gefehlt haben**, als eine Behörde oder ein Kunde gefragt hat. Das ist die wertvollste Rückmeldung überhaupt
- **Widersprüche, die aufgetreten sind**: welche Angabe lief in welchen Registern auseinander
- **Namenskonventionen**, die sich bewährt haben — oder Begriffe, die hier noch doppeldeutig sind
- **Erfahrungen mit der Feldzahl**: ab wann ein Aufnahmeformular umgangen wurde
- **Korrekturen an Rechtsbezügen und Fristen** — mit Fundstelle und Datum
- **Übersetzungen** einzelner Dokumente

Am nützlichsten sind Rückmeldungen nach einer echten Prüfung: wonach gefragt wurde, und welches sorgfältig geführte Feld niemanden interessiert hat.

## Weniger hilfreich

- **Mehr Felder.** Jedes zusätzliche Feld braucht eine Begründung, wofür es gebraucht wird; ohne sie wird es nicht gepflegt
- **Ausformulierte Beispieltexte** für Dokumentationsabschnitte. Sie werden abgeschrieben, und abgeschriebene Abschnitte fallen in einer Prüfung als Füllsätze auf. Die Vorlagen sagen deshalb, **was** gefragt ist und **wer** es liefert
- **Eine Mustervorlage für eine KI-Richtlinie.** Sie regelt einen unbekannten Bestand und kommt nach dem Register, nicht davor
- Reine Umformulierungen

Die ersten drei Punkte sind bewusste Entscheidungen, nicht Versäumnisse. Wer sie für falsch hält, gern — aber dann mit Begründung im Issue.

## Was hier nicht liegt

Die meisten Vorlagen liegen in den Themenrepositories; dieses hält nur das Kernbündel und die Karte. Eine Vorlage, die an zwei Stellen liegt, veraltet an einer von beiden.

Wo welche Vorlage hingehört, zeigt die [Vorlagenkarte](./templates/template-map.md) und das [Repository-Netz](./docs/repository-network.md).

## Vorgehen

Kleine Korrekturen gern direkt als Pull Request. Bei größeren Änderungen vorher ein Issue.

Wer ein Feld ändert, prüft bitte zwei Dinge mit: Steht die Angabe schon in einer anderen Vorlage? Und heißt sie dort genauso?

`npm run validate` prüft, dass alle Pflichtpfade vorhanden und die JSON-Dateien lesbar sind. Die Prüfung läuft auch in CI.

## Rechtliches

Beiträge stehen unter der MIT-Lizenz dieses Repositories. Inhalte hier sind keine Rechtsberatung; wer eine Fundstelle oder ein Datum ändert, gibt bitte die Quelle an. Fristen sind besonders heikel, weil der Digital Omnibus manche verschoben hat und andere ausdrücklich nicht.

Beispieldaten bitte erfinden. Echte Systeme oder Anbieternamen mit dokumentierten Mängeln gehören nicht in ein öffentliches Repository.

## Kodierung

Alle Dateien sind UTF-8. Das klingt selbstverständlich, war es in diesem Repository aber eine Weile nicht — deutsche Umlaute erschienen auf GitHub als Ersatzzeichen. Wer unter Windows arbeitet, prüft das vor dem Commit.
