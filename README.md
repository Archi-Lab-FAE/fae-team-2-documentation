# Domain Vision Statement - Zonenalarmsystem
[Demenziell Erkrankte Personen](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-dementiell-Erkrankter.html) möchte man weiterhin dieselbe Freiheit geben wie bisher. Je nach Grad der Erkrankung wird durch diese Freiheit eine größere Belastung für die Angehörigen und für die Mitarbeiter des Heims hervorgerufen, wenn die erkrankte Person z.B. durch das Dorf irrt und nicht mehr weiß wo sie sich gerade befindet. Um die Sicherheit der erkrankten Person weiterhin gewährleisten zu können, wird daraufhin meistens diese Freiheit eingeschränkt.
Die in diesem Rahmen erstellte Applikation soll diese Belastung reduzieren, aber die Freiheit der erkrankten Person nicht einschränken. Die Applikation soll der erkrankten Person die Möglichkeit geben sich weiterhin auch ohne Betreuung frei im Dorf bewegen und die Tagesaufgaben (z.B. zum Arzt zu gehen) selbstständig erledigen zu können. Dafür benötigt die demenziell erkrankte Person lediglich einen [Positionssender](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Positionssender.html) im Schuh. Sollte während ihres Tagesablaufs außerhalb des Heims eine Abweichung auftreten, d.h. wenn die erkrankte Person anstatt zum Arzt in Richtung der Bahngleise läuft, da sie nicht mehr weiß, wo sie sich befindet oder wo sie hin wollte, werden die Verantwortlichen informiert.

Die Domäne des Zonenalarmsystems bildet die Situation zwischen dem Verlassen des Heims und dem Zurückkehren zum Heim ab. Diese umfasst neben den eigentlichen Zonendaten auch den [Positionssender](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Positionssender.html) im Schuh des [demenziell Erkrankten](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-dementiell-Erkrankter.html) und die zugehörigen [Positions](https://fae.archi-lab.io/glossary/2019/11/05/Glossary-Position.html)- und Personendaten. Die [Zonen](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-Zone.html) selbst können dabei in zwei verschiedenen Ausführungen auftreten. Zum einen die „gewohnte Zone“, in welcher sich ein demenziell Erkrankter aufhalten kann, ohne dass ein Alarm ausgelöst wird. Die „gewohnte Zone“ umfasst Bereiche wie das Heim, Ärzte im Dorf oder sonstige geläufige Anlaufstellen der demenziell erkrankten Person sowie die Wege dorthin. Diese werden im Vorfeld mithilfe der Heimleitung definiert. Um Abweichungsfehler oder ein zu häufiges Informieren der Verantwortlichen zu vermeiden, ist bei der Erkennung eine kleine Toleranz gegeben. Zum anderen werden „ungewohnte Zonen“ abgebildet, welche Bereiche mit einem besonders hohen Verletzungsrisiko nachbilden. Eine solche „ungewohnte Zone“ könnte bspw. eine steile Felskante oder Bahngleise darstellen.

Mithilfe dieser Daten kann in regelmäßigen Abständen ermittelt werden, ob sich ein [demenziell Erkrankter](https://fae.archi-lab.io/glossary/2019/11/15/Glossary-dementiell-Erkrankter.html) in Gefahr befindet oder seine gewohnte Umgebung verlässt. Verlässt die Person eine gewohnte Zone und betritt eine ungewohnte Zone, so werden nach einer gewissen Toleranz die Verantwortlichen entsprechend ihrer Priorität informiert.


**Weitere Informationen können aus dem [Wiki](https://github.com/Archi-Lab-FAE/fae-team-2-documentation/wiki) entnommen werden.**

<!--#### Anmerkungen SB 29.11. (bitte nach Bearbeitung löschen)
* Das README sollte die "Eintrittskarte" in das Repo bieten. Hierhin gehört:
   * das Domain Vision Statement - in einer Form, dass ein **Außenstehender** versteht, worum es geht.
   * Hinweise auf Weiterlesen (Wiki)-->


<!--
#### Anmerkungen SB 15.11. (bitte nach Bearbeitung löschen)
* Dokumentation Events / Domain Model: 
    * wie mappen die Events auf die Entitäten Ihres Datenmodells?
    * wo sind die Events dokumentiert?
-->
<!--
# fae-team-2-documentation

In this repository all decisions concerning only team 2 should be documented.

## Usage
To create a new entry first create a markdown file according to the following template.

```
Filename: YYYY-MM-DD-TITLE.md
Example: 2019-09-12-Example.md
```

Attention: Each title must be unique, so the file is always found.

After you have created the file, the server needs some metadata to properly assign the entry. The metadata must be at the top of the file.

### Metadata
```
---
layout: post
title: The title // This does not have to be the same as the file name!
author: The name of the author // optional
categories: team2 // The Team Specific Category
---
```

Following the metadata comes the actual content. Once you commit and push an entry, the server is refreshed and provides the new entry.
-->
