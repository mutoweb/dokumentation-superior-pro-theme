# Hintergrund mischen

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

+Für eine Sektion mit Hintergrundfarbe und Hintergrundbild gibt es das Feld **Mischmodus**. Es steht über **Parallax**. Die Auswahl mischt das Bild mit der Farbe und ist in der Zeichenfläche sichtbar.

**Normal** entfernt den Modus. Die weiteren Wahlmöglichkeiten schreiben eine Klasse ins Feld **CSS-Klassen**:

| Auswahl    | Wirkung                                                      | Klasse                  |
| ---------- | ------------------------------------------------------------ | ----------------------- |
| Multiply   | Das Bild wird mit der Farbe multipliziert und wirkt dunkler. | `muto-blend-multiply`   |
| Screen     | Die Farbe hellt das Bild auf.                                | `muto-blend-screen`     |
| Overlay    | Helle Bildstellen werden heller, dunkle dunkler.             | `muto-blend-overlay`    |
| Darken     | Je Pixel bleibt der dunklere Wert aus Farbe und Bild.        | `muto-blend-darken`     |
| Lighten    | Je Pixel bleibt der hellere Wert.                            | `muto-blend-lighten`    |
| Color      | Die Farbe färbt das Bild, die Helligkeit des Fotos bleibt.   | `muto-blend-color`      |
| Luminosity | Die Helligkeit der Farbe legt sich über das Bild.            | `muto-blend-luminosity` |

Es gilt immer nur eine dieser Klassen. Andere Klassen bleiben. Du kannst die Klasse auch weiterhin direkt eintragen. Stehen mehrere Mischmodus-Klassen im Feld, gilt die letzte.

Das Feld ist deaktiviert, solange Farbe oder Bild fehlt. Die Mischung gilt auch zusammen mit [Parallax](parallax.md).

## So richtest du es ein

1. Klicke links auf das Sektions-Symbol.
2. Setze eine **Hintergrundfarbe** und ein **Hintergrundbild**.
3. Wähle den **Mischmodus**.
4. Speichere die Erlebniswelt.

Eine kräftige Primärfarbe mit **Multiply** oder **Color** färbt ein graues Foto ein, ohne das Motiv zu ersetzen. **Normal** zeigt Farbe und Bild wieder ungemischt, je nachdem, wie Shopware beide übereinanderlegt.
