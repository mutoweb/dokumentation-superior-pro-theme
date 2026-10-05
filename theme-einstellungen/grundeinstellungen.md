# Grundeinstellungen

Im Tab **Grundeinstellungen** legst du die Farben und das Grundlayout des Shops fest. Viele spätere Farbfelder verweisen auf diese Werte. Änderst du hier die Primärfarbe, ziehen die verknüpften Stellen mit.

Logo-Breiten, Suchfeld-Farben und die TopBar-Farben liegen im Tab [Header](header.md). Ob die Navigation einzeilig ist und ob der Header beim Scrollen mitläuft, entscheidest du hier.

## Farb-Preset

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Oben findest du das Feld **Farb-Preset**. Damit setzt du mit einem Klick eine vorbereitete Farbpalette.

| Preset              | Charakter                                   |
| ------------------- | ------------------------------------------- |
| Kein Preset gewählt | Ändert nichts. Das ist der Ausgangszustand. |
| Preset Green        | Salbeigrün                                  |
| Preset Orange-Blue  | Orange und Schieferblau                     |
| Preset Mono         | Schwarz, Weiß und Grau                      |
| Preset Yellow-Black | Amber und Schwarz                           |

Ein Preset greift nur, wenn du es aktiv auswählst. Dabei werden zuerst die Farb-Standards gesetzt und danach die Palette. Der Wechsel setzt auch Hintergrund und Text des Newsletter-E-Mail-Feldes auf die Formularfeld-Farben zurück.

Änderst du danach eine Farbe von Hand, springt die Auswahl zurück auf **Kein Preset gewählt**. Deine manuellen Farben bleiben dabei erhalten. Ein Preset überschreibt sie erst wieder, wenn du es erneut auswählst.

## Farben

**Primärfarbe** und **Sekundärfarbe** sind die beiden Hauptfarben des Shops. Viele Farbfelder zeigen noch auf diese Werte. Änderst du die Primärfarbe, ändern sich auch alle Felder, die du nicht selbst überschrieben hast. Leere Farbfelder in Teaser, Accordion, Tabs, Seiten-Header und Lauftext nutzen ebenfalls die Primärfarbe.

**Rahmen** färbt Linien und Rahmen im Inhaltsbereich. Staffelpreise und einige Karten greifen darauf zurück.

**Hintergrund Body** ist der Hintergrund der gesamten Seite, also auch der Bereich außerhalb des Inhalts, wenn der Boxed-Modus aktiv ist.

**Hintergrundfarbe Inhalt** färbt den Inhaltsbereich, sobald der Boxed-Modus aktiv ist. Ohne Boxed-Modus siehst du vor allem den Body-Hintergrund.

### Status-Ausgaben

Diese vier Farben markieren Rückmeldungen im Shop, zum Beispiel nach dem Speichern einer Adresse oder bei einem Hinweis im Checkout.

| Feld        | Typische Verwendung |
| ----------- | ------------------- |
| Erfolg      | Bestätigungen       |
| Information | neutrale Hinweise   |
| Hinweis     | Warnungen           |
| Fehler      | Fehlermeldungen     |

### E-Commerce

| Feld               | Wirkung                                                |
| ------------------ | ------------------------------------------------------ |
| Preis              | die normale Preisfarbe in Produktbox und Produktdetail |
| Kaufen-Button      | Hintergrund des Kauf-Buttons                           |
| Kaufen-Button Text | Schrift auf dem Kauf-Button                            |

Die Produktbox kann Preis und Streichpreis zusätzlich eigen färben. Diese Felder liegen unter [Produktboxen](produktlisting/produktboxen.md). Solange du sie nicht abweichend setzt, bleibt der Preis hier die Quelle.

## Header-Grundentscheidungen

### Header Typ

**Header Typ** entscheidet, wie Logo, Icons und Navigation zueinander stehen.

* **mehrzeilig:** Die Navigation liegt in einer eigenen Zeile unter Logo und Icons. Das Logo bleibt zentriert. Diese Variante trägt viele Hauptkategorien.
* **einzeilig:** Navigation, Logo und Icons teilen sich eine Zeile. Die Leiste wirkt schmaler und passt, wenn du wenige Hauptpunkte hast. Das Flyout öffnet sich unter dieser Zeile.

### Mobiler Header einzeilig

**Mobiler Header einzeilig** gilt unter 576 px.

* **nein** behält Logo und Aktionsbuttons untereinander. Das ist der Ausgangswert.
* **ja** legt Logo und Buttons in eine Zeile. Die Suche bleibt darunter.

Beim einzeiligen mobilen Header sitzt das Logo unter 768 px links neben den Buttons. Es behält die maximale Mobilbreite aus dem Tab Header und wird nur kleiner, wenn der Platz daneben enger wird. Ab 768 px und im zweizeiligen Header bleibt das Logo zentriert.

### Anzeige des Suchfeldes

**Anzeige des Suchfeldes im Header** schaltet zwischen zwei Darstellungen:

* **Suchfeld mit Such-Icon ein-/ausblenden:** Die Suche öffnet sich erst nach einem Klick auf das Icon.
* **Suchfeld immer zeigen:** Das Eingabefeld ist dauerhaft sichtbar.

