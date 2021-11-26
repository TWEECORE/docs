+++
title = "Mietkalender und Abrechnungszeiträume"
weight = 1040
+++

Die Einrichtung von verschiedenen Mietkalender ist immer dann notwendig, wenn Sie mit verschiedenen Miettarifen arbeiten. Für einen Miettarif, der beispielsweise eine Abrechnung auch am Wochenende vorsieht, müssen Sie einen Miettarif und einen Kalender erzeugen, der diese Abrechnungsmethode ermöglicht. Sie können aber auch eine monatliche Pauschale konfigurieren, bei der der Preis immer gleich ist und es egal ist, ob der Monat nun 28 oder 31 Tage hat.

![Miettarif](/images/miettarif.jpg)

### Beispiel für eine taggenaue Abrechnung ohne Berechnung der Wochenenden und Feiertage:

Legen Sie hierzu einen neuen Miettarif an. Dieser sollte so benannt werden, dass die Anwender sofort erkennen, um was für eine Konstellation es sich handelt. Für unser Beispiel bedeutet das also, dass wir einen Miettarif TAG erstellen. Vom Mietpreis Typ wählen Sie nun tägliche Basis und können den Standard Mietkalender DE (Der Standardmietkalender DE sollte schon die Feiertage und Wochenende enthalten, ggf. sollten Sie das nochmals überprüfen) wählen. Im Feld für die Datumsformel tragen Sie bitte 1T ein. BusinessRental erkennt nun, dass Feiertage und Wochenenden nicht berechnet werden sollen. 

### Beispiel für eine monatliche Pauschale

Erstellen Sie einen neuen Miettarif. Für eine Pauschale ist es relevant, dass der Miettarif Typ den Wert Pauschale enthält. Menge in Tagen muss 0 sein, die Datumsformel für die Pauschale muss mit 1M befüllt werden. Der Mietkalender ist hier nicht erheblich, da der Kunde einen pauschalen Monatspreis berechnet bekommt und Feiertage nicht ins Gewicht fallen.

### Beispiel für eine tägliche Berechnung mit Feiertagen

Wenn Sie möchten, dass Feiertage berechnet werden, steuern Sie das über die verschiedenen Mietkalender. Exemplarisch können Sie den 25.12. (es handelt sich ja um einen bundeseinheitlichen Feiertag) berechnen, wenn Sie den Haken "Frei" im Mietkalender an diesem Tag entfernen. BusinessRental wird den Tag dann regulär berechnen. Denken Sie aber bitte daran, dass es sinnvoll ist, einen eigenen Kalender für dieses Szenario zu erstellen, da der Standardkalender zahlreiche Feiertage und Wochenenden hinterlegt hat.

### Abrechnungszeitraum

Sie können selbst bestimmen, über welchen Zeitraum sich die Abrechnung erstreckt. Üblicherweise werden Abrechnungen monatlich vorgenommen, Sie können jedoch auch alle 14 Tage oder wöchentlich abrechnen. Erstellen Sie einen neuen Abrechnungszeitraum und hinterlegen Sie eine entsprechende Datumsformel (14T für 14 Tage oder 1M für einen Monat) und grenzen Sie den Zeitraum ab. Sie können auswählen, ob Sie zum ersten Tag der Periode, einem festen Tag oder am letzten Tag der Periode abrechnen.

![Mietabrechnung](/images/abrechnung.jpg)