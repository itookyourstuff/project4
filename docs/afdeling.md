# Afdeling methode

Alle methodes van de afdeling api

[https://locateit-backend.herokuapp.com/afdelingen](https://locateit-backend.herokuapp.com/afdelingen)
## header token
Om een request te kunnen doen moet je een header token meegeven waarbij er een passwoord zit.
## Get all afdeling
Met deze methode doe je een get request , hier krijg je een object terug met het volgende in:    
`naam: String`  
`id: Number`


## Afdeling toevoegen methode
Met deze methode doe je post request, hiermee creër je een object waarbij volgende waardes in zitten:  
`id: Deze word zelf gegenereerd`  
`naam: Naam van de afdeling`    

## Afdelingen Delete methode
Met deze methode ga je alle afdeling verwijderen.

## Afdeling Delete by id methode
Met deze methode ga je een delete request doen om een bepaalde afdeling te verwijderen op basis van een `id`.  
