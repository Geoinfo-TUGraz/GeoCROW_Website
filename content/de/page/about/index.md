---
title: Zusammenfassung GeoCROW
comments: false
---

{{<justify>}}
Virtuelle 3D Darstellungen - wie z.B. Google Earth, NASA World Wind – können im professionellen Kontext dafür eingesetzt
werden, um sich in unbekannten Gebieten mit den örtlichen Gegebenheiten auseinanderzusetzen. Diese „vorab-Aufklärung“
in einem virtuellen Raum beschränkt sich jedoch nur auf Repräsentation der Realwelt zum Zeitpunkt der Datenakquise; z.B.
zum Zeitpunkt der Aufnahme des Satellitenbildes. Damit ist es unmöglich aktuelle Entwicklungen und Besonderheiten
abzubilden, die sich in jüngster Zeit ergeben haben. Somit sind Phänomene und Besonderheiten, wie zB.: Brücke ist nicht
mehr intakt, Fluss führt gerade Hochwässer, Sicherheitsrisiken (z.B. social unrest), nicht berücksichtigt. Doch gerade in der
sicherheitsdienstlichen Aufklärung sind solche aktuellen Informationen von besonderem Interesse.
Das Projekt GeoCROW nutzt daher Geosemantik und intelligente Data Crawling Methoden, um aktuelle Daten und
Informationen zu einem bestimmten Gebiet im Internet zu finden, zu kategorisieren, zu validieren und entsprechend
lagegenau zu verortet und zu visualisieren. Potenzielle Quellen hierfür sind Social Media Dienste, Linked (Open) Data
Portale, Nachrichtendienste, etc. So können aktuelle Informationen in das virtuelle Lagebild integriert werden. Da Social
Media und andere Kanäle im Internet wesentlich dazu beitragen können die aktuelle Lage zu beurteilen, jedoch ein einzelner
Mensch die Fülle an Daten nicht sichten, kategorisieren und analysieren kann, benötigt man intelligente Algorithmen. Da
jedoch die nur eine kleine Menge an Webquellen mit expliziten Ortsangaben versehen sind (im Falle von Twitter sind dies ca.
1% [Lansley & Longley 2016]), ist es notwendig das Geotagging auch über die Analyse des Textes und des Kontextes
durchzuführen, was in den Testgebieten (Afrika, Naher Osten) eine herausfordernde Problemstellung ist. Die technischen
Herausforderungen, die im Projekt gelöst werden sollen, drehen sich um drei Problemkreise:
{{</justify>}}

1. (geo-)semantische Analyse und Geoparsing & Georeferenzierung von unstrukturierten Web-Daten aus unterschiedlichen
   kulturellen und sprachlichen Regionen der Welt
2. Integration (geo-)semantisch annotierter Daten in eine VR Umgebung
3. Interaktion mit (geo-)semantisch annotierten Daten in einer VR Umgebung

{{<justify>}}
Im Vorfeld der Einbettung der akquirierten und gespeicherten Daten müssen diese in eine harmonisierte Form für die
Weiterverarbeitung gebracht werden. Des trifft ebenfalls für Daten und Informationen in verschiedenen Sprachen (Englisch,
Französisch und Arabisch) zu. Dies geschieht durch (i) Extraktion von relevanten Events und Geolokationen in den
genannten Sprachen und in Folge durch das Mapping dieser identifizierten Konzepte und Named Entities auf einen
mehrsprachigen Knowledge Graphen - in diesem werden die relevanten, gefundenen Daten auf eine Default Sprache (zB
Englisch, aber zukünftig zB auch Deutsch) gemappt und damit harmonisiert. Weiters wird in diesem Schritt Kontext mittels
semantischer Verarbeitung und durch Data Linking hergestellt. Dies bedeutet, dass zB verschiedene Event oder Incident
Levels (die vorher entsprechend den Anforderungen spezifiziert wurden - und zB in verschiedenen Regionen verschiedene
Bedeutung haben- Beispiel gebrochener Brückenkopf in der Steiermark versus in Syrien) - mit geografischer Information in
Bezug gesetzt werden, um damit entsprechende Bedeutung in der Endanwendung erfahren. Methoden wie Disambiguierung
(Klärung von begrifflichen Mehrdeutigkeiten) und Klassifizierung (Machine Learning basiertes Klassifizieren von Events)
kommen hier zum Einsatz. Die aufbereiteten und harmonisierten Informationen (Event Detection, Geolocations) werden in
Folge für die nächsten Verarbeitungsschritte übergeben.Die Integration von geosemantisch annotierten, gecrawlten Daten in VR birgt mehrere Herausforderungen, die bei der
Erreichung der Ziele dieses Projekts angegangen werden müssen. Diese Herausforderungen haben damit zu tun, wie die
Informationen präsentiert und mit ihnen aus Sicht des Users interagiert wird. Ein weiterer Aspekt ist, wie die neuen
Informationen in der VR-Welt dargestellt werden sollen. Visuelle Analysetechniken in Desktop-Computern haben einen
speziellen Bildschirm, auf dem die volle Aufmerksamkeit des Analytikers platziert wird. Bei der Verwendung von lokalisierter
Immersivtechnik muss die Datenvisualisierung jedoch mit der Umgebung koexistieren. Das heißt, die Datenvisualisierung
kann nicht das volle Gesichtsfeld einnehmen und muss so angepasst werden, dass sie nicht mit den natürlichen visuellen
Merkmalen der Umgebung konkurriert. Eine weitere Herausforderung ist die Darstellung von Beziehungen zwischen
Entitäten, die nicht ko-lokalisiert sind. Bei der Erweiterung von gecrawlten Informationen wie Nachrichten und Social Media
mit Semantik entsteht ein reichhaltiger, verbundenes Set von Entitäten. Aber diese geo-getaggten Entitäten können räumlich
verteilt sein. Wir werden Methoden untersuchen, um Beziehungen zwischen nicht isolierten Einheiten darzustellen. Zu guter
Letzt muss die Interaktion mit der lokalisierten Visualisierung entwickelt werden, um die Möglichkeit der freien Bewegung und
der Nutzung von visuellem und kinästhetischem Feedback zu nutzen. Hierbei ist wichtig, dass der physische
Bewegungsraum immer kleiner sein wird als die virtuelle Umgebung. Es gilt daher vestibuläre und propriozeptive Sinne zu
nutzen und gleichzeitig Bewegungskrankheiten zu vermeiden.
{{</justify>}}

**Projektlaufzeit:**

01 Februar 2023 - 31 Januar 2025

---

**Partner:**
![Partners](geocrow_partners.png)

- Technische Universität Graz
- Semantic Web Company GmbH
- Technische Universität Wien
- Bundesministerium für Landesverteidigung
- Donau Universität Krems
- Research Institute AG & Co KG

---

**Förderungen:**

![FFG](ffg_logo.svg)

Dieses Projekt wird gefördert durch Österreichische Forschungsförderungsgesellschaft mbH
(FFG) durch das Programm “FORTE, FORTE, FORTE - Kooperative F&EProjekte
2021/2022” (Projektnummer FO999895161)
