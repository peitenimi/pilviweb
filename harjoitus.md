# Harjoitustyö

[Linkki sivustolle](https://peitenimi.github.io/pilviweb/harjoitus/)

## Kuvaus

Sivustolla voi lisätä omia tehtäviä ja tieto, mitä sinne on tuotu, on esimerkki tehtävälistasta. Käytin siihen ulkoista REST-rajapintaa DummyJSON -sivulta. Tuotu tieto ei ehkä ole niin hyödyllistä, mutta ainakin itse toiminto on.

Sivulle pystyy lisämään omia tehtäviä vain jos on kirjautunut sisään. Autentikointi on toteutettu Firebase Authentication -palvelun avulla ja tehtävät tallentuvat Firestore tietokantaan. Sivustolta löytyy myös mittari, jolla pystyy seuraamaan tehtävien edistymistä.

## Responsiivisuus

Testasin selaimen responsiivisuutta kehittäjätyökaluilla sekä omalla puhelimella.

Sivusto skaalautuu eri näyttöleveyksille niin, että sisältö pysyy luettavana ja
toiminnot ovat helposti käytettävissä myös pienemmillä näytöillä. Navigaatio,
lomakkeet ja painikkeet mukautuvat näytön leveyden mukaan, eikä sisältöä mene
päällekkäin tai ruudun ulkopuolelle.

## Toimivuus eri selaimilla

Testasin sivua Chromella ja Edgellä eikä mitään ongelmaa. Mobiilitestauksessa käytin Safaria ja Chromea. Safarissa oli pieniä eroja, mutta ei mitään käyttöä haittaavaa eli enemmän visuaalisesti epämiellyttävä yksityiskohta.

## Latautumisaika

Mobiilissa latautuminen oli pikkuisen heikompi kuin desktopilla.

![Mobiili](mobiili.png)


![Desktop](tietokone.png)



