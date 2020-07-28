Codebuch

testat_edgelist.csv (Edgelist)
testat_nodelist.csv (Nodelist)
Codebuch.md (Codierung der Datensätze)

Ursprung und Datenerhebung

Im Zentrum der Analyse steht das Netzwerk der Kohlekommission, welches auf seine Mitglieder und deren Mitgliedschaften in weiteren Organisationen (Parteien) untersucht und interpretiert werden soll. Als Grundlage für die Analyse dienen ein Artikel der Klimareporter über die Mitglieder der Kohlekommission (https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission), ergänzend dazu das Munzinger Archiv (https://www.munzinger.de/search/start.jsp) und die Pressemeldung des Bundesministerium für Wirtschaft zur Kommission (https://www.bmwi.de/Redaktion/DE/Pressemitteilungen/2018/20180606-bundeskabinett-setzt-kommission-wachstum-strukturwandel-und-beschaeftigung-ein.html). Es wird ein ungerichtetes two-mode Netzwerk (Akteur-Organisations-Netzwerk) aus Personen/Mitgliedern der Kohlekommission und Organisationen erstellt. Fehlende Daten werden mit 99 kodiert.

Edgelist

Id

(eindeutige Codierung des Knoten, jede ID entspricht einem Mitglied oder einer Organisation)

From (id Mitglied der Kommission)

To (id alle Mitgliedschaften der Person in anderen Organisation wie zB politische Parteien, Unternehmen, Verbände, Vereine)

Nodelist

Id (Identische ID wie aus der Edgelist)

Label (Vollständige Bezeichnung der Knoten)

Type (Handelt es sich um eine Person, Organisation, Partei oder Unternehmen?) 1 = Person 2 = Organisation 3 = Partei 4 = Unternehmen

Sex (Geschlecht der Mitglieder) 1 = männlich 2 = weiblich

Age (Alter der Mitglieder) 1 = 20-30 Jahre 2 = 30-40 Jahre 3 = 40-50 Jahre 4 = 50-60 Jahre 5 = 60-70 Jahre 6 = 70-80 Jahre 7 = 80-90 Jahre 8 = tot

Party (Ist die Person Mitglied einer politischen Partei?) "1 = keine, 2 = CDU 3 = SPD 4 = FDP 5 = Grüne"

Representation (Funktion innerhalb der Kommission)  1 = Politik 2 = Wirtschaft 3 = Gewerkschaft 4 = Umwelt 5 = Regionen 6 = Wissenschaft 7 = Soziales

Position (Position innerhalb der Kommission) 1 = kein Stimmrecht 2 = Mitglied 3 = Vorsitz

State (Bundesland) 1 = Baden Württemberg 2 = Bayern 3 = Berlin 4 = Brandenburg 5 = Bremen 6 = Hamburg 7 = Hessen 8 = Mecklenburg-Vorpommern 9 = Niedersachsen 10 = Nordrhein-Westfalen 11 = Rheinland-Pfalz 12 = Saarland 13 = Sachsen 14 = Sachsen-Anhalt 15 = Schleswig-Holstein 16 = Thüringen

Proclimate (Tätigkeit im Bereich Klima- oder Umweltschutz) 1 = Ja 2 = Nein
