+++
title = "Project Invoice unterstütze Einrichtung"
weight = 2020
+++

Die einfachste Methode zur Einrichtung von Project Invoice ist die "Unterstütze Einrichtung".

<br/>

### Schritt 1:

![Assisted Setup Project Invoice](/piimages/assistedsetup.png)

*Rechnungs Typ* - definieren Sie den Typ der Verkaufszeile mit der die Abrechnung durchgeführt werden soll.

*Nr.* - wählen Sie passend zum Typ die Nummer für den Artikel, die Ressource oder des Sachkontos zur Abrechnung.

*Nr. Serie Project Invoice* - die gewählte Nummernserie wird verwendet um die Importe aus Ihren System zu benamen.

*Zeiten zusammenfassen* - durch auswahl der Zusammenfassungen werden Zeiten zusammen gefasst in eine Verkaufszeile geschrieben. Dies kann pro Projekt überschrieben werden.

*Summarize Description* - bei Verwendung von zusammengefassten Zeiten wird diese Beschreibung in der Verkaufszeile verwendet. Dies kann pro Projekt überschrieben werden. 

 
<br/>


### Schritt 2:

![Assisted Setup Project Invoice](/piimages/assistedsetup2.png)

*Code* - unique name for the oAuth Application.

*Description* - description for this oAuth Application.

*Project Mgt. System* - defines which Project Mgt. System will be used.

*Endpoint* - url to the Project Mgt. System.

*Timetracking Endpoint* - this url will only be needed if you selected Jira (Tempo) as Project Mgt. System, please enter the Tempo Timesheet url.

*User Name* - user with enough rights in the project mgt. system, to be able to get receive the data of all projects.

*Password* - password for the user.

*Permanent Token* - api authorization key also known as permanent token which you can create in your Project Mgt. System.

*Timetracking Permanent Token* - this token will only be needed if you selected Jira (Tempo) as Project Mgt. System, please enter the generated token by Tempo Timesheet.