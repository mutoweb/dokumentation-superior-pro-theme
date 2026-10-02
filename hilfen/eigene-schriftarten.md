# Eigene Schriftarten verwenden

Superior PRO bringt keine Schriftdateien mit. So bleibt das Theme schlank, und du lädst nur die Schriften, die zu deiner Marke gehören. Google Fonts und andere Webfonts bindest du lokal ein. Die Dateien liegen dann auf deinem Server, nicht bei einem externen Dienst.

Den Namen der Schrift trägst du danach im Tab [Typografie](../theme-einstellungen/typografie.md) ein, getrennt für Text und Überschriften.

## Schriften hochladen

Lege die Schriftdateien in den Ordner `/public/fonts/` deiner Shopware-Installation. Fehlt der Ordner `fonts`, lege ihn an.

Beispiel: Der Ordner `Roboto` liegt unter `/public/fonts/Roboto/` und enthält die Dateien `woff2` und `ttf`.

## Schrift per CSS anmelden

1. Öffne **Inhalte → Themes** und wähle **Superior PRO Theme**.
2. Wechsle in den Tab **Custom Code </>**.
3. Füge im Feld **CSS eingeben** einen `@font-face`-Block ein. Das Theme setzt das `<style>`-Tag selbst. Kommentare in diesem Feld können beim Kompilieren stören.

```css
@font-face {
  font-display: swap;
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  src: url('/fonts/Roboto/roboto-v30-latin-regular.woff2') format('woff2'),
       url('/fonts/Roboto/roboto-v30-latin-regular.ttf') format('truetype');
}
```

Für jede Schriftstärke, die du nutzen willst, brauchst du einen eigenen Block mit passendem `font-weight`, zum Beispiel `400` für normal und `700` für fett. Die Stärken in Typografie, Navigation und Footer müssen zu diesen Dateien passen. Eine Stärke ohne Datei lässt der Browser auf die nächste vorhandene Stärke ausweichen.

4. Speichere das Theme und warte, bis es kompiliert ist.
5. Trage im Tab **Typografie** als Schriftart den Namen ein, den du bei `font-family` gesetzt hast, im Beispiel `Roboto`. Für Überschriften kannst du denselben Namen oder eine zweite Schrift verwenden.

## Google Fonts herunterladen

Unter [google-webfonts-helper](https://gwfh.mranftl.com/fonts) lädst du eine Google-Schrift herunter und bekommst den passenden CSS-Code.

1. Suche die Schrift und wähle sie aus.
2. Setze die Häkchen bei den Stärken, die du brauchst, zum Beispiel 300, regular und 700.
3. Passe den Ordner im CSS an, zum Beispiel `/fonts/Roboto/`.
4. Lade das Paket herunter und lege die Dateien nach `/public/fonts/`.
5. Kopiere den CSS-Code in das Feld **CSS eingeben**, wie oben beschrieben.

Der Lauftext kann danach zwischen Text-Schrift und Überschriften-Schrift wählen. Eine dritte Schrift nur für ein Element gibt es nicht. Dafür bräuchtest du eine eigene CSS-Klasse im Tab Custom Code und am Block.
