---
title: "Blog erstellen. Aber wie?"
date: 2019-11-01
draft: false
tags: ["Blog"]
img: ""
src: ""
description: "In diesem Beitrag erfährt ihr, wie ich meinen Blog mithilfe von Hugo und Github Pages gestartet habe."
---

Nach dem Besuch des Leopoldsmuseums ist ja einige Zeit vergangen. Was habe ich bis dahin gemacht? Keine Museen besucht? Ja, aber dafür hart gearbeitet. Der Blog wurde erstellt und schließlich ins World Wide Web gestellt. Wie habe ich das gemacht? Das erfährst du in diesem Beitrag. Ein Blick hinter die Kulissen sozusagen. <!--more-->

## Allgemein

Zu Beginn war natürlich Recherche angebracht. Das erste Mal sollte doch glücken. Die Suchergebnisse waren jedoch ernüchternd. In Blogs wurde geraten, auf Blogplattformen zu vertrauen. Die sind erprobt, einfach, aber spaßbefreit. Vermutlich sind deren Namen bekannt: Wordpress, Blogger, Tumblr, Ghost. Aber so was wollte ich nicht, ich wollte »meinen« Blog, nicht einen Blog von Wordpress. Ich wollte mehr Gestaltungsfreiheit, Offenheit, Unabhängigkeit, Wissen was dahinter ist. So tauchte ich tiefer ins Web, lernte mehr.

Domain Name. Ein Blog braucht eine eigene Adresse, klar. Hosting. Irgendjemand muss meine Texte lagern. Beides kostet. Da kommt die erste Möglichkeit billiger. Geiz. Schließlich, auf der Suche nach einem günstigen Anbieter, fand ich ein unschlagbares Angebot. Gratis, aber nur bei Static Sites. Hä, OK. Aber was ist das? Ein paar Duckduckgo-Suchen und ich hatte die Lösung.

## Static Site Generator

Static Sites werden vorab geschrieben und bei Abfrage versendet. Sie bestehen praktisch nur aus einer HTML-Datei; können aber auch eine CSS-Datei für die Gestaltung der Website und eine JavaScript-Datei für die Ausführung von Befehlen enthalten. Deswegen sind sie ausgesprochen leicht und schnell. Das Grundgerüst meines Blogs besteht lediglich aus einigen HTML-Dateien und einer CSS-Datei und benötigt deshalb nur 27kB. Auf meiner [GitHub-Seite](https://github.com/museedepot/museedepotsource) kannst du alle Dateien betrachten.

Demgegenüber stehen Dynamic Sites. Bei jeder Abfrage wird eine HTML-Datei nach einem festgelegten Muster neu generiert und dann versendet.

So, nachdem ich mich für eine statische Seite entschieden hatte, suchte ich nach einer einfachen Möglichkeit eine solche Seite einzurichten. Dabei helfen sogenannte Static Site Generators. Sie erstellen das Grundgerüst und bieten die Möglichkeit durch vorgefertigte Themen zügig eine Website aufzubauen.

Ich entschied mich für den Static Site Generator [Hugo](https://gohugo.io/) – ein toller Name, der mich an den zauberhaften Film [Hugo Cabret](https://www.youtube.com/watch?v=Hv3obL9HqyY) erinnerte. Hugo versprach mir besonders schnell und eine Gaudi beim Bauen von Webseiten zu sein. Gut, hört sich toll an. Ach, wie einfach Werbung mich beeinflusst.

Ohne Schwierigkeiten folgte ich der Anleitung und entschied mich für das Thema, [Kiera](https://github.com/avianto/hugo-kiera) – ein besonders minimalistisches ohne viel Tamtam. Somit wäre der Webseitenbau beendet gewesen, wäre da nicht ICH. Denn ich wollte etwas Eigenes erschaffen; war unzufrieden mit Kleinigkeiten.

## Probieren, Formen und Bauen

Auch wenn meine Ausführungen ein anderes Bild zeichnen, so war ich bis vor Kurzem noch ein einfältiger Laie, der keine Ahnung von CSS und HTML hatte. Somit musste ich lernen. Versuch und Irrtum – meine Methode. 

Als erstes störte mich die Schrift. Ich testete mich durch, wie bei einer Weinverkostung. Hier die Roboto, eine Sans-Serif mit feinen geometrischen Formen und freundlichen offenen Kurven; da die Lora, eine Serif mit Einflüssen aus Kalligrafie und musischen Gesamtbild; dort die Bitter, eine Slab Serif mit robustem Design in humanistischer Tradition. Und welche mundet ihnen am besten? Hhmm.

Leicht benebelt entschied ich mich dann für folgende Schriftarten: Cinzel Decorative, der Blogtitel; Josefin Sans, Überschriften, und Alegreya, Text. Puh.

Dann veränderte ich die Farben. Nur Schwarz-Weiß wird doch langweilig; Farbe zur Erheiterung. Besonders störte mich der Übergang von Seite zu Seite – er fehlte. Das Script [swup](https://swup.js.org/) erleichterte mir die gewünschte Umsetzung. Ausblenden und Einblenden – ein Traum. Danach pfuschte ich noch an ein paar einfachen Animationen herum, fügte ein Seitenregister für die Hauptseite hinzu, veränderte Schriftgrößen, platzierte Bilder, wählte für die Icons [Fork Awesome](https://forkaweso.me/Fork-Awesome/) und variierte noch einiges Kleinzeugs mehr.

Schlussendlich war ich zufrieden und wie ich meine, ist mir eine besonders ästhetische und elegante Seite gelungen. Für das erste Mal sicher in Ordnung.

Da die Seite nun fertiggestellt war, konnte ich sie endlich auf GitHub hochladen. GitHub bietet die Möglichkeit über GitHub Pages die Webseite gleichzeitig zu hosten. Hierzu muss sie jedoch zuerst noch durch Hugo gebaut werden, denn bisher saß sie nur auf meinem Computer als Hugo-Projekt. Um das zu umgehen, habe ich mein Git-Repository mit [Render](https://render.com/) verbunden. Render führt den Befehl für mich aus. Somit muss ich nur meine Veränderungen auf GitHub hochladen und meine Webseite wird gebaut.

Geschafft. Falls du Fragen oder Anmerkungen hast, schreib mir. Einzelne Schritte könnte ich dann noch näher ausführen, vielleicht auch in einer Blogserie. Mein Weg zu einem Blog war sicherlich beschwerlicher und mühsamer als mit einer Bloggingplattform, dafür war er aber wesentlich interessanter und lehrreicher.