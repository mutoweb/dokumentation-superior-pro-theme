# Typografie

Im Tab **Typografie** stellst du die Schriften des Shops ein. Oben liegen die Grundeinstellungen für den Fließtext, darunter die Überschriften von H1 bis H6.

Superior PRO liefert keine Schriftdateien mit. Die Schrift deiner Marke bindest du selbst ein und trägst den Namen danach hier ein. Die Schritte stehen auf der Seite [Eigene Schriftarten verwenden](../hilfen/eigene-schriftarten.md).

## Grundeinstellungen

### Schriftarten

**Schriftart Text** gilt für Absätze, Navigation, Footer und die übrigen Lauftexte, solange ein Element keine eigene Schrift setzt.

**Schriftart Überschrift** gilt für H1 bis H6. Trag denselben Namen ein, den du in `@font-face` als `font-family` verwendet hast, zum Beispiel `Roboto`.

Der Lauftext kann zwischen diesen beiden Schriften wählen. Das erweiterte Text-Element übernimmt die Schriften aus dem Theme und setzt nur die Farben lokal.

### Fließtext

| Feld | Wirkung |
| --- | --- |
| Schriftstärke | Die Strichstärke des Fließtexts, zum Beispiel 400 für normal und 700 für fett. Die Schriftdatei muss diese Stärke enthalten. |
| Zeilenhöhe (Faktor) | Der Zeilenabstand als Faktor der Schriftgröße. Ein höherer Wert macht den Text luftiger. |
| Textfarbe | Die Farbe von Absätzen und der Standard für Texte, die keine eigene Farbe haben. |
| Überschriftfarbe | Die Ausgangsfarbe für H1 bis H6. Eine Stufe, die du darunter einzeln färbst, löst sich davon. |

### Schriftgrößen

**Standard Schriftgröße** trägst du in rem ein. Ein Wert von `0.875` entspricht bei einer Browser-Basis von 16 px etwa 14 px. Dieser Wert ist die Basis für die Multiplikatoren.

Zwei weitere Multiplikatoren skalieren großen und kleinen Text gegenüber dieser Basis. Sie gelten shopweit, zum Beispiel für hervorgehobene und für nachgeordnete Texte. Die Überschriften haben darunter eigene Multiplikatoren.

## Überschriften H1 bis H6

Jede Stufe hat dieselben Felder. So bleibt die Hierarchie auf Startseite, Kategorien und Produktdetail einheitlich, und du kannst eine einzelne Stufe trotzdem absetzen.

| Feld | Wirkung |
| --- | --- |
| Farbe | Die Farbe dieser Stufe. Der Ausgangswert ist die Überschriftfarbe aus den Grundeinstellungen. Solange du die Stufe nicht einzeln färbst, zieht sie mit, wenn du die Überschriftfarbe änderst. |
| Schriftgröße Multiplikator | Die Größe gegenüber der Standard-Schriftgröße. H1 ist der größte Multiplikator, H6 der kleinste. |
| Zeilenhöhe (Faktor) | Der Zeilenabstand dieser Stufe. |
| Schriftstärke | Die Strichstärke. Sie braucht eine passende Schriftdatei. |
| Buchstabenabstand | Der Abstand zwischen den Zeichen. Ein kleiner positiver Wert lockert Überschriften, ein negativer zieht sie zusammen. |
| Text transformieren | **Normal** lässt die Schreibweise aus dem Inhalt. **Großbuchstaben** setzt die Stufe in Versalien, unabhängig davon, wie du sie im Editor getippt hast. |

Die Stufen gelten für Überschriften im Shopware-Text, im erweiterten Text-Element und in den übrigen Inhaltsbereichen, die die Theme-Überschriften nutzen. Eine **Überschrift Farbe** im erweiterten Text-Element überschreibt die Farbe nur in diesem Element.

{% hint style="info" %}
Änderst du nur die Überschriftfarbe in den Grundeinstellungen, folgen alle Stufen, deren Farbfeld noch auf diesen Wert zeigt. Eine Stufe, die du schon auf einen festen Farbwert gesetzt hast, bleibt bei diesem Wert.
{% endhint %}
