# Tietosuojakäytäntö

*30. kesäkuuta 2026*

Lucky Decisions ("Sovellus") on AlexJKL:n kehittämä. Tämä tietosuojakäytäntö kuvaa, miten tietojasi kerätään, käytetään ja jaetaan, kun käytät Sovellusta.

## Keräämämme tiedot

Sovellus tallentaa kaiken käyttäjän luoman sisällön (pyörät, sektorit, pyörityslokit, asetukset) paikallisesti laitteellesi.

Premium-tilaajat voivat vapaaehtoisesti ottaa käyttöön **Tietojen synkronointi** -ominaisuuden — pilvivarmuuskopiointiominaisuuden. Tätä ominaisuutta käytettäessä:

- Kirjaudut sisään Googlella tai Applella
- Saamme sähköpostiosoitteesi ja yksilöllisen tilitunnisteen
- Sovelluksesi tiedot (pyörät, asetukset, suosikit) tallennetaan Firebase Firestoreen (Googlen pilvitallennus)

Tietojen synkronoinnin käyttö on täysin vapaaehtoista. Jos et kirjaudu sisään, henkilötietoja ei siirretä meille tai kolmansille osapuolille.

Sovelluksessa käytetään seuraavia kolmannen osapuolen palveluja, jotka voivat kerätä tiettyjä tietoja:

- **Google AdMob** — Kerää mainostunnisteen, laitetietoja, tietoa mainosvuorovaikutuksista (klikkaukset, näytöt, näkemäsi mainokset) ja SDK-diagnostiikkaa (kaatumis- ja suorituskykytiedot) mainosten näyttämistä ja mittaamista varten. iOS:ssä personoidut mainokset edellyttävät suostumustasi App Tracking Transparency -toiminnon kautta. [Googlen tietosuojakäytäntö](https://policies.google.com/privacy)
- **Yandex Mobile Ads** — Näyttää mainoksia ja kerää mainostunnisteen, laitetietoja, tietoa mainosvuorovaikutuksista ja SDK-diagnostiikkaa. [Yandexin tietosuojakäytäntö](https://yandex.com/legal/confidential/)
- **Meta Audience Network** — Näyttää mainoksia ja kerää mainostunnisteen, laitetietoja, tietoa mainosvuorovaikutuksista ja SDK-diagnostiikkaa. [Metan tietosuojakäytäntö](https://www.facebook.com/privacy/explanation)
- **Unity Ads** — Näyttää mainoksia ja kerää mainostunnisteen, laitetietoja, tietoa mainosvuorovaikutuksista sekä SDK-diagnostiikkaa. [Unityn tietosuojakäytäntö](https://unity.com/legal/privacy-policy)
- **RevenueCat** — Käsittelee tilausostot, tallentaa ostohistoriasi ja antaa anonyymin käyttäjätunnuksen. [RevenueCatin tietosuojakäytäntö](https://www.revenuecat.com/privacy)
- **Firebase (Google)** — Crashlytics kerää kaatumis- ja virheraportteja: pinojäljet, käyttöjärjestelmäversion, laitemallin ja asennustunnisteen. Firebase Analytics kerää anonyymejä sovelluksen käyttötapahtumia ja laitetunnisteen. Firebase Authentication -palvelua käytetään Google- ja Apple-kirjautumiseen, kun käytät Tietojen synkronointia. Firebase Firestore tallentaa sovelluksen tietojen varmuuskopiot Premium-tilaajille, jotka ovat ottaneet synkronoinnin käyttöön. [Googlen tietosuojakäytäntö](https://policies.google.com/privacy)

## Tietojen tallennus

Oletusarvoisesti kaikki sovelluksen tiedot tallennetaan paikallisesti laitteellesi. Jos otat Tietojen synkronoinnin käyttöön (vain Premium), sovelluksesi tiedot tallennetaan myös Firebase Firestoreen – Googlen pilvipalveluun, joka sijaitsee Euroopassa (alue eur3).

## Tilin poistaminen

Voit poistaa tilisi ja kaikki siihen liittyvät tiedot milloin tahansa:

- **Sovelluksessa:** Asetukset → Tietojen synkronointi → Poista tili
- **Verkossa:** [alexjkldev.github.io/luckydecisions/delete-account](https://alexjkldev.github.io/luckydecisions/delete-account)

Tilin poistaminen poistaa pysyvästi kaikki pilvipalvelun tietosi ja Firebase Authentication -tietueesi. Tilin poistaminen ei automaattisesti peruuta Premium-tilaustasi.

## Lasten yksityisyys

Sovellus ei tietoisesti kerää lasten henkilötietoja. Yllä mainituilla kolmannen osapuolen palveluilla voi olla omat ikärajoituksensa.

## Muutokset tähän käytäntöön

Voimme päivittää tätä tietosuojakäytäntöä ajoittain. Muutokset julkaistaan Sovelluksessa tai tällä sivulla.

## Yhteystiedot

Jos sinulla on kysyttävää tästä tietosuojakäytännöstä tai haluat ottaa yhteyttä kehittäjään, voit ottaa meihin yhteyttä Sovelluksen kautta tai App Storen tai Google Play Storen sovelluslistauksen kautta. Kun otat meihin yhteyttä sähköpostitse, saamme sähköpostiosoitteesi, viestisi sisällön ja mahdolliset liitteet. Käytämme näitä tietoja yksinomaan kyselyysi vastaamiseen ja Sovelluksen parantamiseen. Emme jaa niitä kolmansille osapuolille.
