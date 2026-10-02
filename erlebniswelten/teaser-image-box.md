# Teaser Image Box

Die **Teaser Image Box** ist eine Bildfläche mit optionalem Button. Sie eignet sich für Kategorien, Aktionen und Einstiege. Du setzt sie in jede Spalte, auch in die Sidebar.

Fertige Blöcke mit 2, 3 oder 4 Spalten liegen unter **+ Elemente (SuperiorPRO)**. Neue Blöcke dieser Art starten mit dem Box-Format 1:1.

Wie du das Element in eine vorhandene Spalte legst, steht auf der Seite [Elemente einfügen und tauschen](elemente-tauschen.md).

## Inhalt

| Feld | Wirkung |
| --- | --- |
| Bild | Das Motiv der Fläche. Ohne Bild bleibt die Bildfläche leer. Ein zugewiesenes Medienfeld aus der Kategorie wird aufgelöst. |
| Button Text | Die Beschriftung des Buttons. |
| Verlinkung | Der Link öffnet die Shopware-Auswahl. Du kannst eine Kategorie, ein Produkt, eine URL, ein Medium, eine E-Mail-Adresse oder eine Telefonnummer wählen. |
| Link in neuem Tab | Öffnet das Ziel in einem neuen Browser-Tab. |
| Button anzeigen? | **Nein** blendet den Button aus. Die Fläche bleibt verlinkt. **Ja** zeigt den Button. |

## Allgemein

**Box Format** setzt ein festes Seitenverhältnis oder eine Mindesthöhe.

Verfügbar sind Mindesthöhe, 1:1, 2:1, 2:3, 3:1, 3:2, 4:1, 4:3, 5:4, 16:9, 9:16, 21:9 und 9:21.

Bei **Mindesthöhe** gilt das Feld **Box Höhe (min. / in px)**. Die Box wird mindestens so hoch, kann aber mit dem Inhalt wachsen. Bei einem Verhältnis bestimmt das Format die Höhe. Das Bild füllt die Fläche.

In einer Reihe mit unterschiedlich langem Text wächst eine Box mit Mindesthöhe bis zur längsten Spalte. Der Text bleibt in der Box.

**Anzeigemodus** legt fest, wie das Bild in der Fläche sitzt, analog zum Bild-Element von Shopware: das Bild füllt die Fläche und wird beschnitten, oder es bleibt vollständig sichtbar.

## Button

| Feld | Wirkung |
| --- | --- |
| Schriftgröße | Die Größe der Button-Beschriftung. Neue Elemente starten mit 16 px. |
| Schriftstärke | Die Strichstärke der Beschriftung. |
| Button Textfarbe | Die Schrift im Ruhezustand. |
| Button Textfarbe (hover) | Die Schrift, wenn der Zeiger darüber liegt. |
| Button Farbe | Die Fläche des Buttons. |
| Button Farbe (hover) | Die Fläche bei Hover. |
| Button Position vertikal | **oben**, **zentriert** oder **unten** |
| Button Position horizontal | **links**, **zentriert** oder **rechts** |

Lässt du die Farbfelder leer, ist der Button weiß mit der Primärfarbe als Schrift. Beim Hover wird der Button zur Primärfarbe, die Schrift passt sich im Kontrast an. Eine gesetzte Farbe überschreibt das nur an diesem Element.

## Effekte

Drei Hover-Effekte schaltest du einzeln. Sie gelten, wenn der Zeiger über der Fläche liegt.

| Feld | Wirkung |
| --- | --- |
| ZoomIn Effekt (hover) | Das Bild wird leicht vergrößert. |
| Shadow Effekt (hover) | Ein Schatten liegt auf der Fläche. |
| Button Pfeil (hover) | Ein Pfeil schiebt sich an den Button. |

Die Effekte sind unabhängig. Du kannst Zoom ohne Schatten nutzen oder alle drei zusammen.

Die Abrundung der Fläche kommt vom Element-Radius in den [Grundeinstellungen](../theme-einstellungen/grundeinstellungen.md). In den Blöcken aus Bild und Text entfällt der Radius an der gemeinsamen Kante, damit beide Teile eine Kachel bilden.
