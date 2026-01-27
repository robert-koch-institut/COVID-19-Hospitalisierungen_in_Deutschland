<!-- HEADER_START: {"lang": "de"} -->


Dokumentation  

# COVID-19-Hospitalisierungen in Deutschland

<br> 
<br> 
<br> 

[**Robert Koch-Institut**](http://www.rki.de/)

<br> 

**Beitragende**   
[Alexander Ullrich](https://orcid.org/0000-0002-4894-6124)&sup1;, [Matthias an der Heiden](https://orcid.org/0000-0001-5863-4549)&sup2;, [Michaela Diercke](https://orcid.org/0000-0002-4678-1813)&sup1;, & [Hannes Wünsche](https://orcid.org/0000-0002-8837-0326)&sup3;

&emsp;&emsp;&sup1; [Robert Koch-Institut](http://www.rki.de/) | [Fachgebiet 32](https://www.rki.de/fg32)  
&emsp;&emsp;&sup2; [Robert Koch-Institut](http://www.rki.de/) | [Fachgebiet 34](https://www.rki.de/fg34)  
&emsp;&emsp;&sup3; [Robert Koch-Institut](http://www.rki.de/) | [Fachgebiet MF 4](https://www.rki.de/mf4)

<br> 

**Zitieren**  
Robert Koch-Institut. (2026). COVID-19-Hospitalisierungen in Deutschland [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.18383738](https://doi.org/10.5281/zenodo.18383738)

<br>


**Zusammenfassung**    
Im Datensatz "COVID-19-Hospitalisierungen in Deutschland" des Robert Koch-Institutswerden täglich aktualisierte Informationen zu Hospitalisierungen im Zusammenhang mit COVID-19 basierend auf den Meldungen nach dem Infektionsschutzgesetz (IfSG) bereitgestellt. Neben tagesaktuellen Fallzahlen und Inzidenzen auf Bundes- und Länderebene enthält der Datensatz auch modellgestützte Schätzungen verzögert gemeldeter Hospitalisierungen mittels Nowcasting. Ziel ist es, die tatsächliche Belastung des Gesundheitssystems durch COVID-19 besser abzubilden, insbesondere durch die Berechnung adjustierter 7-Tage-Hospitalisierungsinzidenzen.

<br>

**Inhaltsverzeichnis**  

<!-- TOC_START: {"heading_depth": 2} -->
  - [Informationen zum Datensatz und Entstehungskontext](#informationen-zum-datensatz-und-entstehungskontext)  
  - [Aufbau und Inhalt des Datensatzes](#aufbau-und-inhalt-des-datensatzes)  
  - [Hinweise zur Nachnutzung der Daten](#hinweise-zur-nachnutzung-der-daten)  
<!-- TOC_END -->

<br>

<!-- HEADER_END -->



## Informationen zum Datensatz und Entstehungskontext 

Im Datensatz "COVID-19-Hospitalisierungen in Deutschland" werden die aktuellen Zahlen der nach den Vorgaben des [Infektionsschutzgesetzes - IfSG -](https://www.gesetze-im-internet.de/ifsg/index.html) erfassten hospitalisierten COVID-19-Fälle bereitgestellt.  
Um den Trend der Anzahl von Hospitalisierungen und der 7-Tage-Hospitalisierungsinzidenz besser bewerten zu können, wird die berichtete Hospitalisierungsinzidenz um eine Schätzung der zu erwartenden Anzahl an verzögert berichteten Hospitalisierungen ergänzt. Neben den Daten der gemeldeten COVID-19-Hospitalisierungen auf Bundes- und Länderebene wird daher ein Nowcasting der Anzahl hospitalisierter Fälle und der 7-Tage-Hospitalisierungsinzidenz auf Bundesebene durchgeführt. Ziel ist die Schätzung der Anzahl von hospitalisierten COVID-19-Fällen mit Meldedatum innerhalb der sieben vorhergehenden Tage - inklusive der noch nicht an das RKI berichteten Hospitalisierungen. Aufbauend auf dem Nowcasting wird eine Schätzung der adjustierten 7-Tage-Hospitalisierungsinzidenz durchgeführt.  

### Administrative und organisatorische Angaben  

Die zugrundeliegenden Hospitalisierungsdaten werden an das Robert Koch-Institut (RKI) über das Meldesystem gemäß IfSG übermittelt. Zuständig für den Betrieb des Meldesystems ist das [Fachgebiet 32 | Surveillance | ÖGD-Kontaktstelle](https://www.rki.de/fg32) des RKI. Die Verarbeitung und Aufbereitung der im Meldesystem vorliegenden Rohdaten erfolgt durch das [Fachgebiet IT 4 | Infektionsepidemiologische Fach-IT und Anwendungsentwicklung](https://www.rki.de/fg31). Die Berechnung der adjustierten Anzahl hospitalisierter Fälle und der adjustierten 7-Tage-Hospitalisierungsinzidenz erfolgt durch [Matthias an der Heiden](https://orcid.org/0000-0001-5863-4549), wissenschaftlicher Mitarbeiter des [Fachgebiet 34 | HIV/AIDS und andere sexuell oder durch Blut übertragbare Infektionen](https://www.rki.de/fg34). Inhaltliche Fragen bezüglich der COVID-19-Hospitalisierungen in Deutschland können an das RKI unter [info@rki.de](mailto:info@rki.de) gestellt werden.  
Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgt durch das Fachgebiet [MF 4 | Forschungsdatenmanagement](https://www.rki.de/mf4). Fragen zum Datenmanagement können an das Open Data Team des Fachgebiets MF4 gerichtet werden ([OpenData@rki.de](mailto:OpenData@rki.de)).  

### Erhebung und Aufbereitung der Daten  

Gemäß Infektionsschutzgesetz müssen der Verdacht, die Erkrankung, die Aufnahme und der Tod in Bezug auf COVID-19 sowie der Nachweis von SARS-CoV-2 an das Gesundheitsamt gemeldet werden.  
Die Meldung muss unverzüglich erfolgen und dem Gesundheitsamt spätestens innerhalb von 24 Stunden vorliegen. Dabei müssen auch Name, Adresse und Kontaktdaten der betroffenen Person gemeldet werden, damit das Gesundheitsamt die Person kontaktieren kann und die notwendigen Maßnahmen (z.B. Isolierung der betroffenen Person, Ermittlung von Kontaktpersonen) einleiten kann.  
Der Meldeweg vom Arzt oder anderen Meldepflichtigen zum Gesundheitsamt läuft derzeit noch routinemäßig per Fax, selten per Telefon oder E-Mail. Seit Mitte Juni 2020 haben Labore die Möglichkeit, Erregernachweise von SARS-CoV-2 elektronisch an das zuständige Gesundheitsamt zu melden (erste Ausbaustufe des [Deutschen Elektronischen Melde- und Informationssystems für den Infektionsschutz - DEMIS](https://www.rki.de/DE/Themen/Infektionskrankheiten/Meldewesen/DEMIS/DEMIS_inhalt.html)). Für Labore ist die Meldung von SARS-CoV-2-Erregernachweisen über DEMIS seit dem 01.01.2021 verpflichtend.

COVID-19-Fälle, die die Falldefintionen des RKI erfüllen, müssen vom zuständigen Gesundheitsamt, spätestens am nächsten Arbeitstag, elektronisch an die zuständige Landesbehörde und von dort, spätestens am nächsten Arbeitstag, an das RKI übermittelt werden, allerdings ohne Name, Wohnort und Kontaktdaten der Betroffenen. In der aktuellen Lage übermitteln die meisten Gesundheitsämter früher und häufiger als gesetzlich vorgesehen, meist täglich und auch am Wochenende. Allerdings kann es bei der Übermittlung der Fälle auch zu einem Melde- und Übermittlungsverzug von einigen Tagen kommen.

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

#### Bevölkerungsdaten  

Die für die Berechnung der Inzidenzen bezieht das RKI Bevölkerungsdaten durch das Statistisches Bundesamt (Destatis), Referat F24 | Bevölkerungsfortschreibung, Ausländer- und Integrationsstatistiken. Detaillierte Informationen und Ergebnisse des Statistischen Bundesamtes bietet der Themenbereiche „[Bevölkerungstand](https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Bevoelkerung/Bevoelkerungsstand/_inhalt.html)“ und die Datenbank [GENESIS-Online](https://www-genesis.destatis.de/genesis/online?sequenz=tabellen&selectionname=12411*#abreadcrumb), sowie die [Regionaldatenbank Deutschland](https://www.regionalstatistik.de/genesis/online?operation=statistic&levelindex=0&levelid=1664438374999&code=12411#abreadcrumb) des Bundes und der Länder. Die Daten zur Bevölkerung lassen sich in sich durch den Filtercode "12411" aufrufen.   

Für die Berechnung der Inzidenzen werden jeweils die Bevölkerungszahlen des entsprechenden Jahres verwendet (z. B. für das Jahr 2020 die Bevölkerungsdaten von 2020). Da aktuelle Bevölkerungsstatistiken zeitverzögert veröffentlicht werden, werden für jüngere Zeiträume, für die noch keine Daten vorliegen, die zuletzt verfügbaren Bevölkerungszahlen herangezogen. Aktuell (Datenstand: 2025-01-08) werden daher für die Jahre 2023, 2024 und 2025 die Bevölkerungszahlen des Jahres 2022 verwendet. Eine Umstellung auf die jeweils neuesten Zahlen ist stets angestrebt. Dabei kann es jedoch zu sprunghaften Änderungen der Inzidenzen kommen.

## Aufbau und Inhalt des Datensatzes

Der Datensatz enthält epidemiologische Daten zur Anzahl und 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle nach Bundesland und Altersgruppen in Deutschland. Im Datensatz enthalten sind:  

* Hospitalisierte COVID-19-Fälle auf Bundes- und Länderebene  
* Berechnung der adjustierten COVID-19-Hospitalisierungen auf Bundesebene  
* Lizenz-Datei mit der Nutzungslizenz des Datensatzes in Deutsch und Englisch  
* Datensatzdokumentation in deutscher Sprache  
* Metadaten-Datei zum Import in Zenodo  

### Hospitalisierte COVID-19-Fälle nach Bundesland und Altersgruppe  

Die Hospitalisierungsdaten bilden einen tagesaktuellen Stand (00:00 Uhr) aller über das Meldesystem gemäß Infektionsschutzgesetz an das RKI übermittelten COVID-19-Fälle, bei denen eine Hospitalisierung angegeben ist, ab. Das bedeutet, dass alle, bis 00:00 Uhr des Tages, von den Gesundheitsämtern über die zuständigen Landesbehörden an das RKI übermittelten Hospitalisierungen mit Bezug zu COVID-19 im Datenstand enthalten sind. Die Daten werden täglich vollständig neu erzeugt, dieser Datenstand ersetzt den Datenstand des Vortages.  

>[Aktuell_Deutschland_COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Aktuell_Deutschland_COVID-19-Hospitalisierungen.csv)


#### Variablen und Variablenausprägungen

Die Hospitalisierungsdaten differenzieren verschiedenen Merkmale. Grundlegend nach folgende Merkmale differenziert (in den Klammern finden sich die Variablen dieser Merkmale):  

* Berichtsdatum der 7-Tage-Hospitalisierungsinzidenz 
* Bundesland   
* Altersgruppe 
* 7-Tage-Fallzahl der hospitalisierten COVID-19-Fälle 
* 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle 

Ein Einträge nehmen eine eineindeutige Ausprägung hinsichtlich der Anzahl der Hospitalisierungen der letzten 7 Tage, einer Altersgruppe eines Bundeslands an. Die 7-Tage-Hospitalisierungsinzidenz berechnet sich aus der Anzahl der an das RKI übermittelten COVID-19-Fälle mit Meldedatum innerhalb der sieben vorgehenden Tage und der Bevölkerungszahl der entsprechenden Altersgruppe des Bundeslandes (bzw. des gesamten Bundesgebiets). Zur einheitlichen Darstellung wird die Inzidenz auf 100.000 Einwohner:innen normiert.  

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Aktuell_Deutschland_COVID-19-Hospitalisierungen", "lang": "de"} -->

Die Datei [Aktuell_Deutschland_COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Aktuell_Deutschland_COVID-19-Hospitalisierungen.csv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Aktuell_Deutschland_COVID-19-Hospitalisierungen.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Metadaten/schemas/tableschema_Aktuell_Deutschland_COVID-19-Hospitalisierungen.json) hinterlegt:
> [tableschema_Aktuell_Deutschland_COVID-19-Hospitalisierungen.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Metadaten/schemas/tableschema_Aktuell_Deutschland_COVID-19-Hospitalisierungen.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                         | Typ     | Ausprägungen                                                                                       | Beschreibung                                                                                                                           |
|:---------------------------------|:--------|:---------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------|
| Datum                            | date    | Format: `YYYY-MM-DD`                                                                               | Berichtsdatum der 7-Tage-Hospitalisierungsinzidenz.                                                                                    |
| Bundesland                       | string  | Werte:<br>`Baden-Württemberg`, `Bayern`, `Berlin`, `Brandenburg`, `Bremen`, `Hamburg`, `Hessen`, … | Name des Bundeslandes sowie ein Wert für das gesamte Bundesgebiet                                                                      |
| Bundesland_Id                    | string  | Werte:<br>`01`, `02`, `03`, `04`, `05`, `06`, `07`, …                                              | Identifikationsnummer des Bundeslandes basierend auf dem Amtlichen Gemeindeschlüssel (AGS) sowie ein Wert für das gesamte Bundesgebiet |
| Altersgruppe                     | string  | Werte:<br>`00+`, `00-04`, `05-14`, `15-34`, `35-59`, `60-79`, `80+`                                | Altersgruppe der  hospitalisierten COVID-19-Fälle                                                                                      |
| 7T_Hospitalisierung_<br>Faelle   | integer | Werte: `≥0`                                                                                        | Summe der hospitalisierten COVID-19-Fälle mit Meldedatum innerhalb der letzten 7 Tage                                                  |
| 7T_Hospitalisierung_<br>Inzidenz | number  | Werte: `≥0`                                                                                        | 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (nach Meldedatum des Falles) bezogen auf 100.000 Bevölkerung                       |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


#### Formatierung

Die Daten sind im Datensatz als kommaseparierte .csv Datei enthalten. Der verwendete Zeichensatz der .csv Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",".

- Zeichensatz: UTF-8
- .csv Trennzeichen: Komma ","


### Adjustierte COVID-19-Hospitalisierungen auf Länderebene  

Zwischen dem Beginn des Krankenhausaufenthalts eines COVID-19-Falles und dem Zeitpunkt, an dem diese Information am RKI eingeht, entsteht ein zeitlicher Verzug. Um den Trend der Anzahl von Hospitalisierungen und der 7-Tage-Hospitalisierungsinzidenz besser bewerten zu können, ergänzen wir die berichtete Hospitalisierungsinzidenz um eine Schätzung der zu erwartenden Anzahl an verzögert berichteten Hospitalisierungen. Neben den Daten der gemeldeten COVID-19-Hospitalisierungen auf Bundes- und Länderebene wird daher ein Nowcasting der Anzahl hospitalisierter Fälle und der 7-Tage-Hospitalisierungsinzidenz auf Bundes- und Länderebene durchgeführt. Ziel ist die Schätzung der Anzahl von hospitalisierten COVID-19-Fällen mit Meldedatum innerhalb der sieben vorhergehenden Tage - inklusive der noch nicht an das RKI berichteten Hospitalisierungen.  

Datengrundlage des Nowcastings sind die [Hospitalisierten COVID-19-Fälle nach Bundesland und Altersgruppe](#Hospitalisierte-COVID-19-Fälle-nach-Bundesland-und-Altersgruppe). Eine ausführliche Dokumentation über [Methoden, Instrumente und Verlauf der Datengenerierung](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung#methoden-instrumente-und-verlauf-der-datengenerierung) ist im Datensatz des [Nowcastings der Infektionszahlen](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung) zu finden. Um keine Verwirrung in Bezug auf das Nowcasting der Infektionszahlen zu erzeugen, wird in der Benennung der Daten auf den Begriff “Nowcasting” verzichtet und stattdessen von der adjustierten Anzahl von COVID-19-Hospitalisierungen gesprochen.

>[Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv) 

#### Variablen und Variablenausprägungen

Die adjustierte Anzahl von COVID-19-Hospitalisierungen wird nach folgenden Merkmalen differenziert (in den Klammern finden sich die Variablen dieser Merkmale):  

* Berichtsdatum der adjustierten COVID-19-Hospitalisierungen (Datum)  
* Bundesland 
* Bevölkerungsgruppe 
* 7-Tage-Fallzahl der hospitalisierten COVID-19-Fälle 
* adjustierte 7-Tage-Fallzahl der hospitalisierten COVID-19-Fälle 
* 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle 
* adjustierte 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle 

Ein Einträge nehmen eine eineindeutige Ausprägungen an. Die adjustierte 7-Tage-Hospitalisierungsinzidenz berechnet sich aus der adjustierten Anzahl der hospitalisierten COVID-19-Fälle der letzten sieben Tage (vorherig des Berichtsdatums) und der Bevölkerungszahl. Zur einheitlichen Darstellung wird die Inzidenz auf 100.000 Einwohner:innen normiert.

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen", "lang": "de"} -->

Die Datei [Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.csv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Metadaten/schemas/tableschema_Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.json) hinterlegt:
> [tableschema_Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Metadaten/schemas/tableschema_Aktuell_Deutschland_adjustierte-COVID-19-Hospitalisierungen.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                                           | Typ     | Ausprägungen                                                                                       | Beschreibung                                                                                                                                                             |
|:---------------------------------------------------|:--------|:---------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Datum                                              | date    | Format: `YYYY-MM-DD`                                                                               | Berichtsdatum der 7-Tage-Hospitalisierungsinzidenz                                                                                                                       |
| Bundesland                                         | string  | Werte:<br>`Baden-Württemberg`, `Bayern`, `Berlin`, `Brandenburg`, `Bremen`, `Hamburg`, `Hessen`, … | Name des Bundeslandes sowie ein Wert für das gesamte Bundesgebiet                                                                                                        |
| Bundesland_Id                                      | string  | Werte:<br>`01`, `02`, `03`, `04`, `05`, `06`, `07`, …                                              | Identifikationsnummer des Bundeslandes basierend auf dem Amtlichen Gemeindeschlüssel (AGS) sowie ein Wert für das gesamte Bundesgebiet                                   |
| Altersgruppe                                       | string  | Werte:<br>`00+`                                                                                    | Altersgruppe der  hospitalisierten COVID-19-Fälle                                                                                                                        |
| fixierte_7T_<br>Hospitalisierung_Faelle            | integer | Werte: `≥0`                                                                                        | Tagesaktuell berichtete Summe der hospitalisierten COVID-19-Fälle mit Altersangabe und Meldedatum innerhalb der letzten 7 Tage                                           |
| aktualisierte_7T_<br>Hospitalisierung_Faelle       | integer | Werte: `≥0`                                                                                        | Summe der hospitalisierten COVID-19-Fälle mit Altersangabe und Meldedatum innerhalb der letzten 7 Tage inklusive eingetroffener Nachmeldungen                            |
| PS_adjustierte_7T_<br>Hospitalisierung_Faelle      | integer | Werte: `≥0`<br>Fehlende Werte:<br>`NA`                                                             | Punktschätzer der hospitalisierten COVID-19-Fälle der letzten 7 Tage                                                                                                     |
| UG_PI_adjustierte_7T_<br>Hospitalisierung_Faelle   | integer | Werte: `≥0`<br>Fehlende Werte:<br>`NA`                                                             | Untere Grenze des 95%-Prädiktionsintervalls der hospitalisierten COVID-19-Fälle der letzten 7 Tage                                                                       |
| OG_PI_adjustierte_7T_<br>Hospitalisierung_Faelle   | integer | Werte: `≥0`<br>Fehlende Werte:<br>`NA`                                                             | Obere Grenze des 95%-Prädiktionsintervalls der hospitalisierten COVID-19-Fälle der letzten 7 Tage                                                                        |
| Bevoelkerung                                       | integer | Werte: `≥0`                                                                                        | Bevölkerungszahl für die Berechnung der adjustierten 7-Tage-Inzidenz                                                                                                     |
| fixierte_7T_<br>Hospitalisierung_Inzidenz          | number  | Werte: `≥0`                                                                                        | Tagesaktuell berichtete 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (nach Meldedatum des Falles) bezogen auf 100.000 Einwohner:innen                             |
| aktualisierte_7T_<br>Hospitalisierung_Inzidenz     | number  | Werte: `≥0`                                                                                        | 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle (nach Meldedatum des Falles) bezogen auf 100.000 Einwohner:innen unter Berücksichtigung eingetroffener Nachmeldungen |
| PS_adjustierte_7T_<br>Hospitalisierung_Inzidenz    | number  | Werte: `≥0`<br>Fehlende Werte:<br>`NA`                                                             | Punktschätzer der 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle                                                                                                    |
| UG_PI_adjustierte_7T_<br>Hospitalisierung_Inzidenz | number  | Werte: `≥0`<br>Fehlende Werte:<br>`NA`                                                             | Untere Grenze des 95%-Prädiktionsintervalls der 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle                                                                      |
| OG_PI_adjustierte_7T_<br>Hospitalisierung_Inzidenz | number  | Werte: `≥0`<br>Fehlende Werte:<br>`NA`                                                             | Obere Grenze des 95%-Prädiktionsintervalls der 7-Tage-Inzidenz der hospitalisierten COVID-19-Fälle                                                                       |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->

##### Keine adjustierte Anzahl von Hospitalisierungen für den aktuellen und die zurückliegenden beiden Tage

Die Schätzung der adjustierten Anzahl von COVID-19-Hospitalisierungen ist für die Werte der letzten 3 Tage teilweise instabil, insbesondere wenn eine große Zahl von Nachmeldungen erwartet wird. Aus Gründen des Qualitätsmanagements, wird daher auf die Angabe der adjustierten Werte für den aktuellen und die zurückliegenden 2 Tage verzichtet. 

#### Formatierung

Die Daten sind im Datensatz als kommaseparierte .csv Datei enthalten. Der verwendete Zeichensatz der .csv Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",".

- Zeichensatz: UTF-8
- .csv Trennzeichen: Komma ","


<!-- FOOTER_START: {"lang": "de"} -->



### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:  

> [Metadaten/](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/tree/main/Metadaten/) 

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter [https://developers.zenodo.org/#representation](https://developers.zenodo.org/#representation) nachlesbar.
 
> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/Metadaten/zenodo.json)  

In der zenodo.json ist neben dem Publikationsdatum (`"publication_date"`) auch der Datenstand in folgendem Format enthalten (Beispiel):  

```
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Created",
      "description": "Date when the published data was created"
    }
  ],
```    


Zusätzlich beschreiben wir tabellarische Daten mithilfe des [Data Package Standards](https://datapackage.org/).
Ein Data Package ist eine strukturierte Sammlung von Daten und zugehörigen Metadaten, die den Austausch und die Wiederverwendung von Daten erleichtert. Es besteht aus einer datapackage.json-Datei, die zentrale Informationen wie die enthaltenen Ressourcen, ihre Formate und Schema-Definitionen beschreibt.

Der Data Package Standard wird von der [Open Knowledge Foundation](https://okfn.org/) bereitgestellt und ist ein offenes Format, das eine einfache, maschinenlesbare Beschreibung von Datensätzen ermöglicht.

Die Liste der in diesem Repository enthaltenen Daten ist in folgender Datei hinterlegt:

> [datapackage.json](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/tree/main/datapackage.json)

Für tabellarische Daten definieren wir zusätzlich ein [Table Schema](https://datapackage.org/standard/table-schema/), das die Struktur der Tabellen beschreibt, einschließlich Spaltennamen, Datentypen und Validierungsregeln. Diese Schema-Dateien finden sich unter:

> [Metadaten/schemas/](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/tree/main/Metadaten/schemas) 



## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://zenodo.org/communities/robertkochinstitut  
- https://github.com/robert-koch-institut  
- https://gitlab.opencode.de/robert-koch-institut  
- https://edoc.rki.de/  


 
### Lizenz  

Der Datensatz "COVID-19-Hospitalisierungen in Deutschland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/COVID-19-Hospitalisierungen_in_Deutschland/blob/main/LIZENZ) Datei des Datensatzes.  
<!-- FOOTER_END -->