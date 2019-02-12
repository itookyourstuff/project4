#Alle methodes van de gebruikers api

[https://locateit-backend.herokuapp.com/gebruikers](https://locateit-backend.herokuapp.com/gebruikers)


##get all gebruikers
Met deze methode doe je een get request , hier krijg je een object terug met het volgende in:    
`naam: String`  
`id: Number`
`email: String`
`niveau: Number`
`passwoord: String`

##add gebruikers
Met deze methode doe je een post request, hiermee creër je een object waarbij volgende waardes in zitten:  
`id: Deze word zelf gegenereerd`  
`naam: Naam van de gebruiker`  
`niveau: Dit bepaald wat voor toegang de gebruiker krijgt `
`email: het mail address van de gebruiker `
`passwoord: het passwoord van de gebruiker`


##login
Met deze methode doe je een post request waarbij je gaat controleren of de login overeenkomt op basis van `email` en `passwoord`.
