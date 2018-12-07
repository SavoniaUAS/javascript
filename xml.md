# XML

XML **Extensible Markup Language** on merkkauskieli, jota W3C-organisaation (World Wide Web Consortium) suositus yleiseksi merkkauskieleksi.

Täytyy määrittää omat "tagit" ja niiden tarkoitus. Voidaan käyttää mm. tiedon jäsentelyyn ja välitykseen. Helposti koneluettavissa.


## Materiaaleja

[https://developer.mozilla.org/en-US/docs/XML_introduction](https://developer.mozilla.org/en-US/docs/XML_introduction)

[https://www.w3.org/TR/xml/](https://www.w3.org/TR/xml/)

[https://www.w3schools.com/xml/](https://www.w3schools.com/xml/)


## Esimerkki

```xml
<?xml version="1.0" encoding="UTF-8"?>
<catalog>
   <book id="bk101">
      <author>Gambardella, Matthew</author>
      <title>XML Developer's Guide</title>
      <genre>Computer</genre>
      <price>44.95</price>
      <publish_date>2000-10-01</publish_date>
      <description>An in-depth look at creating applications 
      with XML.</description>
   </book>
   <book id="bk102">
      <author>Ralls, Kim</author>
      <title>Midnight Rain</title>
      <genre>Fantasy</genre>
      <price>5.95</price>
      <publish_date>2000-12-16</publish_date>
      <description>A former architect battles corporate zombies, 
      an evil sorceress, and her own childhood to become queen 
      of the world.</description>
   </book>
</catalog>
```
