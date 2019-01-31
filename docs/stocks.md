#Stock methode
[https://locateit-backend.herokuapp.com/stocks](https://locateit-backend.herokuapp.com/stocks)
##header
Om een request te kunnen doen moet je een header token meegeven waarbij er een passwoord zit.
##get latest Stock
Deze methode doet een get request, waarbij deze stock object gaat vinden die is laatst toegevoegd op basis van de `timestamp`.

##add afdeling
Deze methode doet een post request, waarbij volgende waardes zijn:  
`id: Number`  
`inStock: Boolean`  
`timestamp: Number`  
