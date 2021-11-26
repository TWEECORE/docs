+++
title = "Erstellung von Artikeln, Hauptmietartikeln und Mietartikeln"
weight = 1020
+++

Um einen Artikel vermieten zu können, benötigen Sie einen Hauptmietartikel sowie einen Mietartikel, der auf den Hauptmietartikel referenziert. Rufen Sie für die Erstellung eines Mietartikels die Liste der Artikel auf, die Sie auch schon aus dem Standard kennen.

Legen Sie hier einen neuen Artikel an, den Sie vermieten möchten. Je nach Vorlage sind schon bestimmte Werte gefüllt, wie zum Beispiel die Produktbuchungsgruppe. Sollte das nicht der Fall sein, treffen Sie hier bitte eine Auswahl. Pflichtfelder erkennen Sie an einem roten Stern, sollten Sie keine Auswahl treffen, können Sie nicht fortfahren und erhalten eine entsprechende Meldung. 

Der Artikel muss über einen Bestand verfügen, diesen können Sie regulär einkaufen oder über das Artikel Buch. Blatt in Ihr Lager überführen. Über die Funktion Artikel in Mietartikel konvertieren erzeugen Sie einen sogenannten Hauptmietartikel und gleichzeitig die gewünschte Auswahl an Mietartikeln. Sie können mindestens einen oder maximal den gesamtten Lagerbestand zu einem Mietartikel konvertieren.

Nehmen wir nun beispielhaft an, dass Sie ein Fahrradhändler sind. Das kann bedeuten, dass Sie einen bestimmten Fahrradtyp sowohl vermieten als auch verkaufen wollen. Für den Verkauf ändert sich für Sie nichts, Sie können hier den gewöhnlichen Standardverkaufsprozess nutzen und benötigen auch somit keinen Hauptmietartikel. Für unser Beispiel wollen Sie einen bestimmten Fahrradtyp nicht nur verkaufen, sondern auch vermieten. Sie erstellen also einen neuen Artikel und buchen einen entsprechenden Lagerbestand. 

Nun nutzen Sie die Konvertierungsfunktion:

![Funktion konvertieren](/images/convert.jpg)

Es erfolgt eine Nachfrage, ob Sie sich sicher sind, dass Sie die Konvertierung vornehmen möchten. Bestätigen Sie diese mit Ja. Es erfolgt eine Nachfrage, wieviele der vorhandenen Artikel Sie in einen Mietartikel konvertieren möchten, wobei der komplette Lagerbestand vorgeschlagen wird. In unserem Beispiel möchten wir von den 50 verfügbaren Trekkingrädern 15 als Mietartikel anlegen. Nachdem die Konvertierung erfolgt ist, werfen wir einen Blick auf die Artikelposten:

![Artikelposten](/images/posten.jpg)

Wie Sie sehen können, wurden 50 Artikel regulär eingekauft. Anschließend gab es eine Abgangsbuchung über die 15 Artikel, die jetzt zu einem Mietartikel konvertiert worden sind. In der Ansicht der Mietartikel finden wir diese 15 Fahrräder wieder:

![Mietartikel](/images/mietartikel.jpg)

Für den Fall, dass Sie einen Mietartikel wieder in den regulären Bestand (Handelsware) übernehmen möchten, können Sie einen Mietartikel wieder jederzeit in einen Artikel umwandeln, vorausgesetzt der Mietartikel befindet sich derzeit nicht in der Vermietung.

![Mietartikel zum Artikel konvertieren](/images/mart_convert.jpg)

Die Logik lässt sich also wie folgt zusammenfassen: jeder Artikel, den Sie vermieten wollen, konvertieren Sie in einen Hauptmietartikel. Sie können beliebig viele Mietartikel in Ihrem System verwalten.

![Logik der Mietartikel](/images/articleconvert.jpg)

Hauptmietartikel sind vom Typ immer **ohne Bestand** und Basiseinheit Stück. Mit den Buchungsdetails legen Sie fest, welche Sachkonten bei der Vermietung bebucht und angesprochen werden sollen. Sollte noch keine Einrichtung vorgenommmen worden sein, halten Sie hier bitte Rücksprache mit Ihrer Finanzbuchhaltung. 

Der Hauptmietartikel erfüllt die Funktion eines übergeordneten Artikels, den Sie vermieten möchten. Anders gesagt: Sie haben immer mindestens einen **Haupt**mietartikel, dieser kann aber so oft Sie wollen als Mietartikel vorhanden sein. Der Mietartikel ist auch das Produkt, welches Sie an den Kunden vermieten. Einen Hauptmietartikel können Sie nicht vermieten.

Wenn Sie möchten, können Sie auf der Hauptmietartikelkarte unter Preise & Rabatte Werte eintragen. 

![Mietpreise](/images/mietpreis.jpg)

Diese können für bestimmte Debitoren, Preisgruppen oder Kampagnen in einer Preisliste hinterlegt werden. Beispielhaft sehen Sie eine Preisliste für die beiden Hauptmietartikel Trekking Fahrrad und Mountain Bike, diese Preise gelten für alle Debitoren. Um die Preisliste zu aktivieren, müssen Sie den Status von Entwurf auf Aktiv umstellen.

![Preisliste](/images/preisliste.jpg)

Grundsätzlich ist die Erstellung jetzt abgeschlossen und Sie können Mietartikel anbieten und vermieten. Jetzt muss noch sichergestellt werden, dass Sie Angaben zu Ihren Abrechnungszeiträumen und ggf. verschiedenen Mietkalendern machen.