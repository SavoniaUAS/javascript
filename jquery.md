# jQuery

JavaScriptin päälle on tehty paljon erilaisia kirjastoja eri käyttötarkoituksiin. jQuery on yleisesti käytetty JavaScript kirjasto, jolla DOM-elementtejä on helppo käsitellä. jQuery on suunniteltu toimivaksi kaikkien selainten ja selainversioiden kanssa. Kaiken mitä jQuery voi tehdä, voi tehdä myös ilman jQueryä (vaatinee vain paljon työtä...).


## Materiaaleja

[https://jquery.com/](https://jquery.com/)

[https://learn.jquery.com/](https://learn.jquery.com/)

[https://www.w3schools.com/jquery/](https://www.w3schools.com/jquery/)

## Esimerkki

Ladataan ensin jQuery-kirjasto.

```html
<script src="https://code.jquery.com/jquery-3.3.1.js"></script>
```

Suoritetaan koodi kun koko DOM on latautunut

```javascript
$(function() {
    // tässä lohkossa olevat koodit suoritetaan kun koko DOM on latautunut
    // etsitään elementti, jonka id = page-header ja sijoitetaan elementin arvoksi teksti Hello from jQuery!
    $('#page-header').html('Hello from jQuery!');
});

```
