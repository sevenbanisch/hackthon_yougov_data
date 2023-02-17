# Herzlich Willkommen!

Am 24. und 25. Februar finden wir uns in einem Seminar zusammen, in dem wir Umfragedaten zur Coronapandemie sowie den Maßnahmen, sie einzudämmen, im Hinblick auf Polarisierungsphänomene ins Visier nehmen. In diesem **repository** teilen wir unsere Entwicklungen und Analysen. 

## Struktur des Repositories

### ./data: 
Dort liegen die Daten und dort speichern wir Daten (z.B. ausgewählte Slices  nach Zeit oder Land). Wichtig zu wissen: die Originaldaten sind 750 MB groß und liegen nicht dort. Derzeit stelle ich zwei Subdatensätze zur Verfügung: alle Daten jeweils für Deutschland und die UK.

Enthält derzeit:
- all_countries_numerical_germany.csv
- all_countries_numerical_united-kingdom.csv
- codebook_sb.xlsx

### ./preparations: 
Dort arbeite ich an der Vorbereitung des Hackathons. Die Skripte könnt ihr anschauen, ausprobieren (nicht das NB **splitdatabycountry.ipynb**). Siehe unten bei „Was gibt es schon?“. Wichtig: falls ihr in den NBs (neue) Dinge ausprobieren wollt, legt euch bitte einen eigenen Ordner mit eurem Namen an. Siehe nächster Punkt.

### ./hackathon/euer_name:
Das ist eure Spielwiese! Liegt euch in **./hackthon** einen Ordnerin eurem Namen an. Kopiert euch NBs, auf denen ihr aufbauen wollte hier rein und los geht’s.

### ./private:
Dies ist ein Ordner, der **nicht synchronisiert** wird. D.h. ihr seht ihn nicht. Ich würde aber empfehlen, euch lokal diesen Ordner anzulegen. Ich benutze ihn beispielsweise, um eigene Analysen und Resultate zu speichern und aufzubereiten.


## Was gibt es schon?

Alles, was im Ordner **./preparations** liegt. Für den Start:

### codebook.ipynb: 
Dieses script läd das codebook (**codebook_sb.xlsx**) und gibt einen Überblick über die Fragen. Ich benutze den Code in anderen scripts, um z.B. auf den Wortlaut der Fragen zugreifen zu können.

### splitdatabycountry.ipynb:
Dieses NB liest den Gesamtdatensatz ein und gibt einen Überblick über die Länder, in denen das Survey lief. Anschauen lohnt sich!

***Dieses script kann nicht ausgeführt werden***. Ich verwende es, um Sub-Datensätze für die einzelnen Länder zu erstellen und dann im **./data** Ordner zu speichern. Diese Sub-Datensätze stehen also zur Verfügung.

### inspection.ipynb:
Hier habe ich bisher vor allem für die Deutschen Daten geschaut, mit was wir es eigentlich zu tun haben und was Fragen/Trends sein könnten, die wir in Gruppenarbeit unter die Lupe nehmen wollen.

### weitere Skripte:
Die weiteren beiden Skripte sind noch etwas wild, aber man kann sie ausprobieren. In fourtimeperiods.ipynb such ich nach einer sinnvollen zeitlichen Einteilung (Aggregation) und in correlations.ipynb exploriere ich die generelle Struktur der Korrelationen.
