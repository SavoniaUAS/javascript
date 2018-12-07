# JSON

Json **JavaScript Object Notation** on kevyt (lightweight) tiedonvälitysformaatti, jota ihmisten on helppo lukea ja kirjoittaa sekä koneiden helppo parsia (parse) ja luoda (generate).

On ohjelmointikieliriippumaton. Perustuu kahteen rakenteeseen:

* nimi/arvo -parien kokoelma
* järjestetty arvolista

Käytetään tiedon välitykseen ja tallentamiseen. 


## Materiaaleja

[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)

[https://json.org/](https://json.org/)

[https://www.w3schools.com/js/js_json_intro.asp](https://www.w3schools.com/js/js_json_intro.asp)


## Esimerkki

Yksinkertainen json-objekti.
```json
{
    "avain": "merkkijonoarvo",
    "laskuri": 4,
    "taulukko": [
        "ensimmäinen arvo",
        "toinen arvo"
    ]
}
```

Json-objekti voi sisältää myös toisia json-objekteja ja taulukon toisia objekteja
```json
{
    "info": "tämä on esimerkki",
    "data": {
        "id": 2,
        "name": "eka data"
    },
    "taulukollinenmuutatietoa": [
        {
            "sensor": "temperature",
            "value": -2.5
        },
        {
            "sensor": "humidity",
            "value": 45
        }
    ]
}
```
