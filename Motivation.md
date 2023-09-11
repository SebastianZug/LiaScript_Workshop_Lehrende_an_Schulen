<!--
author:   Sebastian Zug, André Dietrich

email:    Sebastian.Zug@informatik.tu-freiberg.de

version:  0.0.2

language: de

narrator: Deutsch Male

mode:     Presentation

comment:  Dieser Kurs für in das Projekt LiaScript ein und diskutiert die
          Vorteile im Kontext der OER Idee.

logo:     ./images/logo.png

translation: Deutsch  translations/German.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/LiaPlayground/Delfi-Workshop-2023/main/Motivation.md)

# Konzepte und Erfahrungen bei der Realisierung dezentraler, offener Lehrmaterialien mit LiaScript

![OER logo](pic/LiaScript_Meets_OER.png "OER-Logo - Quelle: Jonathasmello - Eigenes Werk, CC BY 3.0, [https://commons.wikimedia.org/w/index.php?curid=18460156](https://commons.wikimedia.org/w/index.php?curid=18460156) erweitert um LiaScript Logo")

------------------------------------------------------

<h2>Herzlich Willkommen!</h2>

<h4>DELFI 2023, Aachen 11. September 2023</h4>

_ Der Quellcode kann des Open Source Dokuments ist unter [Link](https://github.com/LiaPlayground/Delfi-Workshop-2023) zu finden._

------------------------------------------------------

## Akteure und Ziele der Veranstaltung

Wer sind wir?
---------------------

+ Sebastian Zug 
+ André Dietrich

Wo soll es hingehen?
--------------------

+ Diskussion der Erwartungen an OER
+ Konzepte von LiaScript für deren Umsetzung
+ Tutorial zu LiaScript anhand eine Beispiels
+ Austausch von Erfahrungen bei der Nutzung von OER

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii

      Wunsch nach                                             Wunsch nach
  einfacher Umsetzung  -----------> Konflikt <----------- spezifischen Elementen
                                       |                       im Material
                                       |
                                       v
                              OER als Lösungsansatz

```


{{1}}
> __Was sind Ihre Erwartungen an den heutigen Nachmittag? Welche Erfahrungen bei der Arbeit mit OER bringen Sie mit?__

## OER Vision

> {0-1}{Lehrende möchten motivierende, interaktive Lehrmaterialien einbetten.}
> {1-2}{Lehrende möchten motivierende, interaktive Lehrmaterialien __mit einem überschaubaren Aufwand realisieren.__}
> {2-4}{Lehrende möchten maximal motivierende, interaktive Lehrmaterialien mit einem überschaubaren Aufwand realisieren, __die optimal auf die eigenen didaktischen Ziele abgestimmt sind.__}


                             {{3}}
********************************************************************************

> Das kann er/sie natürlich alleine realisieren, aber ...

---------------------

**1. Muss er/sie sich über alle Inhalte selbst Gedanken machen**

Beispiel:


- [[male (der)] (female [die]) [neuter (das)]]
- [    [X]           [ ]             [ ]     ]  Mann - German for man
- [    ( )           (X)             ( )     ]  Frau - German for woman

---------------------

**2. Muss er/sie sich erheblichen technischen Herausforderungen stellen**

Beispiel:

??[ear model](https://sketchfab.com/3d-models/ear-anatomy-468e2039bde34a3fabb9e90bff9cd56b)

---------------------

********************************************************************************

### Ausgangspunkt

>  **Open Courseware / Open Educational Resources** ... teaching, learning and
> research materials in any medium, digital or otherwise,that reside in the
> **public domain** or have been released under an open license that permits
> no-cost access, use, **adaptation** and **redistribution** by others with no or 4
> limited restrictions. Open licensing is built within the existing framework of
> intellectual property rights as defined by relevant international conventions
> and respects the authorship of the work
>
> -- UNESCO 2002 Forum on the Impact of Open Courseware for Higher Education in Developing Countries [(Link)](https://unesdoc.unesco.org/ark:/48223/pf0000128515)

           {{0-1}}
********************************************************************************

| Anforderung                  | Bedeutung                                  |
| ---------------------------- | ------------------------------------------ |
| `verwahren/vervielfältigen ` | Download, Speicherung und Vervielfältigung |
| `verwenden`                  | Nutzung im Lernkontext                     |
| `verarbeiten`                | Umgestaltung und Adaption                  |
| `vermischen`                 | Kombination und Extraktion                 |
| `verbreiten`                 | (digitale) Publikation                     |


*_5 V-Freiheiten für Offenheit_ von Jöran Muuß-Merholz und Jörg Lohrer für [open-educational-ressources](https://open-educational-resources.de) - Transferstelle für OER*

> _OER können der Auslöser für Innovation und neue Lenrformen des 21. Jahrhunderts sein._
>
> -- _Handreichung OER - Der Einstieg in den Umgang mit Open Educational Ressources_, Bericht des Projektes OERsax, 2018

********************************************************************************


### Kritik am OER-Ansatz


| Ebene                               | Kernaussage                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------- |
| Emotionale Einordnung               | "_Da kann ja jeder meine Arbeit für sich nutzen!_"                                      |
|                                     | "_Da kann mich ja jeder kontrollieren!_"                                                |
| Rechtliche Herausforderungen        | "_Ich verwende viele Grafiken, die bei deren Urheberrecht ich mir im besten Fall unsicher bin!_"                                                                                        |
| Auffindbarkeit                      | "_Ich finde keine Inhalte, die ich in meiner Lehre gewinnbringend integrieren kann!_"   |
| <!-- Style="color:red" --> Aufwand  | <!-- Style="color:red" --> "_Da muss man ja Informatik studiert haben!_"                |
| <!-- Style="color:red" -->Abdeckung | <!-- Style="color:red" -->"_Da fehlen mir aber die Schnittstellen für meine Tools XY!_" |


### Ideales OER Material - ein Textdokument?

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii

Kurs.txt         Version 1.0          Kurs.txt          Version 1.1
+--------------------------+          +---------------------------+
| Kurs  Deutsche Literatur |          | Kurs  Deutsche Literatur  |
| Autor Peter Muster       | "Fehler" | Autoren Peter Muster      |
|                          |------>   |         Angelika Maier    |----->
|~~~~~~~~~~~~~~~~~~~~~~~~~~|          |~~~~~~~~~~~~~~~~~~~~~~~~~~~|
| Ab 1756 bereiste Goethe  |---.      | Ab 1786 bereiste Goethe   |--.
| Italien ...              |   |      | Italien ...               |  |
                               |                                     |    Course.txt       Version 1.1.2
                               |                                     |    +----------------------------+
                               |                                     |    | Kurs  German Literature    |
                               |                                     |    | Autoren Peter Muster       |
                               |                                     .--> |         Angelika Maier     |
                               |                                          |         Steve Gray         |
                               |                                          |~~~~~~~~~~~~~~~~~~~~~~~~~~~~|
                               |                                          | In 1786 Goethe traveled to |
                               |                                          | Italy ...                  |
                               |      Kurs.txt         Version 1.0
                               |      +---------------------------+
                               |      | Kurs  Goethes Welt        |
                               |      | Autoren Peter Muster      |
                               .-->   |         Angelika Maier    |----->
                                      |~~~~~~~~~~~~~~~~~~~~~~~~~~~|
                                      | Während der italienischen |
                                      | Reise ...                 |
```
*Versionen der Lehrinhalte eines Kurses und deren Wiederverwendung in anderen Veranstaltungen*

{{0-1}}
********************************************************************************

| Anforderung                  | txt |                                                          |
| ---------------------------- | --- | -------------------------------------------------------- |
| `verwahren/vervielfältigen ` | ++  | vorteilhaft wegen geringer Größe                         |
| `verwenden`                  | +   | analoge / digitale Verteilung an Studieren unkompliziert |
| `verarbeiten`                | ++  | verarbeitbar ohne zusätzliche Software                   |
| `vermischen`                 | ++  | einfache Kombination von Textfragmenten per Copy&Paste   |
| `verbreiten`                 | ++  | gut exportierbar                                         |

> **Moment, ein reines Textdokument ist als OER Inhalt perfekt?**

********************************************************************************

{{1-2}}
********************************************************************************

> _1. Die 5V Definition fokussiert das Open in OER lässt aber das Education beiseite._
>
> _2. Die Verwaltung und Auffindbarkeit von OER Inhalten ist dadurch nicht erfasst._

| Anforderung                                           | txt                           |                                                          |
| ----------------------------------------------------- | ----------------------------- | -------------------------------------------------------- |
| `verwahren/vervielfältigen `                          | ++                            | vorteilhaft wegen geringer Größe                         |
| `verwenden`                                           | +                             | analoge / digitale Verteilung an Studieren unkompliziert |
| `verarbeiten`                                         | ++                            | verarbeitbar ohne zusätzliche Software                   |
| `vermischen`                                          | ++                            | einfache Kombination von Textfragmenten per Copy&Paste   |
| `verbreiten`                                          | ++                            | gut exportierbar                                         |
| <!-- Style="color:green" --> verwalten / versionieren | ++                            |                                                          |
| <!-- Style="color:green" -->   (motivierend) verpacken             | <!-- Style="color:red" --> -- | keine zeitgemäßen Formate und interaktiven Inhalte       |

> __Offensichtlich brauchen wir Formate, die neben den positiven Aspekten von Textdarstellungen auch das erweiterte Set von Anforderungen abdecken.__

********************************************************************************

### OER Transparenz

> 1. Materialien müssen transformierbar sein, um eine Wiederverwendung zu ermöglichen. (_Verarbeiten/Verwenden/Verbreiten_)
> 2. Materialien brauchen Metadaten, um auffindbar zu sein. (_Verbreiten_)
> 3. Materialien brauchen offenkundige Versionierungen (_Verwalten_)

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii
+------------------+
| # Digital Systems|\                                      .-----------.
| (SoSe 2021)      +-+                              ╔══════|   LMS  X  |══════╗
|                    |  --------------------------> ║      '-----------'      ║
| ## Task 1          |                              ║ Digital Systems 2021    ║
|                    |                              ║                         ║
| + Implement ...    | --------------+              ║ import numpy as np      ║
|                    |    Trans-     |              ║ ...                     ║
|                    |    formation  |              ╚═════════════════════════╝
+--------------------+               v
                                .-,(   ),-.                .-----------.
Lizenz: ...                  .-(           )-.      ╔══════|   LMS  Y  |══════╗
Inhalt: ...                 (    OER Cloud    )     ║      '-----------'      ║
Autor: ...                   '-(           )-'  +-->║ Digital Systems 2021    ║
Versionshistorie: ...           '-.(   ).-'     |   ║                         ║
                                     |          |
                                     +----------+          .-----------.
                                                |   ╔══════|  Webapp   |══════╗
                                                |   ║      '-----------'      ║
                                                +-->║ Digital Systems 2021    ║
                                                    ║                         ║

```
*Transformation von OER Materialien für die Verwendung in verschiedenen LMS*

## OER in der Praxis

[OERSI](pic/OERSI.png "Screenshot der OER-Sammlung auf OERSI")

### OER in OPAL ...

                {{0-1}}
********************************************************************************

Anderen Kursmaterialien zur Verfügung zu stellen, ist in OPAL im Wesentlichen auf 3 Wegen möglich:

+ für ganze Kurse

   - innerhalb der OPAL "Welt" als offene Kurse
   - über Exportschnittstellen, die die Einbettung in andere LMS ermöglichen
   - manuelle Übertragung

+ für einzelne Dateien

   - Dateien mit Meta-Informationen und expliziter Angabe

![alt-text](https://github.com/SebastianZug/WillkommenAufLiaScript/blob/master/images/OER_in_OPAL.png?raw=true "Screenshot eines OER Materials im OPAL LMS, 22. März 2022")

********************************************************************************

                    {{1-2}}
********************************************************************************

Welche Muster lassen sich mit Blick auf die verfügbaren Kurse erkennen?

![](https://github.com/SebastianZug/WillkommenAufLiaScript/blob/master/images/OERExtractedMetaInformation.png?raw=true "Verfügbare Metadaten im Bestand der offenen OPAL Materialien")

<!-- data-type="BarChart"
data-title="Anteil der Datenformate im Kontext der OPAL OER Materialien"
data-xlabel="Datentyp"
data-ylabel="% of Anzahl" -->
| Dateityp | Anzahl | ratio    |
| -------- | ------ | -------- |
| `pdf`    | 5242   | 0.49     |
| `jpg`    | 1040   | 0.09     |
| `mkv`    | 873    | 0.08     |
| `mp4`    | 586    | 0.05     |
| `png`    | 494    | 0.04     |
| `zip`    | 443    | 0.04     |
| `html`   | 387    | 0.03     |
| `docx`   | 376    | 0.03     |
| `pptx`   | 245    | 0.02     |
| `xlsx`   | 191    | 0.01     |


Die Materialien im OPAL kommen überwiegend als geschlossenes Dateiformat (und ohne Metainformationen) daher. Eine Wiederverwendung ist entsprechend nur schwer möglich.

********************************************************************************

### OER in LiaScript ...

*LiaScript* löst den Inhalt vom LMS und erlaubt die Anwendung von Methoden der verteilten Softwareentwicklung.

- Beschreibungssprache
- Verteilte Entwicklung
- Serverlose Infrastruktur
- Dynamische Inhalte

Weitere Informationen finden Sie unter der Projektwebseite [https://liascript.github.io/](https://liascript.github.io/) in der [Dokumentation](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1) oder dem [Youtube-Channel](https://www.youtube.com/channel/UCyiTe2GkW_u05HSdvUblGYg)
