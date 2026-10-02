# Scroll-Animation

An einer Sektion und an einem Block gibt es den Bereich **Scroll Animation**. Die Fläche blendet ein, wenn sie ins Bild kommt, und kann einen zweiten Effekt spielen, wenn du zurückscrollst.

Ohne Auswahl bleibt alles unverändert. Weitere CSS-Klassen bleiben erhalten.

Dieselben Effektnamen gibt es für die Produktboxen im Theme-Manager. Die Erklärung dazu steht unter [Produktboxen](../theme-einstellungen/produktlisting/produktboxen.md).

## Felder

| Feld | Wirkung |
| --- | --- |
| Beim Hineinscrollen | Der Effekt, sobald die Fläche ins Bild scrollt. **Keine** entfernt ihn. |
| Beim Zurückscrollen | Der Effekt, wenn die Fläche beim Hochscrollen das Bild verlässt. **Keine** lässt sie sichtbar. |
| Dauer | Die Länge des Effekts. **Standard** behält 0,9 Sekunden. |

Die Dauer stellst du von 300 ms bis 2000 ms in Schritten von 100 ms ein. Sie wirkt nur zusammen mit einem Effekt. Ohne Effekt ändert die Dauer nichts.

Die Animation startet 100 px über dem unteren Rand des Fensters, unabhängig von der Höhe der Fläche. Flächen, die beim Laden schon im Bild sind, blenden mit ihrem Effekt ein. Sie springen nicht erst später auf.

## Effekte beim Hineinscrollen

| Auswahl | Bewegung |
| --- | --- |
| Keine | Die Fläche ist sofort sichtbar. |
| Fade | Die Fläche blendet ein. |
| Slide von unten | Die Fläche kommt von unten. |
| Slide von oben | Die Fläche kommt von oben. |
| Slide von rechts | Die Fläche kommt von rechts. |
| Slide von links | Die Fläche kommt von links. |
| Zoom kleiner | Die Fläche startet etwas kleiner und wächst auf die normale Größe. |
| Zoom größer | Die Fläche startet etwas kleiner und wächst auf die normale Größe. |

## Effekte beim Zurückscrollen

| Auswahl | Bewegung |
| --- | --- |
| Keine | Die Fläche bleibt sichtbar. |
| Fade | Die Fläche blendet aus. |
| Slide nach oben | Die Fläche fährt nach oben heraus. |
| Slide nach unten | Die Fläche fährt nach unten heraus. |
| Slide nach links | Die Fläche fährt nach links heraus. |
| Slide nach rechts | Die Fläche fährt nach rechts heraus. |
| Zoom kleiner | Die Fläche wird etwas kleiner. |
| Zoom größer | Die Fläche wird etwas größer. |

Ein zweites Hineinscrollen nutzt wieder den Effekt vom Hineinscrollen, auch wenn der Effekt beim Zurückscrollen ein anderer ist. Seitliches Sliden und Zoom verbreitern die Seite nicht, auch auf dem Smartphone.

Fade, Slide und Zoom laufen über die gewählte Dauer weich aus.

## Zusammen mit anderen Einstellungen

Ein [Versatz](versatz.md) bleibt sichtbar, auch wenn dieselbe Sektion eine Scroll-Animation hat. Parallax, Mischmodus und Spaltenabstand bleiben eigene Klassen und werden von der Animation nicht gelöscht.

Wer im Betriebssystem „Animationen reduzieren“ aktiviert hat, sieht die Flächen ohne Bewegung. Ohne JavaScript bleiben sie ebenfalls sichtbar.

{% hint style="info" %}
Setz den Effekt an der Sektion, wenn die ganze Fläche gemeinsam erscheinen soll. Setz ihn am Block, wenn nur eine Kachel in der Sektion animiert werden soll und die Nachbarblöcke still bleiben.
{% endhint %}
