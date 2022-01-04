# coalitieplannentracker

Website om de voortgang van coalitieplannen bij te houden. Onder elk punt kunnen updates worden toegevoegd, zodat er een tijdlijn ontstaat die inzichtelijk maakt hoe het plan naar beleid is vormgegeven.

[Klik hier om naar de website te gaan!](https://odinjorna.github.io/coalitieplannentracker/)

# Toevoegen van updates

Heb je een artikel/rapport/update over een coalitieplan die je wilt toevoegen? Dat kan! Elke update is een file onder de folder 'tiddlers/Updates'. Maak een PR aan voor een nieuwe file met de volgende fields:

```
title: "vul hier de titel in van het artikel/rapport/etc."
tags: Update // elke update heeft de tag update, hoeft niet aangepast te worden
description: "een korte beschrijving van het artikel/rapport/etc dat gebruikt voor voor de preview pane" // wordt ingevuld door linkPreview 
image: "een link naar een foto op de pagina waar je naar linkt" // wordt ingevuld door linkPreview
url: "de url van je link" 
source: "naam van de organisatie die het document heeft gemaakt waar je naar linkt. Bijvoorbeeld nieuwsartikel van nos.nl = NOS"
date: "datum van het plaatsen van het artikel in het formaat: 'jaar maand dag' in getallen, bijvoorbeeld: 18 december 2021 = 20211218"
parent: "Volledige naam van het coalitieplan waar je link bij hoort"
```

Gebruik de [update toevoeger hulp website](https://odinjorna.github.io/update-toevoeger/) om de data te genereren, zodat het gemakkelijker wordt om een PR aan te maken.

# Gemaakt met TiddlyWiki

De coalitietracker is gemaakt met behulp van open source software [TiddlyWiki.](tiddlywiki.com)
