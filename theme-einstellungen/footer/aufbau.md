# Aufbau des Footers

Im Tab **Footer**, Bereich **Grundeinstellungen**, entscheidest du, welche Spalten erscheinen, wie breit sie sind und in welcher Reihenfolge sie stehen.

## Spalten ein- und ausblenden

| Einstellung | Möglichkeiten |
| --- | --- |
| Benutzerdefinierte Spalte 1 bis 3 | als Spalte anzeigen oder nicht anzeigen |
| Newsletter Spalte | nicht anzeigen, als Spalte, oder als Reihe über dem Footer |
| Social Media Spalte | nicht anzeigen, als Spalte, oder als Reihe |
| Kontakt Spalte | als Spalte anzeigen oder nicht anzeigen |
| Zahlung und Versand Logos | nicht anzeigen, als Reihe oder als Spalte, wahlweise alle Logos, nur Zahlung oder nur Versand |

Die **Link-Spalten** sind das Service-Menü aus Shopware. Gibt es dort keine Einträge, wird die Liste nicht ausgegeben. Mit Einträgen bleibt die Liste sichtbar.

Die Social-Media-Zeile entfällt, wenn im Theme-Manager kein Social-Link gesetzt ist. Sobald mindestens eine URL eingetragen ist, erscheinen Zeile und Icons. Details stehen auf der Seite [Newsletter und Social Media](newsletter-social.md).

### Zahlung und Versand

Die Logos kommen aus den Zahlungs- und Versandarten in Shopware. Das Theme zeigt sie nur an, es lädt keine eigenen Logo-Dateien.

| Auswahl | Was du siehst |
| --- | --- |
| nicht anzeigen | keine Logos |
| als Reihe anzeigen (alle Logos) | Zahlung und Versand in einer Zeile |
| als Spalte anzeigen (alle Logos) | Zahlung und Versand als Footer-Spalte |
| als Reihe anzeigen (nur Zahlungs Logos) | nur die Zahlungsarten, als Zeile |
| als Spalte anzeigen (nur Zahlungs Logos) | nur die Zahlungsarten, als Spalte |
| als Reihe anzeigen (nur Versand Logos) | nur die Versandarten, als Zeile |
| als Spalte anzeigen (nur Versand Logos) | nur die Versandarten, als Spalte |

Die Überschriften dieser Bereiche änderst du über `mutoTheme.footer.paymentShippingHeadline`, `mutoTheme.footer.paymentHeadline` und `mutoTheme.footer.shippingHeadline`.

### Newsletter als Reihe

**als Reihe über dem Footer anzeigen** legt das Formular über die Spalten, über die volle Breite. **als Spalte anzeigen** stellt es neben die anderen Spalten. **nicht anzeigen** blendet das Formular aus, die Texte bleiben in den Textbausteinen erhalten.

### Social Media als Reihe

**als Reihe anzeigen** legt die Icons in eine eigene Zeile. **als Spalte anzeigen** stellt sie neben die anderen Spalten. **nicht anzeigen** blendet sie aus, auch wenn URLs eingetragen sind.

## Spaltenbreiten

Für Desktop und Tablet stellst du die Breite je Bereich ein. Die Werte folgen dem Zwölfer-Raster: **12 von 12** ist die volle Breite, **6 von 12** ist die Hälfte, **4 von 12** ist ein Drittel.

Du setzt die Breite getrennt für:

* Benutzerdefinierte Spalte 1, 2 und 3
* Newsletter-Spalte
* Social-Media-Icons-Spalte
* Kontakt-Spalte
* Zahlung/Versand-Spalte
* Link-Spalten

Auf dem Smartphone stehen die Spalten untereinander. Eine Breite von 12 von 12 auf dem Tablet lässt eine Spalte dort ebenfalls die volle Zeile einnehmen.

Die Summe der Breiten in einer Zeile sollte 12 ergeben. Liegt sie darüber, umbricht die nächste Spalte in die folgende Zeile.

## Reihenfolge

Die **Spaltenreihenfolgen** steuerst du mit Zahlen. Je höher die Zahl, desto weiter hinten steht die Spalte. Dieselbe Zahl für zwei Spalten lässt Shopware die ursprüngliche Folge entscheiden. Sinnvoll ist eine lückenlose Folge von vorn nach hinten, zum Beispiel 1 für Kontakt, 2 für die eigenen Spalten und 3 für den Newsletter.

Die Reihenfolge gilt für die Spaltenansicht. Eine Newsletter- oder Social-Zeile über dem Footer bleibt über den Spalten, unabhängig von ihrer Zahl.

## Texte der eigenen Spalten

Überschrift und Inhalt der drei eigenen Spalten, der Social-Zeile und des Newsletters liegen in den Textbausteinen. In den Inhaltsfeldern ist HTML erlaubt, zum Beispiel Absätze und Links.

```
mutoTheme.footer.customHeadline1
mutoTheme.footer.customContent1
mutoTheme.footer.customHeadline2
mutoTheme.footer.customContent2
mutoTheme.footer.customHeadline3
mutoTheme.footer.customContent3
```

Der Copyright-Text in der Leiste ganz unten ist `mutoTheme.footer.copyrightText`.
