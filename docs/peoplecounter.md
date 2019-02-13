#Alle methodes van de gebruikers api

[https://locateit-backend.herokuapp.com/peoplecounter](https://locateit-backend.herokuapp.com/peoplecounter)

##header
Om een request te kunnen doen moet je een header token meegeven waarbij er een passwoord zit.
  
##PeopleCounter toevoegen
Deze methode doet een post request, waarbij volgende waardes zijn:  
`id: Number`  
`totalUp: Boolean`  
`totalDown: Number`  
`timestamp: Number`

##Laatste nieuwe PeopleCounter ophalen.
Deze methode doet een get request, waarbij het nieuwste object opgehaald word op basis van `timestamp`.
