# Tehtävä 2

Jekyll sivuston automatisointi GitHub Actionsin avulla alkaa sillä, kun luodaan YAML-muotoinen konfiguraatiotiedosto .github/workflow/jekyll.yml. Sen ei tarvitse välttämättä olla juuri jekyll.yml, kunhan pääte on .yml tai .yaml. Tiedosto sisältää erilaisia vaiheita kuten sivuston rakentamisen ja lopuksi sen julkaiseminen. Julkaisemiseen käytetään actions-gh-pages -toimintoa. Workflow eli työnkulku käynnistyy kun tehdään muutoksia päähaaraan.


CI eli Continuous Integration tarkistaa ja yhdistää koodin muutokset jaettuun repositioon. CD eli Continuous Delivery ottaa automaattisesti sen vahvistetun koodin ja valmistelee sen julkaistavaksi. GitHub Actionsin lisäksi muita suosittuja työkaluja automaattisten työnkulkujen suorittamiseen ovat esimerkiksi Jenkins tai Azure DevOps. Konttien hallinnassa voidaan käyttää esimerkiksi Dockeria. Automaattiseen julkaisuun voidaan käyttää esimerkiksi AWS.
