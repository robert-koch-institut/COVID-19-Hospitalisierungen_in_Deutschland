Datensatzdokumentation  
# COVID-19-Hospitalisierungen in Deutschland


[Robert Koch-Institut](https://ror.org/01k5qnb77) | RKI  
Nordufer 20  
13353 Berlin  

Beitragende:
FG 32 | Surveillance | ÖGD-Kontaktstelle  
[Michaela Diercke](https://orcid.org/0000-0002-4678-1813) (Leitung)  

FG 34 | HIV/AIDS und andere sexuell oder durch Blut übertragbare Infektionen  
[Matthias an der Heiden](https://orcid.org/0000-0001-5863-4549) (Forschung)

FG 31 | Infektionsepidemiologische Fach-IT und Anwendungsentwicklung  
[Alexander Ullrich](https://orcid.org/0000-0002-4894-6124) (Datenmanagement)  

MF 4 | Forschungsdatenmanagement  
[Hannes Wuensche](https://orcid.org/0000-0002-8837-0326) (Datenkuration)  


---
**Zitieren**  
Robert Koch-Institut (2023): COVID-19-Hospitalisierungen in Deutschland, Berlin: Zenodo. DOI:[10.5281/zenodo.7882302](https://doi.org/10.5281/zenodo.7882302).  


## Informationen zum Datensatz und Entstehungskontext 

Im Datensatz "COVID-19-Hospitalisierungen in Deutschland" werden die aktuellen Zahlen der nach den Vorgaben des [Infektionsschutzgesetzes - IfSG -](https://www.gesetze-im-internet.de/ifsg/index.html) erfassten hospitalisierten COVID-19-Fälle bereitgestellt.  
Um den Trend der Anzahl von Hospitalisierungen und der 7-Tage-Hospitalisierungsinzidenz besser bewerten zu können, wird die berichtete Hospitalisierungsinzidenz um eine Schätzung der zu erwartenden Anzahl an verzögert berichteten Hospitalisierungen ergänzt. Neben den Daten der gemeldeten COVID-19-Hospitalisierungen auf Bundes- und Länderebene wird daher ein Nowcasting der Anzahl hospitalisierter Fälle und der 7-Tage-Hospitalisierungsinzidenz auf Bundesebene durchgeführt. Ziel ist die Schätzung der Anzahl von hospitalisierten COVID-19-Fällen mit Meldedatum innerhalb der sieben vorhergehenden Tage - inklusive der noch nicht an das RKI berichteten Hospitalisierungen. Aufbauend auf dem Nowcasting wird eine Schätzung der adjustierten 7-Tage-Hospitalisierungsinzidenz durchgeführt.  

### Administrative und organisatorische Angaben  

Die zugrundeliegenden Hospitalisierungsdaten werden an das Robert Koch-Institut (RKI) über das Meldesystem gemäß IfSG übermittelt. Zuständig für den Betrieb des Meldesystems ist das [Fachgebiet 32 | Surveillance | ÖGD-Kontaktstelle](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG32/FG32_node.html) des RKI. Die Verarbeitung und Aufbereitung der im Meldesystem vorliegenden Rohdaten erfolgt durch das [Fachgebiet 31 | Infektionsepidemiologische Fach-IT und Anwendungsentwicklung](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG31/FG31_node.html). Die Berechnung der adjustierten Anzahl hospitalisierter Fälle und der adjustierten 7-Tage-Hospitalisierungsinzidenz erfolgt durch [Matthias an der Heiden](https://orcid.org/0000-0001-5863-4549), wissenschaftlicher Mitarbeiter des [Fachgebiet 34 | HIV/AIDS und andere sexuell oder durch Blut übertragbare Infektionen](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG34/FG34_node.html). Inhaltliche Fragen bezüglich der COVID-19-Hospitalisierungen in Deutschland können an das RKI unter [info@rki.de](mailto:info@rki.de) gestellt werden.  
Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgt durch das Fachgebiet [MF 4 | Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html). Fragen zum Datenmanagement können an das Open Data Team des Fachgebiets MF4 gerichtet werden ([OpenData@rki.de](mailto:OpenData@rki.de)).  

### Erhebung und Aufbereitung der Daten  

Gemäß Infektionsschutzgesetz müssen der Verdacht, die Erkrankung, die Aufnahme und der Tod in Bezug auf COVID-19 sowie der Nachweis von SARS-CoV-2 an das Gesundheitsamt gemeldet werden.  
Die Meldung muss unverzüglich erfolgen und dem Gesundheitsamt spätestens innerhalb von 24 Stunden vorliegen. Dabei müssen auch Name, Adresse und Kontaktdaten der betroffenen Person gemeldet werden, damit das Gesundheitsamt die Person kontaktieren kann und die notwendigen Maßnahmen (z.B. Isolierung der betroffenen Person, Ermittlung von Kontaktpersonen) einleiten kann.  
Der Meldeweg vom Arzt oder anderen Meldepflichtigen zum Gesundheitsamt läuft derzeit noch routinemäßig per Fax, selten per Telefon oder E-Mail. Seit Mitte Juni 2020 haben Labore die Möglichkeit, Erregernachweise von SARS-CoV-2 elektronisch an das zuständige Gesundheitsamt zu melden (erste Ausbaustufe des [Deutschen Elektronischen Melde- und Informationssystems für den Infektionsschutz - DEMIS](https://www.rki.de/DE/Content/Infekt/IfSG/DEMIS/DEMIS_node.html)). Für Labore ist die Meldung von SARS-CoV-2-Erregernachweisen über DEMIS seit dem 01.01.2021 verpflichtend.  
COVID-19-Fälle, die die Falldefintionen des RKI erfüllen, müssen vom zuständigen Gesundheitsamt, spätestens am nächsten Arbeitstag, elektronisch an die zuständige Landesbehörde und von dort, spätestens am nächsten Arbeitstag, an das RKI übermittelt werden, allerdings ohne Name, Wohnort und Kontaktdaten der Betroffenen. In der aktuellen Lage übermitteln die meisten Gesundheitsämter früher und häufiger als gesetzlich vorgesehen, meist täglich und auch am Wochenende. Allerdings kann es bei der Übermittlung der Fälle auch zu einem Melde- und Übermittlungsverzug von einigen Tagen kommen.
Weitere Informationen und Antworten auf häufig gestellte Fragen zum Meldeweg und Meldeinhalten finden sich unter folgendem Link: https://www.rki.de/SharedDocs/FAQ/NCOV2019/gesamt.html

#### Zeitlicher Bezug der hospitalisierten COVID-19-Fälle

Der Umfang der an das RKI übermittelten Daten ist in §11 IfSG festgelegt. Dies beinhaltet neben demografischen und weiteren wichtigen epidemiologischen Angaben auch Angaben zum Hospitalisierungsstatus.  
Im Verlauf einer SARS-CoV-Infektion wird zwischen verschiedenen Kennzeitpunkten unterschieden:  

* Erkrankungsdatum des Falls
* Hospitalisierungsdatum des Falls (bei mehreren Krankenhausaufenthalten können mehrere Hospitalisierungsdaten vorliegen)
* Datum der Meldung, z.B. durch Labor, Krankenhaus (pro COVID-19-Fall können mehrere Meldungen vorliegen)
* Meldedatum, das Datum, an dem das lokale Gesundheitsamt Kenntnis über den Fall erlangt und ihn elektronisch erfasst hat.
* Berichtsdatum, das Datum, an dem die 7-Tage-Inzidenz jeweils tagesaktuell vom RKI berichtet wird  

Die hospitalisierten COVID-19-Fälle werden zeitlich nach Meldedatum ausgewiesen. Je nach Verlauf und Meldehistorie des Falls kann es sein, dass das Meldedatum vor, zeitgleich oder nach dem Hospitalisierungsdatum liegt.
Hintergrund dieser Entscheidung ist, dass Angaben zum Hospitalisierungsdatum nicht für jeden hospitalisierten COVID-19-Fall vorliegen, sondern teilweise von den Gesundheitsämtern nachermittelt werden müssen. Gleichzeitig zeigt sich für die vorhandenen Hospitalisierungsdaten, dass das Hospitalisierungsdatum und Meldedatum häufig eng beieinander liegen. Um eine vollständigere Darstellung der COVID-19-Hospitalisierungen zu erreichen wird daher auf das Meldedatum des positiven Infektionsnachweises zurückgegriffen.  
Bei der Bewertung der Daten sollte berücksichtigt werden, dass die betroffene Person bei Meldung noch gar nicht oder nur leicht erkrankt sein kann und sich eine schwere Erkrankung erst im Verlauf entwickelt. Wenn die Hospitalisierung mehr als 7 Tage nach der Meldung erfolgt, dann werden diese Fälle zum Berichtsdatum nicht in der 7-Tage-Hospitalisierungsinzidenz erfasst, sondern werden nur bei rückblickender Betrachtung der Daten sichtbar. Ebenso können Melde- und Übermittlungsverzug zu einer eingeschränkten Vollständigkeit der Daten führen. Die Daten sind demnach zum Berichtsdatum noch unvollständig. Nach einigen Tagen liegen die Informationen vollständiger vor, sodass sich die 7-Tage-Hospitalisierungsinzidenz für den Berichtstag im Nachhinein noch erhöht.  

#### Geografischer Bezug der hospitalisierten COVID-19-Fälle

Die Daten werden in der Regel von dem Gesundheitsamt an das RKI übermittelt, das für den Wohnort der betroffenen Person zuständig ist. In Einzelfällen können die Gesundheitsämter von dieser Regelung abweichen. Wenn die betroffene Person z.B. in Niedersachsen wohnhaft ist, aber in Hamburg hospitalisiert wird, dann erfolgt die Zuordnung zum Bundesland Niedersachsen. Das bedeutet, dass die Daten keinen direkten Rückschluss auf die Krankenhausbelegung der jeweiligen Bundesländer zulassen. 

#### Weitere Veröffentlichung der Daten 

Eine grafisch aufbereitete Darstellung der Daten zu COVID-19-Hospitalisierungen werden gemäß §28a IfSG auf der RKI-Webseite werktäglich aktualisiert unter folgendem Link veröffentlicht: https://rki.de/covid-19-trends 

## Aufbau und Inhalt des Datensatzes

Der Datensatz enthält epidemiologische Daten zur Anzahl und 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle nach Bundesland und Altersgruppen in Deutschland. Im Datensatz enthalten sind:  

* Hospitalisierte COVID-19-Fälle auf Bundes- und Länderebene  
* Berechnung der adjustierten COVID-19-Hospitalisierungen auf Bundesebene  
* Archiv mit der Sammlung aller bisherigen Hospitalisierungsdaten  
* Lizenz-Datei mit der Nutzungslizenz des Datensatzes in Deutsch und Englisch  
* Datensatzdokumentation in deutscher Sprache  
* Metadaten-Datei zum Import in Zenodo  

### Formatierung der Daten

Die Daten sind im Datensatz als kommaseparierte .csv-Datei enthalten. Der verwendete Zeichensatz der .csv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",". Datumsangaben sind im ISO8601 Standard formatiert.  

* Zeichensatz: UTF-8  
* Datumsformat: ISO8601  
* .csv-Trennzeichen: Komma ","  
 
### Metadaten

Die bereitgestellten Daten sind mit Metadaten beschrieben und wissenschaftlich zitierbar, u.a. durch die Vergabe einer DOI durch Zenodo.org. Die für den Import in Zenodo bereitgestellten Metadaten sind in folgender Datei hinterlegt:  

> [.zenodo.json](/.zenodo.json)  

Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.  

## Hospitalisierte COVID-19-Fälle nach Bundesland und Altersgruppe  

Die Hospitalisierungsdaten bilden einen tagesaktuellen Stand (00:00 Uhr) aller über das Meldesystem gemäß Infektionsschutzgesetz an das RKI übermittelten COVID-19-Fälle, bei denen eine Hospitalisierung angegeben ist, ab. Das bedeutet, dass alle, bis 00:00 Uhr des Tages JJJJ-MM-TT, von den Gesundheitsämtern über die zuständigen Landesbehörden an das RKI übermittelten Hospitalisierungen mit Bezug zu COVID-19 im Datenstand enthalten sind. Die Daten werden täglich vollständig neu erzeugt, dieser Datenstand ersetzt den Datenstand des Vortages.  

>[Aktuell_Deutschland_COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/master/Aktuell_Deutschland_COVID-19-Hospitalisierungen.csv)
>[JJJJ-MM-TT_Deutschland_COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/tree/master/Archiv)

Im Dateinamen repräsentiert die Sequenz “JJJJ-MM-TT” das Erstellungsdatum der Datei und gleichzeitig das Datum des enthaltenen Datenstands. “JJJJ” steht dabei für das Jahr, “MM” für den Monat und “TT” für den Tag der Erstellung bzw. des enthaltenen Datenstands.


### Variablen 

Die Hospitalisierungsdaten differenzieren verschiedenen Merkmale. Grundlegend nach folgende Merkmale differenziert (in den Klammern finden sich die Variablen dieser Merkmale):  

* Berichtsdatum der 7-Tage-Hospitalisierungsinzidenz (Datum)  
* Bundesland (Bundesland, Bundesland_Id)  
* Altersgruppe (Altersgruppe)  
* 7-Tage-Fallzahl der hospitalisierten COVID-19-Fälle (7T_Hospitalisierung_Faelle)  
* 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (7T_Hospitalisierung_Inzidenz)  

Ein Einträge nehmen eine eineindeutige Ausprägung hinsichtlich der Anzahl der Hospitalisierungen der letzten 7 Tage, einer Altersgruppe eines Bundeslands an. Die 7-Tage-Hospitalisierungsinzidenz berechnet sich aus der Anzahl der an das RKI übermittelten COVID-19-Fälle mit Meldedatum innerhalb der sieben vorgehenden Tage und der Bevölkerungszahl der entsprechenden Altersgruppe des Bundeslandes (bzw. des gesamten Bundesgebiets). Zur einheitlichen Darstellung wird die Inzidenz auf 100.000 Einwohner:innen normiert.  

### Variablenausprägungen
Die Hospitalisierungsdaten enthalten die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen:  

| Variable | Typ | Ausprägung | Beschreibung |
| -------- | --- | ---------- | ------------ |
| Datum |Datum |```JJJJ-MM-TT``` | Berichtsdatum der 7-Tage-Hospitalisierungsinzidenz. |
| Bundesland | Text | ```Bundesgebiet``` <br/> ```Schleswig-Holstein``` <br/> ... <br/> ```Thüringen``` | Name des Bundeslandes sowie ein Wert für das gesamte Bundesgebiet | 
| Bundesland_Id| Text | ```00``` : Bundesgebiet <br/> ```01```&nbsp;bis&nbsp;```16```&nbsp;:&nbsp;Bundesland ID  | Identifikationsnummer des Bundeslandes basierend auf dem Amtlichen Gemeindeschlüssel (AGS) sowie ein Wert für das gesamte Bundesgebiet|
|Altersgruppe | Text | ```00+```(alle Altersgruppen), ```00-04```, ```05-14```, ```15-34```, ```35-59```, ```60-79```, ```80+``` | Altersgruppe der  hospitalisierten COVID-19-Fälle | 
|7T_Hospitalisierung_Faelle | Natürliche Zahl | ```≥0```| Summe der hospitalisierten COVID-19-Fälle mit Meldedatum innerhalb der letzten 7 Tage | 
|7T_Hospitalisierung_Inzidenz| Rationale Zahl | ```≥0``` | 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (nach Meldedatum des Falles) bezogen auf 100.000 Bevölkerung |


## Adjustierte COVID-19-Hospitalisierungen auf Länderebene  

Zwischen dem Beginn des Krankenhausaufenthalts eines COVID-19-Falles und dem Zeitpunkt, an dem diese Information am RKI eingeht, entsteht ein zeitlicher Verzug. Um den Trend der Anzahl von Hospitalisierungen und der 7-Tage-Hospitalisierungsinzidenz besser bewerten zu können, ergänzen wir die berichtete Hospitalisierungsinzidenz um eine Schätzung der zu erwartenden Anzahl an verzögert berichteten Hospitalisierungen. Neben den Daten der gemeldeten COVID-19-Hospitalisierungen auf Bundes- und Länderebene wird daher ein Nowcasting der Anzahl hospitalisierter Fälle und der 7-Tage-Hospitalisierungsinzidenz auf Bundes- und Länderebene durchgeführt. Ziel ist die Schätzung der Anzahl von hospitalisierten COVID-19-Fällen mit Meldedatum innerhalb der sieben vorhergehenden Tage - inklusive der noch nicht an das RKI berichteten Hospitalisierungen.  

Datengrundlage des Nowcastings sind die [Hospitalisierten COVID-19-Fälle nach Bundesland und Altersgruppe](#Hospitalisierte-COVID-19-Fälle-nach-Bundesland-und-Altersgruppe). Eine ausführliche Dokumentation über [Methoden, Instrumente und Verlauf der Datengenerierung](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung#methoden-instrumente-und-verlauf-der-datengenerierung) ist im Datensatz des [Nowcastings der Infektionszahlen](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung) zu finden. Um keine Verwirrung in Bezug auf das Nowcasting der Infektionszahlen zu erzeugen, wird in der Benennung der Daten auf den Begriff “Nowcasting” verzichtet und stattdessen von der adjustierten Anzahl von COVID-19-Hospitalisierungen gesprochen.

>[Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/master/Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv)
>[JJJJ-MM-TT_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/tree/master/Archiv)

Die adjustierten COVID-19-Hospitalisierungen auf Länderebene werden täglich bereitgestellt. Im Dateinamen repräsentiert die Sequenz “JJJJ-MM-TT” das Erstellungsdatum der Datei und gleichzeitig das Datum des enthaltenen Datenstands um 0:00 Uhr. “JJJJ” steht dabei für das Jahr, “MM” für den Monat und “TT” für den Tag der Erstellung bzw. des enthaltenen Datenstands.  

### Variablen 

Die adjustierte Anzahl von COVID-19-Hospitalisierungen wird nach folgenden Merkmalen differenziert (in den Klammern finden sich die Variablen dieser Merkmale):  

* Berichtsdatum der adjustierten COVID-19-Hospitalisierungen (Datum)  
* Bundesland (Bundesland, Bundesland_Id)  
* Bevölkerungsgruppe (Altersgruppe, Bevoelkerung)  
* 7-Tage-Fallzahl der hospitalisierten COVID-19-Fälle (fixierte_7T_Hospitalisierung_Faelle, aktualisierte_7T_Hospitalisierung_Faelle )
* adjustierte 7-Tage-Fallzahl der hospitalisierten COVID-19-Fälle (PS_7T_Hospitalisierung_Faelle, UG_PI_adjustierte_7T_Hospitalisierung_Faelle, OG_PI_adjustierte_7T_Hospitalisierung_Faelle)  
* 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (fixierte_7T_Hospitalisierung_Inzidenz, aktualisierte_7T_Hospitalisierung_Inzidenz)
* adjustierte 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (PS_7T_Hospitalisierung_Inzidenz, UG_PI_adjustierte_7T_Hospitalisierung_Inzidenz, OG_PI_adjustierte_7T_Hospitalisierung_Inzidenz)  

Ein Einträge nehmen eine eineindeutige Ausprägungen an. Die adjustierte 7-Tage-Hospitalisierungsinzidenz berechnet sich aus der adjustierten Anzahl der hospitalisierten COVID-19-Fälle der letzten sieben Tage (vorherig des Berichtsdatums) und der Bevölkerungszahl. Zur einheitlichen Darstellung wird die Inzidenz auf 100.000 Einwohner:innen normiert.

### Variablenausprägungen
Die Hospitalisierungsdaten enthalten die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen:  

| Variable | Typ | Ausprägung | Beschreibung |
| -------- | --- | ---------- | ------------ |
| Datum |Datum |```JJJJ-MM-TT``` | Berichtsdatum der 7-Tage-Hospitalisierungsinzidenz |
| Bundesland | Text | ```Bundesgebiet``` <br/> ```Schleswig-Holstein``` <br/> ```[...]``` <br/> ```Thüringen``` | Name des Bundeslandes sowie ein Wert für das gesamte Bundesgebiet | 
| Bundesland_Id| Text | ```00``` : Bundesgebiet <br/> ```01```&nbsp;bis&nbsp;```16```:&nbsp;Bundesland&nbsp;ID  | Identifikationsnummer des Bundeslandes basierend auf dem Amtlichen Gemeindeschlüssel (AGS) sowie ein Wert für das gesamte Bundesgebiet|
| Altersgruppe | Text | ```00+``` (alle Altersgruppen) | Altersgruppe der  hospitalisierten COVID-19-Fälle |
| fixierte_7T _Hospitalisierung_Faelle| Natürliche Zahl | ```≥0```| Tagesaktuell berichtete Summe der hospitalisierten COVID-19-Fälle mit Altersangabe und Meldedatum innerhalb der letzten 7 Tage | 
| aktualisierte_7T _Hospitalisierung_Faelle| Natürliche Zahl | ```≥0```| Summe der hospitalisierten COVID-19-Fälle mit Altersangabe und Meldedatum innerhalb der letzten 7 Tage inklusive eingetroffener Nachmeldungen| 
| PS_adjustierte_7T _Hospitalisierung_Faelle| Natürliche Zahl | ```≥0``` | Punktschätzer der hospitalisierten COVID-19-Fälle der letzten 7 Tage|
| UG_PI_adjustierte_ 7T_Hospitalisierung_Faelle | Natürliche Zahl|```≥0```  | Untere Grenze des 95%-Prädiktionsintervalls der hospitalisierten COVID-19-Fälle der letzten 7 Tage |
| OG_PI_adjustierte_ 7T_Hospitalisierung_Faelle | Natürliche Zahl| ```≥0``` | Obere Grenze des 95%-Prädiktionsintervalls der hospitalisierten COVID-19-Fälle der letzten 7 Tage |
| Bevoelkerung | Natürliche&nbsp;Zahl | ```≥0``` | Bevölkerungszahl für die Berechnung der adjustierten 7-Tage-Inzidenz |
| fixierte_7T _Hospitalisierung_Inzidenz | Rationale Zahl | ```≥0``` | Tagesaktuell berichtete 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (nach Meldedatum des Falles) bezogen auf 100.000 Einwohner:innen |
| aktualisierte_7T _Hospitalisierung_Inzidenz | Rationale Zahl | ```≥0``` | 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (nach Meldedatum des Falles) bezogen auf 100.000 Einwohner:innen unter Berücksichtigung eingetroffener Nachmeldungen |
| PS_adjustierte_ 7T_Hospitalisierung_Inzidenz | Rationale Zahl | ```≥0```|Punktschätzer der 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle |
| UG_PI_adjustierte_ 7T_Hospitalisierung_Inzidenz | Rationale Zahl | ```≥0``` | Untere Grenze des 95%-Prädiktionsintervalls der 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle |
| OG_PI_adjustierte_ 7T_Hospitalisierung_Inzidenz | Rationale Zahl | ```≥0``` | Obere Grenze des 95%-Prädiktionsintervalls der 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle |

#### Keine adjustierte Anzahl von Hospitalisierungen für den aktuellen und die zurückliegenden beiden Tage

Die Schätzung der adjustierten Anzahl von COVID-19-Hospitalisierungen ist für die Werte der letzten 3 Tage teilweise instabil, insbesondere wenn eine große Zahl von Nachmeldungen erwartet wird. Aus Gründen des Qualitätsmanagements, wird daher auf die Angabe der adjustierten Werte für den aktuellen und die zurückliegenden 2 Tage verzichtet. 

## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf GitHub.com sowie Zenodo.org bereitgestellt:  
* https://github.com/robert-koch-institut
* https://zenodo.org/communities/robertkochinstitut  

### Lizenz  

Der Datensatz "COVID-19-Hospitalisierungen in Deutschland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de)

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede:r hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](/LICENSE) bzw. [LIZENZ](/LIZENZ) Datei des Datensatzes.  
