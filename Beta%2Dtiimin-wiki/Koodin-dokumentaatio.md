Näiltä sivuilta löytyy listaus käytetyistä tiedostoista sekä tiedostojen merkityksen lyhyet kuvaukset
#kansiot
##\_test_
Jest-testit.
##bin
Sisältää www-tiedoston. jossa on määritelty kutsu app-tiedostoon sekä käytettävät protokolla ja portti.
##languages
Kielitiedostot, joiden avulla kansainvälisyys on toteutettu
##public
Kuvat ja CSS-tiedostot
##routes
Reittitiedostot, jotka käsittelevät tarkemmin käyttäjän kutsumia URL-osoitteita.
##views
Sivujen toteuttamiseen liittyvät tiedostot
#Tiedostot juuressa

## Sovelluksen toimintaan liittyvät tiedostot
###app.js
Sovelluksen päätiedosto. Määrittää esimerkiksi reitit (routes), joihin käyttäjän kutsumat URL-osoitteet ohjataan.
###dbOperations.js
Tietokanta
###package-lock.json
JSON-ohjaustiedosto, jota tarvitaan ilmeisesti, kun toteutettava sovellus on tarkoitus lukita ja julkaista.
###package.json
JSON-ohjaustiedosto.

## Muut sovellukseen liittyvät tiedostot
###.gitignore
Määrittää, mitä tiedostoja ei tule siirtää git-operaation aikana.
###LICENSE
GNU-lisenssi
###README.md
LUEMINUT-tiedosto, jossa on toistaiseksi nimetty vain *MyMessenger* mutta ei mitään sisältöä.

##Asetustiedostot Azure-putkia varten
###azure-pipelines-1.yml
Asetustiedosto *ohjelmistotuotanto-beta*-putkea varten. En ole varma tarvitaanko tätä *Multilan*-haarassa.
###azure-pipelines.yml
Asetustiedosto *ohtu-beta*-putkea varten. En ole varma tarvitaanko tätä *Multilan*-haarassa.
###Beta_Multilanguage-pipeline.yml
Monikielisyyden toteuttavan *Multilang*-haaran asetustiedosto Beta-putkelle, joka on nykyisellään käytössä, kun sovellus ajetaan App Serviceen.