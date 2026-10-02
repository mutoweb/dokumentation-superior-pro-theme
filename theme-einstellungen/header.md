# Header

Im Tab **Header** gestaltest du Logo, Kopfzeile, Suchfeld und die Top-Leiste. Ob die Navigation einzeilig oder mehrzeilig ist, ob der mobile Header in einer Zeile steht und ob der Header beim Scrollen wieder eingeblendet wird, stellst du unter [Grundeinstellungen](grundeinstellungen.md) ein.

## Logo

Die maximale Breite des Logos legst du getrennt fest:

| Feld | Wirkung |
| --- | --- |
| Logo maximale Breite (Desktop) | Obergrenze auf großen Bildschirmen |
| Logo maximale Breite (Tablet) | Obergrenze auf Tablets |
| Logo maximale Breite (Mobil) | Obergrenze auf Smartphones |

Das Logo wird nicht über diese Breite hinaus skaliert. Ein SVG, das kleiner ist als die angegebene Breite, bleibt in der vorgesehenen Größe. Beim einzeiligen mobilen Header schrumpft das Logo nur dann unter die Mobilbreite, wenn der Platz neben den Buttons enger wird.

Das Logo selbst lädst du in Shopware unter den Einstellungen des Verkaufskanals hoch, nicht in diesem Tab.

### Favicon und Share-Icon

**Favicon** ist das kleine Symbol im Browser-Tab.

**App- & Share-Icon** ist das Bild, das erscheint, wenn jemand den Shop auf dem Homescreen ablegt oder eine Seite teilt.

Beide Bilder kommen aus der Medienverwaltung. Ohne eigenes Bild nutzt der Shop das Standard-Icon.

## Kopfzeile

Für den Header stellst du ein:

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche hinter Logo und Icons |
| Icon Farbe | Konto, Warenkorb, Merkzettel und Suche im Ruhezustand |
| Icon Farbe (hover) | Dieselben Icons, wenn der Zeiger darüber liegt |
| Zeige Icon Tooltip | Blendet die kleinen Hinweise an den Icons ein oder aus |
| Header Mindesthöhe | Eine untere Grenze, damit Logo und Icons nicht zusammengedrückt werden |

Die Farben der Tooltips liegen im Tab [Verschiedenes](verschiedenes.md). Die Merkzettel-Farben auf der Produktbox stellst du dort ebenfalls ein. Sie sind von den Header-Icons getrennt.

## Suchfeld

Die Farben des Suchfelds sind vom übrigen Formular getrennt, damit die Suche im Kopf anders aussehen kann als die Felder im Checkout.

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Fläche des Eingabefelds |
| Hintergrundfarbe (focus) | Fläche, während du tippst |
| Text | Die eingegebene Suche |
| Text (focus) | Die Schrift im Fokus |
| Rahmenfarbe | Der Rand im Ruhezustand |
| Rahmenfarbe (focus) | Der Rand im Fokus |
| Icon Farbe | Die Lupe |
| Icon Farbe (hover) | Die Lupe bei Hover |
| Placeholder Farbe | Der Hinweistext, solange das Feld leer ist |
| Hintergrundfarbe Balken | Die Leiste, in der das Feld sitzt |
| Rahmenradius | Die Abrundung nur dieses Feldes |

Ob das Feld immer sichtbar ist oder erst nach einem Klick auf das Icon, entscheidet **Anzeige des Suchfeldes im Header** in den [Grundeinstellungen](grundeinstellungen.md). Unter 768 px, sobald das Feld unter Logo und Buttons liegt, öffnest und schließt du es über die Lupe. Ab 768 px bleibt es offen.

## TopBar

Die TopBar sitzt über dem Header. Ob sie einklappbar, dauerhaft sichtbar oder ausgeblendet ist, stellst du mit **TopBar Typ** in den [Grundeinstellungen](grundeinstellungen.md) ein.

### Farben

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche der Leiste |
| Untere Rahmenfarbe | Die Linie zwischen TopBar und Header |
| Textfarbe | Schrift und Links im Ruhezustand |
| Textfarbe (hover) | Schrift und Links, wenn der Zeiger darüber liegt |

### Inhalte

Zwei Schalter blenden Inhalte ein, ohne die Leiste selbst ein- oder auszublenden:

* **Zeige Anmelden und Registrieren Link** zeigt die Links zum Kundenkonto.
* **Zeige Marketing Text** zeigt den kurzen Text in der Leiste.

Den Marketingtext pflegst du als Textbaustein `mutoTheme.topbar.marketingText`. HTML wie `<strong>` ist dort möglich. Ist der TopBar-Typ auf **nicht sichtbar** gestellt, bleiben Text und Links gespeichert, die Leiste wird aber nicht ausgegeben.
