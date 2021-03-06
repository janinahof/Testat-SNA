# Kohlekommission Datensatz (Testat SNA)  #
Codebuch Stand 2020-07-31   
erstellt von Janina Hofmann (jh231@hdm-stuttgart.de)

## Inhalt
- Edgelist_Testat.csv (Edgelist)
- Nodelist_Testat.csv (Nodelist)
- Codebuch_Testat.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Für das Testat habe ich die Mitglieder der Kohlekommission untersucht und dabei folgende Datenquellen verwendet:

https://www.munzinger.de/search/start.jsp

https://www.abgeordnetenwatch.de/

https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission

https://www.bmwi.de/Redaktion/DE/Pressemitteilungen/2018/20180606-bundeskabinett-setzt-kommission-wachstum-strukturwandel-und-beschaeftigung-ein.html

Bei dem Netzwerk handelt es sich um ein *ungerichtetes two-mode Akteursnetzwerk*.

# Codebuch																	
																	
# edgelist		

**from**	ID Mitglied der Kommission																
**to**	Alle Mitgliedschaften der Person																
																	
# nodelist	

**id**	Identische ID wie aus der Edgelist


**label**	Vollständige Bezeichnung der Knoten																

**type**	1 = Person 2 = Organisation 3 = Partei 4 = Unternehmen															

**sex**	(Geschlecht der Mitglieder) 1 = männlich 2 = weiblich	


**age**	(Alter der Mitglieder) 1 = 20-30 Jahre 2 = 30-40 Jahre 3 = 40-50 Jahre 4 = 50-60 Jahre 5 = 60-70 Jahre 6 = 70-80 Jahre 7 = 80-90 Jahre 8 = tot		


**party**	1 = keine, 2 = CDU 3 = SPD 4 = FDP 5 = Grüne																

**representation**	(Funktion innerhalb der Kommission)  1 = Politik 2 = Wirtschaft 3 = Gewerkschaft 4 = Umwelt 5 = Regionen 6 = Wissenschaft 7 = Soziales	


**position**	(Position innerhalb der Kommission) 1 = kein Stimmrecht 2 = Mitglied 3 = Vorsitz


**state**	(Bundesland) 1 = Baden Württemberg 2 = Bayern 3 = Berlin 4 = Brandenburg 5 = Bremen 6 = Hamburg 7 = Hessen 8 = Mecklenburg-Vorpommern 9 = Niedersachsen 10 = Nordrhein-Westfalen 11 = Rheinland-Pfalz 12 = Saarland 13 = Sachsen 14 = Sachsen-Anhalt 15 = Schleswig-Holstein 16 = Thüringen																																
