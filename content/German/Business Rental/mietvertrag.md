+++
title = "Mietvertrag erstellen"
weight = 1060
+++

Es bestehen drei Möglichkeiten, einen Mietvertrag zu erzeugen. Sie können einen neuen Mietvertrag von Hand erstellen. 

![Mietvertrag ne](/images/MV.jpg)

Oder Sie nutzen die Funktion aus dem Mietangebot und wandeln ein Mietangebot in einen Mietvertrag um. 

![Angebot in Mietvertrag umwandeln](/images/kopieren.jpg)

Wenn schon ein ähnlicher Beleg vorhanden ist, kopieren Sie einen vorhandenen mietbezogenen Beleg.  sehr ähnliche Möglichkeit kennen Sie schon aus dem Standard.

![Mietbeleg kopieren](/images/copy.jpg)

Um den gesamten Prozess abzubilden, erstellen wir in unserem Beispiel einen Mietvertrag ohne die Kopieren Funktion oder die Umwandlung über ein Mietangebot.

Nachdem Sie einen neuen Mietvertrag erstellt haben, füllen Sie die Debitorennummer aus, legen den Mietbeginn und das -ende fest. Zudem benötigen Sie einen Miettarif und Abrechnungszeitraum. Für unser Beispiel nehmen wir eine monatliche Pauschale.

![Mietvertragkopf](/images/mvthead.jpg)

Wie erwartet finden wir einen Mietartikel in den Zeilen zu einem Preis von 12,50. Denken Sie dran, dass Sie hier auch noch die Möglichkeit haben, abweichende Preise oder Rabatte zu erfassen. 

![Mietvertragzeilen](/images/mvtlines.jpg)

Unter den Zeilen sehen Sie eine Summierung der Gesamtpreise netto, brutto und gewährte Rabatte. 

Im Vergleich zu Ihren Standard Verkaufsartikeln ist für die Vermietung keine Auswahl eines Lagerortes vorgesehen. Das Feld mit dem Lagerortcode muss also leer bleiben. Wenn Sie mit den Eingaben zufrieden sind, können Sie den Mietvertrag freigeben. Nun müssen Sie den Mietartikel ausliefern. Hierzu finden Sie in der oberen Leiste die Schaltfläche Buchen. Nach Auswahl erhalten Sie eine Nachfrage, ob Sie Liefern, Fakturieren oder Liefern und Fakturieren möchten. Wählen Sie bitte Liefern aus.

![Mietvertrag liefern](/images/ship.jpg)

Nach der Auswahl mit OK ist der Mietartikel ausgeliefert. 

Bevor wir zu den Posten kommen, schauen wir uns die Mietlieferung genauer an, über Navigieren können Sie sich den Beleg ansehen:

![Mietlieferung](/images/MLS.jpg)

In der Mietlieferung können Sie nachvollziehen, an wenn die Sendung gegangen ist oder den Beleg ausdrucken. Alternativ können Sie übrigens über die Infobox im rechten Bereich zu den Belegen navigieren, die dem benannten Debitor zugeordnet sind. Beachten Sie jedoch, dass die Filterung hier nicht auf den Mietvertrag, sondern auf den Debitor erfolgt und Sie somit ggf. Informationen zu weiteren Mietveträgen finden.

![Mietlieferung Infobox](/images/mls1.jpg)

Was bedeutet die Lieferung nun für die Posten? Werfen wir einen Blick auf den Hauptmietartikel: SCREENSHOT BESTAND

Um den Mietvertrag abrechnen zu können, nutzen Sie wieder die Schaltfläche Buchen und wählen den Punkt Fakturieren aus. Bestätigen Sie bitte mit OK um eine Mietrechnung zu erzeugen. Je nach Konfiguration in der Mieteinrichtung wird nun eine ungebuchte oder gebuchte Mietrechnung erzeugt, die Sie sich auf Nachfrage ansehen und weiter verarbeiten können (Drucken, Mailversand).

Um den Prozess abzukürzen können Sie in der Auswahl auch Liefern und Fakturieren auswählen und erstellen somit gleichzeitig die Lieferung und Rechnung. 

![Mietrechnung Navigieren](/images/MRE.jpg)

Für einen direkten Zugriff können Sie die dem Mietvertrag zugehörigen Mietrechnungen über Navigieren einsehen. Alternativ nutzen Sie die Infobox im rechten Bereich mit der bekannten alternativen Zuordnung. 

Mit der Lieferung und der Berechnung ist der Mietvertrag nun grundsätzlich abgeschlossen. Es muss jetzt abschließend sichergestellt werden, dass Sie den Mietartikel wieder abholen. Hierzu erstellen Sie bitte eine Rücknahme über die entsprechende Schaltfläche. 

![Mietrücknahme Navigieren](/images/rücknahme.jpg)

