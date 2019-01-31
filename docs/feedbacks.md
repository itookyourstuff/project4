#Feedback methode

##Feedback model

##Feedback get all
Met deze methode doe je een get request, hiermee krijg je volgende waarden terug:

`id: Number`  
`score: Number`  
`beschrijving: String`  
`timestamp: Number`

##Feedback get by id
Deze methode gaat get request doen en een feedback object terugsturen op basis van het een id
`id: Number`

##Add Feedback
Met deze methode doe je post request, hiermee creër je een object die het volgende zal nodig hebben:  
`score: Number`  
`beschrijving: String`  

Deze methode zal zelf het volgende aanmaken:  
`id: Number`  
`timestamp: Number`  

##Delete feedback by id
Bij deze methode ga je een delete request sturen, waarbij er een feedback object zal verwijerd wprden op basis van het volgende:  
`id: Number`

##Delete all Feedback
Bij deze methode ga je een delete request sturen, waarbij alle objecten in feedback verwijderd worden.

##Update feedback
Deze methode gaat ene patch request sturen, hiermee kan je de beschrijving of score kan aanpassen voor de feedback.
