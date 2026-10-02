# HTML und CSS

Das Element **HTML / CSS** gibt eigenen Code an einer Stelle der Erlebniswelt aus. Es eignet sich für ein Widget, ein Siegel oder einen Einbettungscode, der nur auf dieser Seite liegen soll.

Code, der auf jeder Seite liegen soll, trägst du im Tab [Custom Code](../theme-einstellungen/custom-code.md) ein.

## Felder

| Feld | Wirkung |
| --- | --- |
| HTML Code | Das Markup, das im Shop erscheint. |
| CSS | Styles für dieses Element. Sie gelten zusammen mit dem HTML dieser Stelle. |
| Twig Kompilierung aktivieren | Wertet Twig in diesem Element aus. Damit kannst du mit Daten der aktuellen Seite arbeiten. |

Unter dem Schalter steht, ob die Kompilierung aktiv ist oder nicht.

Die Twig-Kompilierung ist standardmäßig aus. Schalte sie nur ein, wenn du Twig brauchst. Falscher Twig-Code kann die Ausgabe dieses Elements leer lassen. Der übrige Shop bleibt davon unberührt.

Ohne Twig wird der HTML-Code so ausgegeben, wie du ihn einträgst. Shopware-Variablen wie der Kundenname werden dann nicht ersetzt, sondern als Text gezeigt, wenn du sie hineinschreibst.

{% hint style="warning" %}
Einbettungen von Drittanbietern können Skripte laden. Prüf, ob der Anbieter das für deinen Shop erlaubt, und setze den Code nur auf der Seite ein, auf der das Widget erscheinen soll.
{% endhint %}
