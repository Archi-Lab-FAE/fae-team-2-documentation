---
layout: post
title: API-First
author: alle
categories: team2
---

Für die Dokumentation der REST-Schnittstellen standen zwei verschiedene Vorgehensweisen zur Verfügung - API-Fist und Code-Fist.

- Bei API-First wird zuerst die API beschrieben und aus der Beschreibung ein Server-Stub generiert.
- Bei Code-First wird der vorhandene Quellcode passend annotiert und ausden Annotationen wird die API-Dokumentation automatisch generiert.


Wir haben uns für die API-First Variante entschieden, weil
- ein erster Entwurf der Schnittstellen im OpenApi-Format schnell geschrieben ist, welcher dann mit Anderen besprochen und unkompliziert angepasst bzw. geändert werden kann
- wir durch den automatisch generierten Code eine einheitliche Code-Basis haben (im Vergleich dazu, dass jedes Teammitglied eigenständig einen REST-Controller "von Hand" im Code erstellt)
- das Pflegen der Vielzahl an Annotationen für die API-Dukomentation unübersichtlicher ist, als ein yaml-File zu verwalten
- der API-First-Ansatz von Sven Bernhardt in einem der Gastvorträge empfohlen wurde.
