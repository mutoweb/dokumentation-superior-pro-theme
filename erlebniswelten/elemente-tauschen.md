# Elemente einfügen und tauschen

Die Elemente von Superior PRO setzt du in jede Spalte eines Blocks, auch in die Sidebar einer Erlebniswelt. Dieselben Elemente gibt es als fertige Blöcke, wenn das Raster schon stimmen soll.

## Ein Element tauschen

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

1. Öffne die Erlebniswelt der Seite, der Kategorie oder der Landingpage.
2. Klicke in der gewünschten Spalte auf das Symbol **Element tauschen**.
3. Im Fenster siehst du alle verfügbaren Elemente, auch die von Shopware und von anderen Plugins.
4. Wähle das Element, zum Beispiel **Teaser Image Box**, und bestätige.
5. Über das Zahnrad an der Spalte öffnest du **Inhalt** und **Einstellungen**.

Ein Tausch ersetzt das Element in dieser Spalte. Bilder und Texte des vorherigen Elements bleiben nicht erhalten. Die CSS-Klassen des Blocks bleiben stehen.

{% columns %}
{% column %}
## Fertige Blöcke statt leerer Spalten

Unter **+ Elemente (SuperiorPRO)** liegen Blöcke, in denen das passende Element schon eingesetzt ist. Drei Teaser legst du so in einem Schritt an, ohne das Raster selbst zu bauen. Die Übersicht steht auf der Seite [Fertige Blöcke](fertige-bloecke.md).

Neue Raster unter **+ Spalten (SuperiorPRO)** starten mit dem [Leeren Element](leeres-element.md). Du tauschst den Platzhalter danach gegen den Inhalt.
{% endcolumn %}

{% column %}
<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

## Blöcke mit jeweils 2 Elementen pro Spalte

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

In den Blöcken **Bild und erweitertes Text-Element** liegen Bild und Textkachel in einer Spalte übereinander. An der gemeinsamen Kante entfällt der Element-Radius, damit beide Flächen eine Kachel bilden. Tauschst du die Reihenfolge, wandert die eckige Kante mit.

Dasselbe gilt, wenn du in so einer Spalte eine Teaser Image Box einsetzt. Bei Mindesthöhe wächst die Box bis zur längsten Spalte, der Text bleibt an der Box.

## Leere Farben

Bei Teaser Image Box, Accordion, Tabs, Seiten-Header und Lauftext gilt: Ein leeres Farbfeld übernimmt die Farben aus dem Theme. Eine Farbe, die du im Element setzt, gilt nur für dieses Element.

In der Vorschau der Administration siehst du dafür neutrale Platzhalterfarben. Im Shop greifen die Theme-Farben. Ein leerer Teaser-Button ist in der Vorschau weiß. Leere Accordion- und Tab-Köpfe nutzen dort ein helles Grau.

## Datenzuordnung an Kategorie oder Produkt

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Bei Seiten-Header, Bild und erweitertem Text-Element kannst du Felder per Datenzuordnung an Kategorie oder Produkt binden, wo Shopware das Mapping anbietet. Der Inhalt kommt dann aus dem Datensatz der Seite, nicht aus einem fest eingetippten Text. Eine feste Eingabe überschreibt die Datenzuordnung, sobald du sie speicherst.
