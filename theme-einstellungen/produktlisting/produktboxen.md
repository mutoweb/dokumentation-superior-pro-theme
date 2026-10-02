# Produktboxen

Die Produktbox ist die Kachel in Kategorie, Suche und Produkt-Slidern. Du gestaltest sie im Tab **Produktlisting** unter **Produktboxen**.

## Bild

**Höhe des Produktbildes** setzt eine feste Höhe in Pixel. Das Bild wird in diese Höhe eingepasst.

**Bildformat** startet mit **Nicht gesetzt** und behält diese Höhe. Wählst du ein Format, ersetzt es die Höhe. Das Bild füllt die Fläche und wird dabei beschnitten. Der Ausschnitt bleibt zentriert.

| Format | Wirkung |
| --- | --- |
| Nicht gesetzt | Die Bildhöhe gilt. |
| 1:1 | Quadrat |
| 4:3, 3:2, 5:4 | Querformat |
| 3:4, 2:3 | Hochformat |

Ein gesetztes Format gilt für alle Produktboxen des Verkaufskanals. Die Bildergalerie in den Erlebniswelten hat ein eigenes Format und folgt diesem Feld nicht.

## Inhalt

| Feld | Wirkung |
| --- | --- |
| Zeige Beschreibung | **ja** zeigt den Kurztext unter dem Namen. **nein** blendet ihn aus. |
| Zeige Variantenmerkmale | **ja** zeigt die Merkmale, mit denen sich Varianten unterscheiden. **nein** blendet sie aus. |
| Zeige Preis Einheit | **ja** zeigt die Einheit zum Preis, zum Beispiel je Liter. **nein** blendet sie aus. |
| Produktbox Inhalt Ausrichtung | **linksbündig**, **zentriert** oder **rechtsbündig**. Name, Preis und Text folgen dieser Ausrichtung. |

Name, Preis und Bild bleiben sichtbar. Ausblenden betrifft nur die genannten Zeilen.

## Scroll-Effekt

Unter den Produktboxen gibt es **Beim Hineinscrollen** und **Beim Zurückscrollen**. Die Namen sind dieselben wie bei der [Scroll-Animation](../../erlebniswelten/scroll-animation.md) in den Erlebniswelten. **Keine** ist der Ausgangswert und lässt das Listing unverändert.

Die Boxen blenden nacheinander ein, nicht alle auf einmal.

| Beim Hineinscrollen | Bewegung |
| --- | --- |
| Keine | kein Effekt |
| Fade | Die Box wird sichtbar. |
| Slide von unten | Die Box kommt von unten. |
| Slide von oben | Die Box kommt von oben. |
| Slide von rechts | Die Box kommt von rechts. |
| Slide von links | Die Box kommt von links. |
| Zoom kleiner | Die Box startet etwas kleiner und wächst auf die normale Größe. |
| Zoom größer | Die Box startet etwas kleiner und wächst auf die normale Größe. |

| Beim Zurückscrollen | Bewegung |
| --- | --- |
| Keine | Die Box bleibt sichtbar. |
| Fade | Die Box blendet aus. |
| Slide nach oben, unten, links oder rechts | Die Box verlässt das Bild in diese Richtung. |
| Zoom kleiner | Die Box wird etwas kleiner. |
| Zoom größer | Die Box wird etwas größer. |

Ein zweites Hineinscrollen nutzt wieder den Effekt vom Hineinscrollen, auch wenn der Effekt beim Zurückscrollen ein anderer ist. Wer im System „Animationen reduzieren“ aktiviert hat, sieht die Boxen ohne Bewegung.

## Farben

Jede Farbe gibt es für den Ruhezustand. Wo eine Hover-Zeile dabei steht, gilt sie, wenn der Zeiger über der Box liegt.

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche der Box |
| Hintergrundfarbe (hover) | Die Fläche bei Hover |
| Rahmenfarbe | Der Rand |
| Rahmenfarbe (hover) | Der Rand bei Hover |
| Produktname Farbe | Der Name |
| Produktname Farbe (Box hover) | Der Name bei Hover |
| Beschreibungstext Farbe | Der Kurztext |
| Beschreibungstext Farbe (Box hover) | Der Kurztext bei Hover |
| Bewertungssterne Farbe (leer) | Sterne ohne Bewertung |
| Bewertungssterne Farbe (leer) (Box hover) | Leere Sterne bei Hover |
| Bewertungssterne Farbe (ausgefüllt) | Sterne mit Bewertung |
| Bewertungssterne Farbe (ausgefüllt) (Box hover) | Gefüllte Sterne bei Hover |
| Preis Farbe | Der aktuelle Preis |
| Sale Preis Farbe | Der Streichpreis |

Die Preisfarbe aus den [Grundeinstellungen](../grundeinstellungen.md) bleibt die shopweite Quelle. Hier überschreibst du sie nur in der Produktbox.

Während die Filter neu laden, zeigt jede Box nur noch mittig einen Kreis in der Primärfarbe. Name, Preis, Beschreibung und das Merkzettel-Icon sind in diesem Moment ausgeblendet. Dafür gibt es keine eigene Einstellung. Die Farben außerhalb des Ladezustands bleiben, wie du sie gesetzt hast.

Das Merkzettel-Icon auf dem Bild färbst du im Tab [Verschiedenes](../verschiedenes.md).
