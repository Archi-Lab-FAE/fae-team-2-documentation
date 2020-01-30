---
layout: post
title: Benennung von IDs
author: alle
categories: team2
---

**Wie sollen die Entity IDs benannt werden?**

Nach Möglichkeit sollen alle IDs in Entitäten sprechend benannt werden.

Beispiel für Zone:
- DO: zoneId
- DONT: id

Dies ist nur für Entitäten möglich, welche selbst verwaltet werden, da es bei
einer externen Verwaltung der durch Swagger generierte Code bei jeder Änderung
angepasst werden müsste.
