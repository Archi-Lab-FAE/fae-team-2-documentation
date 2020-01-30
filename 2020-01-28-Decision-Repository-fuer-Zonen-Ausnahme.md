---
layout: post
title: Team2 Repository für Zonen Ausnahme
author: alle
categories: team2
---

Die fehlgeschlagendem REST-Calls mit den [Zonen Ausnahmen](https://fae.archi-lab.io/team2/2020/01/28/Decision-Tests-von-Getter-und-Setter.html) an den Nachrichten-Services sollen in einem Repository aufgefangen werden um nach einer definierten Zeitspanne ein erneutes Senden zu ermöglichen.

Dabei wird auf ein Repository und nicht auf ein Variablen-Speicher gesetzt, damit falls unser Service z.B. neustartet, die [Zonen Ausnahmen](https://fae.archi-lab.io/team2/2020/01/28/Decision-Tests-von-Getter-und-Setter.html) nicht verloren gehen. [Zonen Ausnahmen](https://fae.archi-lab.io/team2/2020/01/28/Decision-Tests-von-Getter-und-Setter.html), unabhänig von dem Erfolg des Sendens, sollen nicht mehr in dem Retry-Zykuls berücksichtigt werden, wenn diese ein bestimmtes Alter überschritten haben.
