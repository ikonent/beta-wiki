Tehtävänä on laatia yleinen MyMessenger-viestittelypalvelu osoitteeseen **https://smartict-beta.azurewebsites.net**, jossa korvataan oman tiimin tunnuksella pienillä kirjaimilla kirjoitettuna, esimerkiksi https://smartict-alpha.azurewebsites.net.

Sovelluksen tulee olla ylläpidettävissä ja ensimmäisen version julkaisun jälkeen tiimi **ylläpitää** ja **operoi** palvelua ja **huomioi** työskentelyssään palveluun kohdistuvat
- strategiset kehittämistarpeet ja
- käyttäjien antaman palautteen ja
- vikailmoitukset.

Sovelluksen vaatimusmäärittely noudattaa tammi-maaliskuussa toteutetun **web- ja mobiilisovelluskehitysopintojakson vaatimusmäärittelyä**. Lopullisen ohjelmiston tulee toimia niin, että
- viestejä voi vain lukea ilman kirjautumista.
- Viestien lähettäminen, muokkaaminen ja poistaminen edellyttävät rekisteröityneen käyttäjän kirjautumisen.
- Käyttäjätunnus ja salattu salasana tallennetaan users -tauluun rekisteröitymisen yhteydessä (Tämä tarkoittaa sitä, että rekisteröityminen ja kirjautuminen on toteutettava erikseen).
- Käyttäjätunnus on yksilöllinen(kahta samaa käyttäjätunnusta ei voi olla).

Toteutettavat käyttäjätarinat:
- Käyttäjä rekisteröityy viestisovelluksen käyttäjäksi
- Käyttäjän kirjautuu viestisovellukseen
- Onnistuneesti kirjautunut käyttäjä voi:
- lukea kaikkien viestejä
- lähettää viestejä (lisätä uuden viestin messages -tauluun)
- poistaa itse lähettämänsä viestin
- voi muokata lähettämäänsä viestiä
- Käyttäjä voi kirjautua ulos viestisovelluksesta

Lisäksi operatiivinen johto ja markkinointiosasto tarvitsee käyttöönsä mahdollisimman kattavan palvelun käyttöä koskevan mittaroinnin, jonka ratkaisussa voidaan hyödyntää Google Analyticsin palveluja.

Johtoryhmä on myös kiinnostunut palvelun saattamiseksi mobiilisovelluksella käytettäväksi. Sovelluksen ensimmäinen versio voidaan laatia suomenkieliseksi tai englanninkieliseksi, mutta johtoryhmä on kiinnostunut myös sovelluksen kansainvälistämisestä seuraavan vuosineljänneksen aikana.