# Produktseite

Im Tab **Produktseite** färbst du die Reiter unter der Kaufbox. Das sind Beschreibung, Bewertungen und die weiteren Tabs, die Shopware auf der Produktdetailseite ausgibt.

Die Tabs in den Erlebniswelten sind ein anderes Element. Deren Farben stellst du am Element [Tabs](../erlebniswelten/tabs.md) ein, nicht hier.

## Style

**Style** hat zwei Stände:

* **standard** belässt die Shopware-Darstellung. Die Farbfelder darunter greifen dann nicht.
* **individuell** nutzt die Farben aus diesem Tab.

## Farben

Sobald du **individuell** wählst, stehen diese Felder zur Verfügung:

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe Inhaltsbereich | Die Fläche hinter dem Tab-Inhalt. Für keine Fläche trägst du das Wort `transparent` ein. |
| Button Hintergrundfarbe | Der Reiter im Ruhezustand |
| Button Hintergrundfarbe (hover/active) | Der Reiter bei Hover und der aktive Reiter |
| Button Textfarbe | Die Schrift auf dem Reiter |
| Button Textfarbe (hover/active) | Die Schrift bei Hover und auf dem aktiven Reiter |
| Button Hintergrundfarbe (mobil) | Der Reiter auf dem Smartphone |
| Button Textfarbe (mobil) | Die Schrift auf dem Smartphone |

## Ecken

Im individuellen Stil nutzt der Tab-Inhalt ab Tablet den Button-Radius aus den [Grundeinstellungen](grundeinstellungen.md) an oben rechts, unten rechts und unten links. Oben links bleibt eckig, damit der erste Reiter bündig anschließt.

Auf dem Smartphone nutzen die Reiter denselben Button-Radius an allen Ecken. Der Standard-Stil bleibt eckig, wie Shopware ihn vorgibt.

## Weitere Flächen auf der Produktseite

Diese Flächen haben kein eigenes Farbfeld. Sie folgen den Grundeinstellungen:

* Der Kopf der Staffelpreise nutzt die Rahmenfarbe. Die Preiszeilen sind etwas heller als der Rahmen.
* Die Staffelpreis-Tabelle und die Eigenschaften-Tabelle nutzen den Element-Radius.
* Unter Tablet stehen Mengenfeld inklusive Einheit und Warenkorb-Button untereinander über die volle Breite. Nur das Zahlenfeld wächst. Ab Tablet bleiben beide nebeneinander.

Die Produktgalerie auf der Detailseite schiebt ihre Bilder. Der Übergang **Fade** im Tab Verschiedenes gilt für den Bildslider in den Erlebniswelten, nicht für diese Galerie.
