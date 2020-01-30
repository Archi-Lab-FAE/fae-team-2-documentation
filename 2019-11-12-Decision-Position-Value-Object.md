---
layout: post
title: Team2 Position ist kein Value Object
author: alle
categories: team2
---

**Betroffene Entität**: Position

Vorherige Überlegung:
Bei der Implementierung hat sich herausgestellt, dass die Entität Position keine Entität ist,
sondern ein zu den Entitäten GPS-Sender und Zone zugehöriges Value Object ist.
Grund dafür ist, dass die Position allein keinen Mehrwert liefert und immer nur in Verbindung mit der Entität GPS-Sender oder Zone abgerufen werden sollte.

Nachträgliche Überlegung:
Da die Art und Weise der Zonendefinition lange offen gehalten wurde um flexibel zu bleiben, war es dementsprechend unpraktisch die Position als Value Object abzubilden. Für den Fall einer konkreten und komplexen Abbildung der Zone durch sehr viele Positionen wäre dadurch ein zu großer Aufwand entstanden.


**Entscheidung**: Die Entität Position wird nicht als Value Object abgebildet.
