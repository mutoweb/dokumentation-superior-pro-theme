# USP

Die USP-Leiste zeigt bis zu vier Vorteile, zum Beispiel Versand, Zahlung oder Rückgabe. Sie sitzt shopweit an der vorgesehenen Stelle im Layout, nicht in einer einzelnen Erlebniswelt. Jeder Block besteht aus einer Überschrift, einem kurzen Text und optional einem Link.

Du öffnest sie im Tab **USP**.

## Ein- und ausblenden

| Feld | Wirkung |
| --- | --- |
| USP aktiv? | **ja** zeigt die Leiste. **nein** blendet sie vollständig aus. Texte und Farben bleiben gespeichert. |
| USP Verlinkungen aktiv? | **ja** macht die Blöcke klickbar. **nein** zeigt Überschrift und Text ohne Link. |
| USP Subtext aktiv? | **ja** zeigt den Text unter der Überschrift. **nein** zeigt nur die Überschrift. |
| Ausrichtung | Der Inhalt steht linksbündig, zentriert oder rechtsbündig. |

Ein Vorteil ohne Überschrift nimmt keinen sichtbaren Platz ein. Du musst nicht genutzte Blöcke nicht einzeln abschalten.

## Inhalte

Die Texte änderst du unter **Einstellungen → Textbausteine**. Suche nach `mutoTheme.usp`.

```
mutoTheme.usp.headline-1
mutoTheme.usp.text-1
mutoTheme.usp.link-1

mutoTheme.usp.headline-2
mutoTheme.usp.text-2
mutoTheme.usp.link-2

mutoTheme.usp.headline-3
mutoTheme.usp.text-3
mutoTheme.usp.link-3

mutoTheme.usp.headline-4
mutoTheme.usp.text-4
mutoTheme.usp.link-4
```

In den Texten ist ein Zeilenumbruch mit `<br>` erlaubt. Die Links sind normale URLs oder shopinterne Pfade. Ist **USP Verlinkungen aktiv?** auf **nein** gestellt, werden die Links nicht ausgegeben.

`mutoTheme.usp.arialabel` ist die Beschriftung der Leiste für Screenreader, zum Beispiel „Unsere Vorteile“. Sie erscheint nicht als sichtbare Überschrift.

## Farben

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche der Leiste |
| Hintergrundfarbe (hover) | Die Fläche, wenn der Zeiger über einem verlinkten Block liegt |
| Überschriftfarbe | Die vier Überschriften |
| Überschriftfarbe (hover) | Die Überschrift bei Hover |
| Textfarbe | Der Text unter der Überschrift |
| Textfarbe (hover) | Der Text bei Hover |
| Rahmen Farbe | Die Linie um die Leiste oder zwischen den Blöcken |

## Typografie

Überschrift und Text haben getrennte Werte:

| Feld | Wirkung |
| --- | --- |
| Schriftgröße Multiplikator | Die Größe gegenüber der Standard-Schriftgröße |
| Zeilenhöhe (Faktor) | Der Zeilenabstand |
| Schriftstärke | Die Strichstärke |
| Buchstabenabstand | Der Zeichenabstand |
| Text transformieren | **Normal** oder **Großbuchstaben** |

So kann die Überschrift in Versalien stehen und der Subtext in normaler Schreibweise bleiben.
