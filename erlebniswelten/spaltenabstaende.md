# Spaltenabstände

Den Abstand zwischen den Spalten eines Blocks stellst du direkt an diesem Block ein. Die frühere Methode über eine CSS-Klasse funktioniert weiterhin.

Der Abstand gilt nur für den Block, an dem du ihn setzt. Andere Blöcke auf derselben Seite bleiben unverändert.

## Über die Block-Einstellungen

1. Klicke den Block in der Erlebniswelt an.
2. Öffne rechts den Bereich **Layout**.
3. Wähle unter **Spaltenabstand** einen Wert.

Der gewählte Abstand ist in der Zeichenfläche nur an diesem Block sichtbar. **Nicht gesetzt** und **Standard** behalten dort den Abstand der Administration.

| Auswahl | Wirkung |
| --- | --- |
| Nicht gesetzt | Der normale Abstand des Themes bleibt. Es wird keine eigene Klasse geschrieben. |
| Standard | Der Standard-Abstand des Themes wird ausdrücklich gesetzt. |
| 0 px | Der Abstand entfällt. Die Spalten stoßen aneinander. |
| 5 px bis 50 px | Fester Abstand in 5-px-Schritten. |

Weitere CSS-Klassen trägst du weiterhin in das Feld **CSS-Klassen** darunter ein. Die Abstandsklasse aus der Auswahl und deine eigenen Klassen stehen nebeneinander.

In einer Sektion über die volle Breite behalten Spaltenblöcke ihren Abstand. Der Inhalt bleibt am Rand, die Seite scrollt nicht seitlich.

## Über eine CSS-Klasse

Dieselbe Wirkung erreichst du, indem du eine Klasse in **CSS-Klassen** schreibst:

```
muto-gutter-0
muto-gutter-5
muto-gutter-10
muto-gutter-15
muto-gutter-20
muto-gutter-25
muto-gutter-30
muto-gutter-35
muto-gutter-40
muto-gutter-45
muto-gutter-50
```

`muto-gutter-default` entspricht der Auswahl **Standard**. Liegen mehrere Abstandsklassen im Feld, gilt die letzte. Die Auswahl im Dropdown zeigt die Klasse, die im Feld steht, und ersetzt sie, wenn du einen anderen Wert wählst.

Neue Blöcke starten ohne eigenen Seitenrand links und rechts, so wie die Standard-Blöcke von Shopware. Den seitlichen Abstand der ganzen Sektion stellst du an der Sektion ein, nicht mit dem Spaltenabstand.
