---
{"dg-publish":true,"permalink":"/hosting-portland-guests/","dg-note-properties":{}}
---

## Views

- Pittock Mansion
- Mt Tabor
- East/west waterfront
- Vista house (windy)
- St John’s Bridge (iconic)
- Tilikum Bridge (pedestrian/transit only)
- Aerial Tram (SW Downtown)
## Activities

### Outdoor

- Japanese Gardens
- Rose Garden
- Adelman Peonies - Salem, largest Peony garden in the world
- Kenilworth community pool
- Zoo
## Indoor

- Art Museum
- [[Food Spots/Mox Boarding house\|Mox Boarding House]]
- Retro Games Bar
- [[Food Spots/Ground Kontrol\|Ground Kontrol]]
- OMSI
- Wunderland / Quarterworld arcades
- Powell’s Books

## Shopping

- Saturday Market downtown

## Food

A selection of food spots that we've been to or know are excellent in the area.

For groceries, Trader Joe's is just down the street from us, and New Seasons and Safeway are a five minute drive away in the Woodstock neighborhood.

> [!NOTE] Diet Tags
> Vegan & Gluten Free tags imply that they are friendly to these diets, not necessarily that they are exclusive to people looking for those dietary paths.



```base
views:
  - type: table
    name: Table
    filters:
      and:
        - "!cuisine.isEmpty()"
    order:
      - file.name
      - cuisine
      - regions
      - tags
      - source
    markers: bullet
    indentProperties: false
    columnSize:
      note.tags: 379

```

