# Newsletter und Social Media

Beide Bereiche liegen im Tab **Footer**. Ob sie als Spalte, als Reihe oder gar nicht erscheinen, stellst du unter [Aufbau](aufbau.md) ein.

## Newsletter

Das Anmeldeformular sitzt im Footer und erscheint auf jeder Seite. Es ist kein Element in den Erlebniswelten.

Überschrift und Absatztext änderst du über:

```
mutoTheme.footer.newsletterHeadline
mutoTheme.footer.newsletterContent
```

### Farben des Blocks

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche hinter Überschrift, Text und Formular |
| Textfarbe | Überschrift und Absatz |
| Buttonfarbe | Der Anmelden-Button |

### E-Mail-Feld

Das Feld hat eigene Farben und startet mit denselben Werten wie die [Formulare](../formulare.md). Du kannst es davon lösen, ohne die Felder im Checkout zu ändern.

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe Eingabefeld | Die Fläche des E-Mail-Feldes |
| Textfarbe Eingabefeld | Die eingetippte Adresse |

Der Rahmen des Feldes folgt der Hintergrundfarbe, auch im Fokus. Der Platzhalter nutzt die Textfarbe mit geringerer Deckkraft. Ein Preset-Wechsel setzt beide Farben wieder auf die Formularfeld-Farben zurück.

Die Checkbox zur Datenschutzerklärung und Hinweise zum Captcha erscheinen erst, nachdem eine E-Mail-Adresse eingegeben wurde. So bleibt das Formular kompakt. Datenschutztext und Captcha kommen aus den Shopware-Einstellungen, nicht aus dem Theme.

## Social Media

### Farben

| Feld | Wirkung |
| --- | --- |
| Hintergrundfarbe | Die Fläche hinter dem Icon |
| Hintergrundfarbe (hover) | Dieselbe Fläche, wenn der Zeiger darüber liegt |
| Icon Farbe | Das Symbol |
| Icon Farbe (hover) | Das Symbol bei Hover |
| Rahmenfarbe | Der Rand des Icons |
| Rahmenfarbe (hover) | Der Rand bei Hover |

**Zeige Social Media Namen als Tooltip** blendet den Netzwerknamen beim Darüberfahren ein, zum Beispiel „Instagram“. Die Tooltip-Farben aus dem Tab Verschiedenes gelten auch hier.

Die Überschrift über den Icons ist der Textbaustein `mutoTheme.footer.socialmediaHeadline`.

### Kanäle

Trag nur die URLs ein, die du wirklich verlinken willst. Ohne URL erscheint kein Icon. Ist keine einzige URL gesetzt, entfällt die Social-Zeile komplett, auch wenn die Spalte auf „anzeigen“ steht.

Verfügbar sind:

Facebook, X, Instagram, Pinterest, YouTube, Vimeo, Google, Tumblr, LinkedIn, Xing, Snapchat, Amazon, eBay, Etsy, WhatsApp, TikTok, Telegram und Discord.

Jede URL muss mit `https://` beginnen. Ein leeres Feld ist gültig und bedeutet: dieses Icon nicht zeigen.
