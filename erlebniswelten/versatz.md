# Versatz

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

Mit dem Versatz schiebst du den Inhalt einer Sektion über den Rand ihres Hintergrunds. Das Bild oder die Farbe der Sektion bleibt stehen. So ragt eine Kachel oder ein Text in die nächste Sektion hinein.

Der Versatz liegt an der Sektion, nicht am Block.

## So stellst du ihn ein

1. Klicke links auf das Sektions-Symbol.
2. Öffne die Sektions-Einstellungen.
3. Wähle unter **Versatz** eine Richtung und einen Wert. Das Feld steht über **CSS-Klassen**.
4. Speichere die Erlebniswelt.

**Nicht gesetzt** entfernt den Versatz. Andere Klassen im CSS-Feld bleiben stehen. Du kannst die Klasse auch weiterhin direkt eintragen. Der Versatz ist in der Zeichenfläche sichtbar.

## Nach unten

| Auswahl           | Verschiebung |
| ----------------- | ------------ |
| Nach unten 50 px  | 50 px        |
| Nach unten 100 px | 100 px       |
| Nach unten 150 px | 150 px       |
| Nach unten 200 px | 200 px       |
| Nach unten 250 px | 250 px       |

## Nach oben

| Auswahl          | Verschiebung |
| ---------------- | ------------ |
| Nach oben 50 px  | 50 px        |
| Nach oben 100 px | 100 px       |
| Nach oben 150 px | 150 px       |
| Nach oben 200 px | 200 px       |
| Nach oben 250 px | 250 px       |

Dieselbe Wirkung haben die Klassen `muto-cms-section-offset-pt-1` bis `muto-cms-section-offset-pt-5` nach unten und `muto-cms-section-offset-nt-1` bis `muto-cms-section-offset-nt-5` nach oben. Die Zahl ist die Stufe, nicht die Pixelzahl. Stufe 1 sind 50 px, Stufe 5 sind 250 px.

Die folgende Sektion braucht genug Abstand nach oben, sonst überdeckt der versetzte Inhalt den nächsten Block.

Eine [Scroll-Animation](scroll-animation.md) auf derselben Sektion blendet den Versatz nicht aus. Der Inhalt bleibt sichtbar, auch wenn die Sektion einen Einblend-Effekt hat.
