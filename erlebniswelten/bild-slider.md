# Bild-Slider mit Text

Der **Bild-Slider mit Text** zeigt mehrere Bilder nacheinander. Jedes Bild kann einen eigenen Text, einen Link und ein eigenes Mobilbild haben. Ein fertiger Block unter **+ Elemente (SuperiorPRO)** setzt den Slider über die volle Breite.

Der Übergang **Fade** im Tab Verschiedenes gilt für den Bildslider von Shopware, nicht für dieses Element. Den Übergang stellst du hier am Element ein.

## Bilder

Im Tab **Inhalt** lädst du die Bilder hoch oder wählst sie aus der Medienverwaltung. Die Reihenfolge ist die Reihenfolge der Slides. Jedes Bild wird darunter im Tab **Einstellungen** als eigener Slide konfiguriert, beschriftet mit **Slide 1**, **Slide 2** und so weiter.

Die Zeichenfläche zeigt den Text auf dem Bild, mit Position, Farben, Breite und Ecken. In der Smartphone-Ansicht der Administration steht der Text unter dem Bild, so wie im Shop.

## Darstellung des Sliders

Diese Felder gelten für den ganzen Slider, nicht für einen einzelnen Slide.

| Feld | Wirkung |
| --- | --- |
| Anzeigemodus | Wie das Bild in der Fläche sitzt. Bei **Cover** füllt es die Fläche und wird beschnitten. |
| Minimale Höhe | Die Höhe der Fläche, solange der Modus Cover ist. Neue Slider starten mit 600 px. |
| Vertikale Ausrichtung | Nur sichtbar, wenn der Modus nicht Cover ist. Setzt das Bild oben, mittig oder unten. |
| Navigation Pfeile | Die Pfeile liegen innen, außen oder sind aus. |
| Navigation Punkte | Die Punkte liegen innen, außen oder sind aus. |
| Geschwindigkeit | Die Dauer des Übergangs in Millisekunden. Neue Slider starten mit 1000. |
| Automatisch wechseln | Der Slider blättert von allein. Shopware weist darauf hin, dass automatisches Blättern für manche Besucher störend sein kann. |
| Pause zwischen den Slides | Die Wartezeit in Millisekunden, solange automatisch gewechselt wird. Der Startwert ist 5000. |
| Dekorativ | Markiert die Bilder als dekorativ, wenn sie keine Information tragen. |
| Übergang | **Fade** blendet die Bilder. **Slide** schiebt sie. Neue Slider starten mit Fade. |

Farben der Pfeile und Punkte kommen aus dem Tab [Verschiedenes](../theme-einstellungen/verschiedenes.md).

## Je Slide

| Feld | Wirkung |
| --- | --- |
| Bild Mobil | Ein zweites Bild für kleine Bildschirme. Ohne Auswahl wird das Hauptbild auch mobil verwendet. |
| Link | Das Ziel, wenn der Slide angeklickt wird. |
| Aria-Label | Eine Beschriftung des Links für Screenreader. |
| Link in neuem Tab | Öffnet das Ziel in einem neuen Tab. |
| Text über dem Bild | Überschrift und Text auf diesem Slide. |
| Textposition | Neun Positionen, von links oben bis rechts unten. |
| Hintergrundfarbe | Die Fläche hinter dem Text auf dem Desktop. Transparenz ist möglich. |
| Hintergrundfarbe Mobil | Die Fläche hinter dem Text, wenn er auf dem Handy unter dem Bild steht. |
| Headline-Farbe | Die Überschrift in diesem Text. |
| Textfarbe | Der Absatz in diesem Text. |
| Textbreite Desktop (%) | Wie viel der Bildbreite der Text einnimmt. Der Startwert ist 40. |
| Textbreite Tablet (%) | Dieselbe Breite auf dem Tablet. Leer übernimmt die Desktop-Breite. |
| Radius je Ecke | Oben links, oben rechts, unten rechts und unten links, in Pixel. |

Auf dem Handy steht der Text unter dem Bild, nicht darüber. Position und Desktop-Breite gelten dort nicht. Die mobile Hintergrundfarbe färbt diese Zeile.

Ein Slide ohne Text zeigt nur das Bild. Ein Slide ohne Link ist nicht klickbar, der Text bleibt lesbar.
