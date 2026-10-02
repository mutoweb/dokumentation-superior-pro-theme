# Custom Code

Im Tab **Custom Code </>** fügst du HTML, CSS und JavaScript ein, das auf jeder Seite des Themes ausgegeben wird. Die Felder sind Code-Editoren. Die meisten Shops brauchen diesen Tab nicht.

Code, der nur auf einer Seite liegen soll, trägst du besser ins Element [HTML und CSS](../erlebniswelten/html-css.md) ein.

## HTML im Head

Das Feld **HTML eingeben** landet im `<head>` jeder Seite. Typisch sind Meta-Tags, mit denen ein Anbieter die Domain prüft.

```html
<meta name="google-site-verification" content="dein-code">
<meta name="facebook-domain-verification" content="dein-code">
```

Trag das Markup so ein, wie es im Head stehen soll. Ein umschließendes `<head>` brauchst du nicht.

## CSS im Head

Das Feld **CSS eingeben** landet ebenfalls im Head, aber nur wenn etwas eingetragen ist. Das Theme setzt das `<style>`-Tag selbst. Trage deshalb reines CSS ein, ohne `<style>`.

Damit überschreibst du vorhandene Klassen oder legst eigene an, die du danach an CMS-Blöcken als CSS-Klasse verwendest. Vermeide Kommentare im Feld, sie können beim Kompilieren stören.

Die Einbindung eigener Schriften läuft über genau dieses Feld. Die Schritte stehen auf der Seite [Eigene Schriftarten verwenden](../hilfen/eigene-schriftarten.md).

Nach dem Speichern kompiliert Shopware das Theme neu. Erst dann ist das CSS im Shop sichtbar.

## JavaScript

Das Feld **Javascript eingeben** wird am Ende der Seite ausgegeben, sobald etwas eingetragen ist. Das Theme setzt das `<script>`-Tag selbst. Trage den Code ohne `<script>` ein.

Ein fehlerhaftes Skript kann den Shop auf jeder Seite stören, weil es überall geladen wird. Prüf den Code zuerst auf einer unkritischen Seite, oder setze ein Widget lieber nur in die Erlebniswelt, auf der es gebraucht wird.

{% hint style="warning" %}
Code aus diesem Tab gilt für den gesamten Shop. Für ein einzelnes Siegel, einen Kalender oder ein Formular auf einer Landingpage ist das Element HTML und CSS die passendere Stelle.
{% endhint %}
