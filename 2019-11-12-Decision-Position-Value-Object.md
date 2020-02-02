---
layout: post
title: Team2 Position ist kein Value Object
author: alle
categories: team2
---

**Betroffene Entität**: Position

Vorherige Überlegung:
Bei der Implementierung hat sich herausgestellt, dass die Entität [Position](https://fae.archi-lab.io/glossary/2019/11/05/Glossary-Position.html) keine Entität ist,
sondern ein zu den Entitäten [Positionssender](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Positionssender.html) und [Zone](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Zone.html) zugehöriges Value Object ist.
Grund dafür ist, dass die Position allein keinen Mehrwert liefert und immer nur in Verbindung mit der Entität [Positionssender](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Positionssender.html) oder [Zone](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Zone.html) abgerufen werden sollte.

Nachträgliche Überlegung:
Da die Art und Weise der Zonendefinition lange offen gehalten wurde um flexibel zu bleiben, war es dementsprechend unpraktisch die [Position](https://fae.archi-lab.io/glossary/2019/11/05/Glossary-Position.html) als Value Object abzubilden. Für den Fall einer konkreten und komplexen Abbildung der Zone durch sehr viele Positionen wäre dadurch ein zu großer Aufwand entstanden.


**Entscheidung**: Die Entität Position wird nicht als Value Object abgebildet.
