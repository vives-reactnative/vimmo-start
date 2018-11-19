# vimmo-start

Deze repository bevat de nodige resources om van start te gaan met de opdracht VIMMO

## Inhoud

- `/assets`
  - `home.jpg`: statische afbeelding op het zoekscherm
- `/components`
  - `Warning.js`: het Warning component. Wordt getoond als oranje balk als tekst wordt meegegeven als `child` van dit component. Retourneert `null` als niets wordt meegegeven
- `/styles`
  - `theme.js`: Bevat enkele constante lay-out waardes die doorheen de volledige applicatie kunnen gebruikt worden
- `/utils`
  - `NestoriaAPI.js`: bevat een functie `fetch(placeName)` die achterliggende de NestoriaAPI zal aanroepen met behulp van `axois`. Retourneert een Promise
