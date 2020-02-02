---
layout: post
title: Nutzung von DTOs
author: alle
categories: team2
---

Wir haben uns Entschieden, eine Trennung von Enities und Data Transfer Objects (DTO) vorzunehmen. Das hat den Grund, dass wir auf den [API-First-Ansatz](https://fae.archi-lab.io/team2/2020/02/02/Decision-API-First.html) bei der Erstellung unserer Code-Basis gesetzt haben und somit automatisch generierte Transfer-Klassen erhalten haben. Wir haben uns dagegen Entscheiden, diese automatisch erstellen Klassen noch um die Entity-Annotationen zu erweitern, da dadurch ein einfaches Ersetzen dieser Klassen bei einer API-Änderung nicht mehr möglich gewesen wäre.

Für die Konvertierung von Entity- zu DTO-Klasse werden in jeder Entity-Klasse "convert"-Methoden implementiert.
Außerdem werden die DTO-Klassen mit "DTO" als Suffiz benannt, um diese im Code identifizieren und unterscheiden zu können. 
