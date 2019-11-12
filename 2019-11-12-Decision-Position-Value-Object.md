---
layout: post
title: Team2 Position ist Value Object
author: alle
categories: team2
---

**Betroffene Entität**: Position

Bei der Implementierung hat sich herausgestellt, dass die Entität Position keine Entität ist,
sondern ein zu den Entitäten GPS-Sender und Zone zugehöriges Value Object ist.
Grund dafür ist, dass die Position allein keinen Mehrwert liefert und immer nur in Verbindung mit der Entität GPS-Sender oder Zone abgerufen werden sollte.


**Entscheidung**: Die Entität Position wird von nun an als Value Object abgebildet.