Liegt das Suchfeld auf kleinen Bildschirmen unter Logo und Buttons, lässt es sich unter 768 px über die Lupe ein- und ausblenden. Ab 768 px bleibt es offen. Die Farben des Feldes stellst du im Tab [Header](header.md) ein.

### Fixierter Header

**Fixierte Header aktiv?** hat drei Stufen.

| Auswahl               | Verhalten                                                                                                                                                                                                      |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Deaktiviert           | Der Header scrollt mit dem Inhalt nach oben und bleibt dort. Es gibt keinen fixierten Header.                                                                                                                  |
| Nur große Bildschirme | Ab 769 px scrollt der Header beim Runterscrollen aus dem Blick und kommt wieder, sobald du nach oben scrollst. Ganz oben sitzt er an seiner normalen Position. Auf dem Smartphone bleibt dieses Verhalten aus. |
| Alle Bildschirmgrößen | Dieselbe Bewegung gilt auch auf dem Handy.                                                                                                                                                                     |

**Schatten bei fixiertem Header?** zeichnet unter der fixierten Leiste einen Schatten, sobald sie eingeblendet ist.

* **ja** zeigt den Schatten.
* **nein** lässt die Leiste ohne Schatten.

Der Schatten liegt nicht auf der Hauptnavigation. Ein Schatten unter dem Flyout bleibt davon unabhängig. Ohne fixierten Header siehst du diesen Schatten nicht.

## Boxed-Modus

Standardmäßig läuft der Shop über die volle Browserbreite.

* **Boxed Modus aktiv?** Mit **ja** wird der Inhalt auf eine maximale Breite begrenzt und zentriert. Der Bereich daneben nutzt **Hintergrund Body**.
* **Boxed Modus Schatten?** Legt um den Inhaltscontainer einen Schatten. Wirkt zusammen mit dem Boxed-Modus.
* **Boxed Modus Breite (in px)** setzt diese maximale Breite. Trag den Wert als Zahl in Pixel ein.

## TopBar

**TopBar Typ** steuert die Leiste über dem Header. Dort sitzen Sprach- und Währungsumschaltung, ein Marketingtext und die Links zu Anmeldung und Registrierung.

| Auswahl          | Verhalten                                                                                                                    |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| ein-/ausklappbar | Ein Icon klappt die Leiste auf und zu. Der Browser merkt sich den Zustand auch nach einem Reload und beim Wechsel der Seite. |
| immer sichtbar   | Die Leiste bleibt offen.                                                                                                     |
| nicht sichtbar   | Die Leiste ist ausgeblendet. Farben und Texte bleiben gespeichert.                                                           |

Farben, der Marketingtext und die beiden Schalter für Anmeldung und Marketing liegen im Tab [Header](header.md).

## Cookie-Hinweis

**Cookie-Erlaubnis-Typ** setzt den Cookie-Hinweis entweder **standard (unten)** oder **mittig** in die Seite.

Die Überschrift des Hinweises änderst du über den Textbaustein `mutoTheme.cookie.headline`. Den übrigen Cookie-Text pflegt Shopware in den Cookie-Einstellungen, nicht im Theme.

## Border Radius

Drei Werte runden Flächen im ganzen Shop. Der Wert ist jeweils in Pixel. `0` lässt die Ecken eckig.

| Feld     | Wirkt auf                                                                                                                 |
| -------- | ------------------------------------------------------------------------------------------------------------------------- |
| Buttons  | Schaltflächen, unter anderem Warenkorb, Mengenauswahl, Pagination und den Entfernen-Button auf dem Merkzettel             |
| Inputs   | Formularfelder. Die Verpackungseinheit am Mengenfeld nutzt rechts denselben Radius.                                       |
| Elemente | Bilder, Karten, Teaser Image Box, erweitertes Text-Element, Modal-Fenster, Staffelpreis-Tabelle und Eigenschaften-Tabelle |

Die Produkt-Tabs im individuellen Stil nutzen den Button-Radius. Details stehen auf der Seite [Produktseite](produktseite.md). Das Suchfeld im Header kann einen eigenen Radius haben, der nur dort gilt.

## Preloader

Der Preloader liegt im selben Tab unter **Preloader**. Er deckt den Shop kurz ab, während die Seite lädt, und bleibt mindestens einen kurzen Moment sichtbar, damit er nicht flackert.

**Preloader Design** bietet:

| Auswahl               | Darstellung          |
| --------------------- | -------------------- |
| Preloader deaktiviert | kein Ladebildschirm  |
| Balken                | ein laufender Balken |
| Kreis                 | ein Kreis            |
| Wellen                | Wellen               |
| Herz                  | ein Herz             |
| Punkte                | Punkte               |

**Hintergrundfarbe** färbt die Fläche während des Ladens. **Loading Icon Farbe** färbt das Symbol darauf.

Während Filter in einer Produktliste neu laden, zeigt jede Produktbox einen eigenen Kreis in der Primärfarbe. Das ist nicht dieser Preloader und hat kein eigenes Feld.
