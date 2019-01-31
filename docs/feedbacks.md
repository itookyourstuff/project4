#Feedback methode
[https://locateit-backend.herokuapp.com/feedback](https://locateit-backend.herokuapp.com/feedback)
##header
Om een request te kunnen doen moet je een header token meegeven waarbij er een passwoord zit.

##Feedback get all
Met deze methode doe je een get request, hiermee krijg je volgende waarden terug:

`id: Number`  
`score: Number`  
`beschrijving: String`  
`timestamp: Number`  

##Feedback get by id
Deze methode gaat get request doen en een feedback object terugsturen op basis van het een `id`.  


##Add Feedback
Met deze methode doe je post request, hiermee creër je een object waarbij volgende waardes kan ingestopt worden:  
`id: Deze word zelf gegenereerd`  
`score: hoeveel score de app krijgt op 5`  
`beschrijving: Beschrijving`  
`timestamp: word zelf toegevoegd(tijd van het aanmaken van een review)`  

##Delete feedback by id
Bij deze methode ga je een delete request sturen, waarbij er een feedback object zal verwijerd worden op basis van het `id`:


##Delete all Feedback
Bij deze methode ga je een delete request sturen, waarbij alle objecten in feedback verwijderd worden.

##Update feedback
Deze methode gaat een patch request sturen, hiermee kan je de `beschrijving` of `score` kan aanpassen voor de feedback.
