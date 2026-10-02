# Erweitertes Text-Element

Das **Erweiterte Text-Element** ergänzt den normalen Text von Shopware um Hintergrund, Farbverlauf und eigene Schriftfarben. Damit baust du Textkacheln, ohne eine eigene CSS-Klasse zu schreiben.

Fertige Blöcke mit 2, 3 oder 4 Spalten liegen unter **+ Elemente (SuperiorPRO)**. Neue Blöcke dieser Art starten mit einem zentrierten Platzhalter aus Überschrift und Absatz, einem hellen Hintergrund, vertikaler Ausrichtung in der Mitte und mit ausgeschalteter Option **Hintergrund nur um Inhalt**.

Daneben gibt es Blöcke **Bild und erweitertes Text-Element** mit 2, 3 oder 4 Spalten. In jeder Spalte liegt ein Bild und darunter diese Textkachel.

## Inhalt

Der Text kommt aus dem Editor, inklusive Überschriften. Die Überschriften nutzen in der Vorschau dieselbe Typografie wie das Shopware-Text-Element. In Kategorie-Erlebniswelten kannst du den Inhalt per Zuordnung an ein Kategorie- oder Produktfeld binden.

## Ausrichtung und Fläche

**Vertikale Ausrichtung** setzt den Inhalt oben, mittig oder unten, wenn die Nachbarspalte höher ist. Ohne Auswahl läuft der Hintergrund über die volle Höhe der Spalte. So entstehen gleich hohe Kacheln.

**Hintergrund nur um Inhalt** legt Farbe oder Verlauf nur um den Text. Ist die Option aus, füllt der Hintergrund die ganze Spaltenhöhe. In den Bild-Text-Blöcken liegt der Text dann direkt am Bild. An der gemeinsamen Kante entfällt der Element-Radius. Nach einem Tausch der beiden Elemente wandert diese Kante mit.

## Farben

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche. Leer lässt die Fläche transparent. |
| Hintergrundfarbe 2 | Zusammen mit der ersten Farbe ein Verlauf. Leer lässt die Fläche einfarbig. |
| Farbverlauf Winkel | Der Winkel in Grad, von −180 bis 180. |
| Überschrift Farbe | H1 bis H6 in diesem Element. |
| Textfarbe | Der Absatztext. Links im Text nutzen dieselbe Farbe. |

Beide Hintergrundfarben können Transparenz enthalten. Der Verlauf übernimmt diese Transparenz. Überschrift- und Textfarbe bleiben deckend.

Die Abrundung kommt vom Element-Radius in den Grundeinstellungen. Eine eigene Ecken-Einstellung gibt es an diesem Element nicht. Der [Lauftext](lauftext.md) hat eigene Ecken.

Neue Bild-Text-Blöcke starten mit einem schwarzen Hintergrund bei sehr geringer Deckkraft. Gespeicherte Blöcke behalten ihre Farbe.
