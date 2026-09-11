# Zur deutschen Selah-Fassung beitragen

Danke, dass Sie helfen, diese Fassung genauer, klarer und
natürlicher zu machen. Man muss kein Fachmann sein, um ein Problem
zu melden: Beschreiben Sie, was Sie beobachten, geben Sie an, was
Ihnen vorliegt, und unterscheiden Sie Gewissheit von Vorschlag.

## Meldung oder Änderungsanfrage

- Eröffnen Sie ein **Issue**, wenn die Lesart Diskussion verlangt,
  mehrere Möglichkeiten bestehen oder unklar ist, wie der
  ausgerichtete Datensatz sich ändern soll.
- Eröffnen Sie einen **Pull Request**, wenn Fehler und exakter
  Ersatz klar sind.
- Für Fehler der Anwendung oder private Fragen zu Sicherheit,
  Konten oder persönlichen Daten nutzen Sie
  [den Selah-Support](https://selahproject.com/support).

## Was anzugeben ist

Nennen Sie Buch, Kapitel, Vers und das hebräische Token; den
aktuellen Text; den vorgeschlagenen Text; den Grund der Änderung;
und die lexikalische, grammatische, kontextuelle oder
veröffentlichte Quelle, die ihn stützt. Sagen Sie auch, ob Sie
deutscher Muttersprachler sind und ob Sie das Hebräische direkt
lesen.

## Wie ein Datensatz zu ändern ist

Die Dateien liegen unter `<buch>/<kapitel>/<vers>.json`.

- Ändern Sie `translation` und den `gloss` des betroffenen Tokens,
  wenn beide betroffen sind.
- Bewahren Sie `book`, `chapter`, `verse`, `ref`, die hebräischen
  `surface`-Werte sowie Reihenfolge und Zahl der Tokens, außer Sie
  melden einen Ausrichtungsfehler.
- Ändern Sie keine Modell-, Stufen-, Datums- oder sonstigen
  Herkunftsfelder, um die Korrektur als neue Erzeugung
  auszugeben.
- Bewahren Sie die Konventionen der Winkelklammern, der
  Gottesnamen und von `⟨את⟩`.
- Vermeiden Sie reine Formänderungen und sachfremde Korrekturen.

## Conduct

Be honest, be kind, show your evidence. Distinguish certainty from
suggestion. The maintainers weigh and decide.
