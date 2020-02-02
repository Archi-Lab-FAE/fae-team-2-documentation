---
layout: post
title: Package Struktur
author: alle
categories: team2
---

Obwohl der [APi-First-Ansatz](https://fae.archi-lab.io/team2/2020/02/02/Decision-API-First.html) bereits eine Package Struktur vorgibt, haben wir uns (teilweise) gegen diese Entscheiden bzw. Abgeändert und Angepasst.

Die automatisch generierte Struktur sieht wie folgt aus:
- api (Alle REST-Controller-interfaces und deren Implementierungen)
- configuration (Konfigurationen)
- model (Modell-Klassen für die Endpunkte)

Diese Struktur ist für uns unbrauchbar, da wir noch zusätzlich Kafka-Event-Consumer- und Producer-Klassen sowie Entity-Klassen unterbringen müssen und diese immer logisch zusammengehörigen Klassen in einem Package haben wollen.

Deswegen haben wir für jede Entity ein Package erstellt, in welches alle dazugehörigen Klassen gepackt werden. Also z.B. ein Package "zone", welches die REST-Controller, Repository, Kafka-Events, DTO- und Modell-Klassen für die Zone beinhaltet. Dabei werden alle Kafka-Spezifischen Klassen in einem extra "event"-Subpackage abgelegt.
