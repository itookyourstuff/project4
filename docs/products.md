#Product methode

##Product model

##Get all products
Deze methode doet een get request, deze zal alle product objecten ophalen. Dit object bevat volgende waardes:  
`id: Number`  
`naam: String`  
`beschrijving: String`  
`afdeling: String`  
`afbeelding: String`  
`prijs: Number`  

##Get products by id
Deze methode doet een get request, deze zal alle waardes ophalen van een object met de meegegeven id.

##Get products by afdeling
Deze methode doet een get request, hiermee zal het elk object ophalen die voldoet aan de meegegeven afdeling.

##Add products
Deze methode doet een post request, dit creër een object waarbij volgende waardes in zitten.  
`id:  Deze word zelf gegenereerd  `  
`naam: Naam van het product`  
`beschrijving: Beschrijving van het product`  
`afdeling: Een afdeling(genre) van het product`  
`prijs: Hoeveel het product kost`   
  
##Delete product by id
Deze methode doet een delete request, dit zal het object verwijderen dat gelinkt is aan de meegegeven `id`.  

##Delete all products

##Update Products
