---
layout: post
title: Team2 Tests von Getter und Setter
author: alle
categories: team2
---

Wie wird das Testen von DTOs und deren Getter und Setter gehandhabt?

Getter und Setter, die keine Logik beinhalten, also nur ein stupides get oder set machen, werden **nicht** explizit durch Tests abgedeckt. Das hat den Grund, da eine 100% Code-Coverage nicht das Ziel einer Code-Qualitsanalyse sein sollte. Es sollen nur Methoden und Code-Stellen durch Tests abgedeck werden, wenn diese auch relevant für die korrekte Ausführung des Services sind und bspw. Business-Logik beinhalten und nicht einfach nur Variablen-Zuweisung durchführen.

Unnötige Getter- und Setter-Tests bringen nicht nur keinen Mehrwert, sondern verschlechtern eher die Übersicht in den Test-Klassen.
