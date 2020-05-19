---
title: "Optimalisatie van natuurbeheer met behulp van machine learning"
author: "Kees van Immerzeel / Willem Molenaar"
date: "19-5-2020"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Samenvatting

Om te onderzoeken of de techniek van ‘machine learning’ bruikbaar is om het beheer in een natuurgebied te optimaliseren zijn de gegevens gebruikt van het schraallandgebied Rome, gelegen nabij Drachten (FR). Er is een model geconstrueerd dat gevoed is met abiotische gegevens die samenhangen met het voorkomen van blauwgrasland.

Het geconstrueerde model blijkt goed in staat te zijn het huidige voorkomen van blauwgrasland te verklaren. Het model laat zien dat in een geselecteerd perceel een verhoging van de grondwaterstand bij kan dragen aan de ontwikkeling van blauwgrasland. 
De techniek kan helpen om ook in andere natuurgebieden de locatie specifieke optimale groeiomstandigheden te vinden voor natuurlijke vegetaties.


## R-Markdown script
Het bestand `AnalyseBlauwgraslandRome.Rmd` bevat de scripts maarmee het vegetatievoorspellingsmodel is gemaakt. Tevens toont het script de resultaten die met het model zijn verkregen.