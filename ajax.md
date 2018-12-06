# Ajax 

Ajax tarkoittaa **Asynchronous JavaScript and XML**. Ajax on tapa, jolla web sivu voi kommunikoida palvelimen kanssa käyttäen XMLHttpRequest-objektia.
Vaikka tekniikan nimessä esiintyy sana XML, voi Ajax:lla kommunikoida useassa eri tietoformaatissa esim. JSON, HTML ja pelkkä teksti.

Ajax:n avulla voi tehdä pyyntöjä palvelimella ilman, että web-sivu täytyy ladata uudelleen ja sen avulla voi ladata tietoa palvelimelta.

Nimensä mukaisesti Ajax-kutsut tapahtuvat asynkroonisesti, eli koodi ei jää odottamaan palvelimen vastausta vaan jatkaa suoritustaan (tämä on oletusasetus, jota voi myös muuttaa). Asynkroninen Ajax-kutsu ei estä web-sivun muuta toimintaa (esim. sivun latautumista tms.). Ajax-kutsuun täytyy määrittää mitä tehdään kun palvelin vastaa kutsuun. Palvelimen vastaus muuttaa Ajax-kutsun tilaa ja tämä tilan muutos otetaan kiinni, jos palvelimen vastaus halutaan käsitellä.


## Materiaaleja

https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX/Getting_Started

Mikä on XMLHttpRequest? https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest

https://www.w3schools.com/js/js_ajax_intro.asp
