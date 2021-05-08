Views-kansion tiedostot
#Varsinaiset sivut
##Alert.ejs
Virheilmoitusten sivu.
##index.ejs
Sovelluksen etusivu.
##keskustelu_aiheesta.ejs
Sivu yksittäisten viestiketjujen näyttämiseksi.
##kirjautuminen.ejs
Sivu käyttäjän kirjautumiseksi.
##omat_viestit.ejs
Sivu, jolla näytetään kirjautuneen käyttäjän omat viestit.
##tietoa.ejs
Tietoa sivustosta -sivu.
##uusi_viesti.ejs
Sivu viestien luomista ja muokkaamista varten.

#Sivuja täydentävät tiedostot
##head.ejs
Jokaisen sivun HEAD-osio, joka sisältää
- Otsikkomääritteen
- kutsuja
  - Google Analytics
  - styles.css
  - Bootstrap
  - Google fontteihin, joita sivustolla käytetään
##hallinta.ejs
Tiedoston avulla hallitaan sovelluksen käyttöliittymään.
##Error.ejs
Tiedosto, joka jäsentää saadun virheilmoituksen. **Ei taida olla käytössä tällä hetkellä**.
##header.ejs
Käyttäjälle näkyvän sivun otsikkoalue. Sisältää vain sivuston otsikkobannerin.
##footer.ejs
Jokaisen sivun alaosa. Sisältää
- otsikon mobiilikäyttöliittymää varten
- Bootstrap-koodin
- Linkin NPM/Popper:iin. Mitä tämä tekee?

#Käytetäänkö näitä tiedostoja?
##ggl_analytics_body.ejs
Koodi Google Tag Managerin kutsumiseksi. **Tätä ei taideta enää käyttää**, vaan käytössä onkin pelkästään Google Analytics.
##ohjeet.ejs
Tarkoitus oli, että tiedosto sisältää sivuston käyttöohjeet, jotta samaa tietoa on mahdollista hyödyntää sekä *tietoa.ejs* että *rekisteroityminen.ejs*-sivulla. Jälkimmäisessä tapauksessa idea oli, että ohjeet saa näkyviin erityisestä painikkeesta pop-up -ikkunaksi.
##register.ejs
Tämä tiedosto saattaa olla perua monikielisen sovellusversion ensimmäisestä toteutuksen aloittamisesta. Todennäköisesti tätä ei enää käytetä mihinkään.