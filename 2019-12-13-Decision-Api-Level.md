---
layout: post
title: Team2 API-Level
author: team2
categories: team2
---

## Definition

Wir nutzen API-Level-2, da alle Entitäten nur einen Zustand besitzen und der Mehrwert zusätzlicher Verlinkungen somit minimal ist.
Des Weiteren werden die zwei Ressourcen /demenziellerkrankter und /positionssender nicht vom Zonenealarmsystem verwaltet. Es ist somit
unwahrscheinlich, dass Verlinkungen, welche im POST, PUT zurückgegeben werden einen Nutzen generieren. Diese werden i. d. R. nur über Events
durch das Zonenalarmsystem konsumiert.
