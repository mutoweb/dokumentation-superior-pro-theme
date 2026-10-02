# Navigation

Im Tab **Navigation** gestaltest du die Hauptnavigation und das Flyout, das sich bei Unterkategorien öffnet. Die Punkte selbst kommen aus deiner Kategorie-Navigation in Shopware, nicht aus dem Theme.

Ob die Leiste in einer eigenen Zeile steht oder neben dem Logo, entscheidet **Header Typ** in den [Grundeinstellungen](grundeinstellungen.md).

## Hauptnavigation

Die Leiste mit den Hauptkategorien hat eigene Farben und eine eigene Typografie.

### Farben

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche der Leiste |
| Link Farbe | Die Hauptpunkte im Ruhezustand |
| Link Farbe (hover) | Die Hauptpunkte, wenn der Zeiger darüber liegt oder der Punkt aktiv ist |
| Border Top Farbe | Die Linie über der Leiste |

### Typografie

| Feld | Wirkung |
| --- | --- |
| Schriftgröße Multiplikator | Die Größe gegenüber der Standard-Schriftgröße aus dem Tab Typografie |
| Schriftstärke | Die Strichstärke der Hauptpunkte |
| Buchstabenabstand | Der Abstand zwischen den Zeichen |
| Text transformieren | **Normal** lässt die Kategorienamen wie in Shopware. **Großbuchstaben** setzt sie in Versalien. |
| Ausrichtung | Die Punkte stehen links, zentriert oder rechts in der Leiste. |

Bei der einzeiligen Navigation sitzt diese Leiste in derselben Zeile wie Logo und Icons. Das Flyout öffnet sich darunter.

## Flyout

Das Flyout ist das Menü, das unter einem Hauptpunkt aufgeht. Es hat eine gemeinsame Fläche und danach eine Typografie je Ebene.

### Farben und Kategoriebild

**Hintergrundfarbe** färbt die Fläche des Flyouts.

**Zeige Kategorie Bild in Flyout Navigation** blendet das Bild der Kategorie neben den Links ein. Das Bild pflegst du an der Kategorie in Shopware. Ohne Bild bleibt die Spalte leer, die Links bleiben stehen.

### Ebenen

Es gibt eigene Werte für die allgemeine Flyout-Schrift und zusätzlich für die Ebenen darunter. Die Ebene 0 ist die erste Reihe im Flyout. Darunter folgen Ebene 1, Ebene 2 und Ebene 3, also verschachtelte Unterkategorien.

Für jede Ebene stellst du ein:

| Feld | Wirkung |
| --- | --- |
| Link Farbe | Die Links dieser Ebene im Ruhezustand |
| Link Farbe (hover) | Die Links, wenn der Zeiger darüber liegt |
| Schriftgröße Multiplikator | Die Größe dieser Ebene |
| Schriftstärke | Die Strichstärke |
| Buchstabenabstand | Der Zeichenabstand |
| Text transformieren | **Normal** oder **Großbuchstaben** |

So kannst du die erste Reihe kräftiger setzen und tiefere Ebenen kleiner und ruhiger halten. Eine Ebene, die du nicht abweichend färbst, folgt den Werten, die in ihrem Feld hinterlegt sind.

{% hint style="info" %}
Die Kategorie-Navigation in der Seitenleiste einer Produktliste ist ein eigener Bereich. Ihre Farben und Ebenen stellst du unter [Sidebar-Navigation](produktlisting/sidebar-navigation.md) ein, nicht hier.
{% endhint %}
