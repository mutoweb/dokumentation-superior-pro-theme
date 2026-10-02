# Textbausteine

Texte, die das Theme fest im Layout ausgibt, änderst du unter **Einstellungen → Textbausteine**. Die Suche nach `mutoTheme` listet alle Bausteine des Themes. Jede Sprache pflegst du im Snippet-Set dieser Sprache.

Ein leerer Baustein gibt an dieser Stelle keinen Text aus. Die Übersetzung einer anderen Sprache bleibt davon unberührt.

## Footer

| Baustein | Erscheint als |
| --- | --- |
| `mutoTheme.footer.paymentShippingHeadline` | Überschrift, wenn Zahlung und Versand gemeinsam gezeigt werden |
| `mutoTheme.footer.paymentHeadline` | Überschrift nur über den Zahlungslogos |
| `mutoTheme.footer.shippingHeadline` | Überschrift nur über den Versandlogos |
| `mutoTheme.footer.copyrightText` | Text in der Leiste ganz unten. HTML ist erlaubt. |
| `mutoTheme.footer.customHeadline1` | Überschrift der ersten eigenen Spalte |
| `mutoTheme.footer.customContent1` | Inhalt der ersten eigenen Spalte |
| `mutoTheme.footer.customHeadline2` | Überschrift der zweiten eigenen Spalte |
| `mutoTheme.footer.customContent2` | Inhalt der zweiten eigenen Spalte |
| `mutoTheme.footer.customHeadline3` | Überschrift der dritten eigenen Spalte |
| `mutoTheme.footer.customContent3` | Inhalt der dritten eigenen Spalte |
| `mutoTheme.footer.socialmediaHeadline` | Überschrift über den Social-Icons |
| `mutoTheme.footer.newsletterHeadline` | Überschrift des Newsletter-Blocks |
| `mutoTheme.footer.newsletterContent` | Absatz über dem Newsletter-Feld |

In den Inhaltsfeldern ist HTML erlaubt, zum Beispiel Absätze und Links. Ob die Spalte sichtbar ist, entscheidest du im Tab Footer. Ein Text ohne eingeschaltete Spalte erscheint nicht. Siehe [Aufbau des Footers](../theme-einstellungen/footer/aufbau.md).

## USP

| Baustein | Erscheint als |
| --- | --- |
| `mutoTheme.usp.arialabel` | Beschriftung der Leiste für Screenreader, nicht sichtbar |
| `mutoTheme.usp.headline-1` bis `headline-4` | Überschrift des Vorteils |
| `mutoTheme.usp.text-1` bis `text-4` | Text unter der Überschrift |
| `mutoTheme.usp.link-1` bis `link-4` | Ziel des Vorteils, nur wenn Verlinkungen aktiv sind |

In den USP-Texten ist `<br>` für einen Zeilenumbruch erlaubt. Die Schalter der Leiste stehen auf der Seite [USP](../theme-einstellungen/usp.md).

## TopBar und Cookie

| Baustein | Erscheint als |
| --- | --- |
| `mutoTheme.topbar.marketingText` | Der kurze Text in der Leiste über dem Header. HTML wie `<strong>` ist erlaubt. |
| `mutoTheme.cookie.headline` | Die Überschrift des Cookie-Hinweises |

Der Marketingtext erscheint nur, wenn **Zeige Marketing Text** im Tab Header aktiv ist und die TopBar nicht auf **nicht sichtbar** steht.

## Bildergalerie

Die Beschriftungen der Lightbox sind für Screenreader gedacht. Die sichtbaren Bildunterschriften kommen aus den Medien in der Galerie, nicht aus diesen Bausteinen.

| Baustein | Erscheint als |
| --- | --- |
| `mutoTheme.lightbox.dialog` | Name des Bild-Viewers |
| `mutoTheme.lightbox.close` | Schließen |
| `mutoTheme.lightbox.prev` | Vorheriges Bild |
| `mutoTheme.lightbox.next` | Nächstes Bild |
| `mutoTheme.lightbox.loadError` | Hinweis, wenn ein Bild nicht geladen werden konnte |
| `mutoTheme.lightbox.showImage` | Bild anzeigen |
