# Lauftext

Der **Lauftext** ist ein Band, das endlos durchläuft. Er eignet sich für Angebote, Hinweise oder kurze Markensätze. Ein fertiger Block unter **+ Elemente (SuperiorPRO)** setzt ihn über die volle Breite.

## Text

Im Feld **Text** steht jeder Satz in einer eigenen Zeile. Jede Zeile wird ein Abschnitt im Band.

```
Kostenloser Versand ab 50 €
Neu im Shop
Jetzt bis zu 30 % auf ausgewählte Artikel
```

HTML in der Zeile ist erlaubt, zum Beispiel `<strong>`, `<em>` oder `&bull;`. Eine leere Zeile erzeugt keinen Abschnitt.

## Bewegung

**Geschwindigkeit** ist das Tempo in Pixeln pro Sekunde, von 1 bis 200. Ein kleiner Wert lässt das Band langsam laufen, 200 ist schnell.

**Pause bei Mausover** hält das Band an, solange der Zeiger darüber liegt. Auf dem Touchscreen gibt es diesen Hover nicht, das Band läuft dort weiter.

## Hintergrund

Drei Farbfelder bauen den Verlauf.

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die erste Farbe |
| Hintergrundfarbe 2 | Die zweite Farbe |
| Hintergrundfarbe 3 | Die dritte Farbe |
| Gradient-Typ | **Linear** zieht den Verlauf in eine Richtung. **Radial** legt ihn kreisförmig. |
| Gradient-Winkel | Dreht den linearen Verlauf. Beim radialen Verlauf hat der Winkel keine sichtbare Richtung. |

Lässt du die Farbfelder leer, nutzt das Band die Primärfarbe, eine aufgehellte Primärfarbe und eine passende Schriftfarbe. Eine gesetzte Farbe überschreibt das. In der Administration siehst du bei leeren Farben einen grauen Verlauf mit schwarzer Schrift, nicht die Shop-Primärfarbe.

## Text

| Feld | Wirkung |
| --- | --- |
| Textfarbe | Die Schrift im Band. Leer nutzt die Kontrastfarbe zur Primärfarbe. |
| Schriftgröße | Die Größe, zusammen mit der Einheit. |
| Schriftgröße Einheit | **px**, **em** oder **rem** |
| Schriftart | **Text-Schriftart** oder **Überschriften-Schriftart** aus dem Tab Typografie |
| Zeichenabstand | Der Abstand zwischen den Buchstaben |

## Ecken und Abstände

Jede Ecke hat einen eigenen Radius: oben links, oben rechts, unten rechts, unten links. Die **Border-Radius Einheit** gilt für alle vier Ecken und kann px, em, rem oder Prozent sein.

**Padding oben** und **Padding unten** sind der Innenabstand des Bandes. **Abstand zwischen Items** ist die Lücke zwischen zwei Textabschnitten. Beide haben eine eigene Einheit.

So kann das Band flach an der Sektion kleben oder als abgerundete Pille in der Seite liegen.
