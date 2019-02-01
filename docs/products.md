#Product methode
[https://locateit-backend.herokuapp.com/products](https://locateit-backend.herokuapp.com/products)

#header
Om een request te kunnen doen moet je een header token meegeven waarbij er een passwoord zit.
##Get all products
Deze methode doet een get request, deze zal alle product objecten ophalen. Dit object bevat volgende waardes:  
`id: Number`  
`naam: String`  
`beschrijving: String`  
`afdeling: String`  
`afbeelding: String`  
`prijs: Number`  

##Get products by id
Deze methode doet een get request, deze zal alle waardes ophalen van een object met de meegegeven `id`.

##Get products by afdeling
Deze methode doet een get request, hiermee zal het elk object ophalen die voldoet aan de meegegeven `afdeling`.

##Add products
Deze methode doet een post request, dit creërt een object waarbij volgende waardes in zitten:   
`id:  Deze word zelf gegenereerd  `  
`naam: Naam van het product`  
`beschrijving: Beschrijving van het product`  
`afdeling: Een afdeling(genre) van het product`  
`prijs: Hoeveel het product kost`   

##Delete product by id
Deze methode doet een delete request, dit zal het object verwijderen dat gelinkt is aan het meegegeven `id`.  

##Delete all products
Bij deze methode doe je een delete request, waarbij alle product objecten verwijderd worden.

##Update Products
Deze methode doet een patch request, hiermee kan de `naam`, `beschrijving`, `afdeling` of `prijs`  aangepast worden.
