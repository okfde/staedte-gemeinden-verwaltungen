# Ständte, Gemeinden, Verwaltungen

Daten zu Stadt- und Gemeindeverwaltungen im JSON-Format:

```js
[
  {
  "name": "München",
  "landkreis": "Kreisfreie Stadt", // nur Bayern
  "adresse": "80313 München", // nur Bayern
  "telefon": "+49 (0)89 233-00", // nur Bayern
  "telefax": "+49 (0)89 233-26458", // nur Bayern
  "email": "rathaus@muenchen.de",
  "website": "http://www.muenchen.de/dienstleistungsfinder/muenchen/",
  "long": "11.5755",
  "lat": "48.137194444",
  "item": "Q1726", // Wikidata Item
  "typ": "Stadt in Deutschland"
  }, ...  
]
```

Aktuell nur Daten zu Bayern und Sachsen-Anhalt. PRs welcome!

## Quellen

- Bayern: [freistaat.bayern](https://freistaat.bayern/dokumente/behoerde/73886855438/alle) und [Wikidata](https://wikidata.org)
- Sachsen Anhalt: CSV Datei im Slack 🤷