Wählen Sie bei der Nachfrage bitte Ja, um die Seite der Rücknahme öffnen zu können und weitere Informationen einzutragen. Das Buchungsdatum in der Rücknahme wird automatisch befüllt, kann aber von Ihnen angepasst werden. Um eine Rücknahme richtig zu verbuchen, müssen Sie in den Zeilen einen Wert bei der Spalte Rückgabe Menge eintragen. In unserem Beispiel ist das EIN Fahrrad. Da Mietartikel zwar mehrfach vorhanden sein können, diese aber immer eine eindeutige Nummer erhalten, können Sie hier keine andere Zahl als 1 eintragen.

In den Mietzeilen können Sie einsehen, dass sich nach der Buchung der Rücknahme die entsprechenden Werte verändert haben. 

Somit ist die Abwicklung mit diesem einfachen Beispiel abgeschlossen und wir können uns nun mit einem komplexerem Mietvertrag auseinander setzen.

## Mietvertrag mit Versandkosten und täglicher Berechnung ##

In diesem Beispiel schauen wir uns an, wir man mit Business Rental eine tägliche Abrechnung sowie die Kosten für eine Anlieferung und Abholung abbilden kann. 
Für die tägliche Abrechnung wählen wir im Mietkopf den Mietpreis-Code TAG aus bzw. den in Ihrem System hinterlegten Mietpreis, der täglich konfiguriert ist.

![Mietpreistyp](/images/mietpreis_tgl.jpg)

Abhänging vom hinterlegten Basiskalender erfolgt eine Berechnung am Wochenende oder eben nicht. Für unser Beispiel mit dem Fahrrad ist eine Berechnung am Wochenende gewünscht, weswegen der Miettarif TAG korrekt ist.

In den Zeilen finden wir insgesamt drei Zeilen: einen Mietartikel (Hier ein Treckingfahhrad) sowie zwei Zeilen für die Anlieferung und die Abholung. 

![Mietvertrag mit Fracht](/images/MVT_compl.jpg)

Die Zielsetzung lautet wie folgt: wir möchten mit der Anlieferung die Kosten berechnen, sowie tageweise die Vermietung des Fahrrads. Die einzelnen Tage sollen ebenfalls einzeln berechnet werden (bisher haben wir eine pauschale Abrechnung vorgenommen), am Ende sollen die Kosten für die Abholung berechnet werden.

Um diese Berechnung nun vorzunehmen, wird wie folgt vorgegangen:
- das Rad sowie die Anlieferung werden mit Menge zu liefern 1 befüllt (Vorbelegung erfolgt in der Regel automatisch).
- die Menge zu liefern in der Zeile der Abholung wird auf 0 gesetzt, somit fehlt die Berechnungsgrundlage (da noch keine Lieferung erfolgte).

![Mietvertrag buchen](/images/menge0.jpg)

- Der Mietvertrag ist nun also bereit für die Fakturierung und kann gebucht werden. Hiermit erzeugen Sie eine gebuchte Mietrechnung. Sie könnnen sich zur Kontrolle die Beträge über die Buchungsvorschau ansehen und erzeugen dann keine Buchung.

![Mietvertrag buchen](/images/buchen.jpg)

- nach einer Woche möchten wir die zweite Mietrechnung erstellen, hierzu verwenden Sie bitte wieder die Funktion buchen. Achten Sie jedoch darauf, dass die Menge zu liefern in der Abholung auf 0 steht.
- Am letzten Tag der Vermietung wird bei der Ressource Abholung die Menge zu liefern auf 1 gesetzt.
- mit der Berechnung der Abholung ist der Mietvertrag abgeschlossen.
- Abhänging vom verwendeteten Abrechnungszeitraum kann die Anzahl an erstellten Mietrechnungen variieren. In unserem Beispiel haben wir uns für eine wochenweise Abrechnung entschieden und erhalten somit zwei Mietrechnungen (14 Tage vermietet) sowie eine Mietrechnung für die Kosten der Abholung.
- Sollten andere Abrechnungszeiträume notwendig sein, können diese flexibel in den Abrechnungszeiträumen erstellt werden.

Damit alle zu diesem Mietvetrag gehörenden Belege schnell zu finden sind, können Sie unter dem Reiter Zugehörig > Dokumente alle bisher erstellten Mietlieferungen und Mietrechnungen einsehen. Alternativ besteht die Möglichkeit, mit Hilfe der Infobox rechts (grüner Rahmen im Screenshot) die entsprechenden Belege aufzurufen, jedoch sind hier die dem *Debitoren* zugeordnenten Belege zu finden. Sofern es für den Kunden also einen zweiten Mietvertrag gibt oder gab, können die relevanten Informationen hier abgerufen werden.

![Mietbelege einsehen](/images/mvlief.jpg)

## Mietvertrag mit automatischer Verlängerung

In den meisten Fällen werden Sie den Mietvertrag so lange automatisch verlängern, bis sich der Kunde bei Ihnen meldet und den Mietartikel freimeldet. Um diesen Vorgang bei Ihnen 