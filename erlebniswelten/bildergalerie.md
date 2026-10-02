# Bildergalerie

Die **Bildergalerie** zeigt mehrere Bilder in einem Raster. Ein Klick kann das Bild groß öffnen. Ein fertiger Block unter **+ Elemente (SuperiorPRO)** setzt die Galerie über die volle Breite.

## Bilder

Im Tab **Inhalt** lädst du Bilder direkt hoch oder wählst sie aus der Medienverwaltung. Die Reihenfolge in der Liste ist die Reihenfolge im Raster. Ziehe die Einträge, um sie zu sortieren. Ein entferntes Bild verschwindet aus der Galerie, die Datei bleibt in der Medienverwaltung.

## Bildformat

**Bildformat** setzt ein festes Verhältnis für jedes Bild oder lässt das Original stehen.

Verfügbar sind Original, 1:1, 2:1, 2:3, 3:1, 3:2, 4:1, 4:3, 5:4, 16:9, 9:16, 21:9 und 9:21.

Bei **Original** behalten die Bilder ihre Proportion. Das Raster setzt sich versetzt, ähnlich einem Mauerwerk. Bei einem festen Format liegen die Bilder in einem gleichmäßigen Raster und werden beschnitten.

Das Format der Produktboxen im Theme-Manager gilt hier nicht.

## Spalten und Abstand

Die Spaltenzahl stellst du getrennt ein für Desktop, Tablet und Smartphone. Auf dem Smartphone sind ein oder zwei Spalten üblich, auf dem Desktop drei oder vier.

**Abstand** ist der Zwischenraum in Pixel. Der Wert `0` ist ein echter Abstand von 0. Die Galerie fällt dabei nicht auf einen Standardabstand zurück.

## Rahmen

| Feld | Wirkung |
| --- | --- |
| Border-Breite (in px) | Die Stärke des Rahmens. `0` entfernt ihn. |
| Border-Farbe | Die Farbe des Rahmens. |
| Border-Radius (in px) | Die Abrundung jedes Bildes. Sie ist unabhängig vom Element-Radius des Themes. |

## Lightbox

**Lightbox aktivieren** öffnet das Bild groß, mit Wechsel zum vorherigen und nächsten Bild. Jede Galerie hat ihre eigene Lightbox. Zwei Galerien auf einer Seite vermischen ihre Bilder nicht.

Die Beschriftungen der Steuerung für Screenreader änderst du über die Textbausteine unter `mutoTheme.lightbox`:

```
mutoTheme.lightbox.dialog
mutoTheme.lightbox.close
mutoTheme.lightbox.prev
mutoTheme.lightbox.next
mutoTheme.lightbox.loadError
mutoTheme.lightbox.showImage
```

Die sichtbaren Bildunterschriften kommen aus den Medien, nicht aus diesen Bausteinen. `showImage` ist die Beschriftung, mit der das Bild geöffnet wird. `loadError` erscheint, wenn ein Bild in der Lightbox nicht geladen werden kann.
