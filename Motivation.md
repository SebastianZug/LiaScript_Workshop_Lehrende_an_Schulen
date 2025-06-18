<!--
author:   Sebastian Zug, André Dietrich

email:    Sebastian.Zug@informatik.tu-freiberg.de

version:  0.0.3

language: de

narrator: Deutsch Male

mode:     Presentation

comment:  Dieser Kurs für in das Projekt LiaScript ein und diskutiert die
          Vorteile im Kontext der OER Idee.

logo:     ./images/logo.png

import:   https://raw.githubusercontent.com/LiaTemplates/LiveEdit-Embeddings/refs/tags/0.0.1/README.md

translation: Deutsch  translations/German.md

@style
.flex-container {
    display: flex;
    flex-wrap: wrap; /* Allows the items to wrap as needed */
    align-items: stretch;
    gap: 20px; /* Adds both horizontal and vertical spacing between items */
}

.flex-child { 
    flex: 1;
    margin-right: 20px; /* Adds space between the columns */
}

@media (max-width: 600px) {
    .flex-child {
        flex: 100%; /* Makes the child divs take up the full width on slim devices */
        margin-right: 0; /* Removes the right margin */
    }
}
@end

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/SebastianZug/LiaScript_Workshop_Lehrende_an_Schulen/refs/heads/main/Motivation.md)

# Konzepte und Motivation hinter LiaScript


<section class="flex-container">

<!-- class="flex-child" style="min-width: 250px;" -->
> <h2>Herzlich Willkommen!</h2>
>
><h4>LiaScript Workshop für Lehrinnen und Lehrer sächsischer Schulen, Freiberg 18. Juni 2024</h4>

<!-- class="flex-child" style="min-width: 250px;" -->
![partner_map](pic/LiaScript_Meets_OER.png "OER-Logo - Quelle: Jonathasmello - Eigenes Werk, CC BY 3.0, [https://commons.wikimedia.org/w/index.php?curid=18460156](https://commons.wikimedia.org/w/index.php?curid=18460156) erweitert um LiaScript Logo")

</section>

--------------------------------------------

_ Der Quellcode kann des Open Source Dokuments ist unter [Link](https://github.com/SebastianZug/LiaScript_Workshop_Lehrende_an_Schulen/blob/main/Motivation.md) zu finden._


## Akteure und Ziele der Veranstaltung

Wer sind wir?
---------------------

+ Sebastian Zug 
+ André Dietrich

Wo soll es hingehen?
--------------------

+ Konzepte von LiaScript für deren Umsetzung
+ Tutorial zu LiaScript anhand eine Beispiels
+ Austausch von Erfahrungen bei der Nutzung von OER im Schulkontext


{{1}}
> __Was sind Ihre Erwartungen an den heutigen Nachmittag? Welche Erfahrungen bei der Arbeit mit digitalen Lehr-Lern-Materialien bringen Sie mit?__

## Ausgangspunkt

>  <!-- Style="color:green" -->__Lehrende möchten motivierende, interaktive Lehrmaterialien in ihren Unterricht einbetten.__

                  {{0-1}}
********************************************

---------------------

Beispiel Quizze:


- [[male (der)] (female [die]) [neuter (das)]]
- [    [X]           [ ]             [ ]     ]  Mann - German for man
- [    ( )           (X)             ( )     ]  Frau - German for woman

********************************************

                  {{1-2}}
********************************************

---------------------

Beispiel 3D-Modelle:

??[ear model](https://sketchfab.com/3d-models/familienschacht-freiberg-germany-7c7d30506c554385a4a4321366e2e601)


********************************************

                  {{2-4}}
********************************************

__Aber ...__

+ Die individuelle Umsetzung ist aufwändig und zeitintensiv.
+ Für verschiedene Formate (z.B. Text, Video, Audio, 3D-Modelle) gibt es unterschiedliche Werkzeuge.
+ Bestehende Inhalte sind nicht auf die individuellen Bedürfnisse von Lehrenden und Lernenden zugeschnitten.
+ ...

> Welche weiteren Hemmnisse kennen Sie aus Ihrer Praxis?

********************************************

{{3}}
```ascii

      Wunsch nach                                             Wunsch nach
  einfacher Umsetzung  -----------> Konflikt <----------- spezifischen Elementen
                                                               im Material
                                                                                                   .
```


### OER als Lösungsansatz

           {{0-3}}
**************************************

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

> OER beschreibt die gemeinsame Entwicklung, Nutzung und Verbreitung von Lehr- und Lernmaterialien, die unter einer offenen Lizenz stehen.

************************************

           {{1-2}}
**************************************

>  **Open Courseware / Open Educational Resources** ... teaching, learning and
> research materials in any medium, digital or otherwise,that reside in the
> **public domain** or have been released under an open license that permits
> no-cost access, use, **adaptation** and **redistribution** by others with no or 4
> limited restrictions. Open licensing is built within the existing framework of
> intellectual property rights as defined by relevant international conventions
> and respects the authorship of the work
>
> -- UNESCO 2002 Forum on the Impact of Open Courseware for Higher Education in Developing Countries [(Link)](https://unesdoc.unesco.org/ark:/48223/pf0000128515)

**************************************

           {{2-3}}
**************************************

| Anforderung an OER Materialien | Bedeutung                                  |
| ------------------------------ | ------------------------------------------ |
| `verwahren/vervielfältigen `   | Download, Speicherung und Vervielfältigung |
| `verwenden`                    | Nutzung im Lernkontext                     |
| `verarbeiten`                  | Umgestaltung und Adaption                  |
| `vermischen`                   | Kombination und Extraktion                 |
| `verbreiten`                   | (digitale) Publikation                     |


*_5 V-Freiheiten für Offenheit_ von Jöran Muuß-Merholz und Jörg Lohrer für [open-educational-ressources](https://open-educational-resources.de) - Transferstelle für OER*

**************************************


### Kritik am OER-Ansatz


| Ebene                               | Kernaussage                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------- |
| Emotionale Einordnung               | "_Da kann ja jeder meine Arbeit für sich nutzen!_"                                      |
|                                     | "_Da kann mich ja jeder kontrollieren!_"                                                |
| Rechtliche Herausforderungen        | "_Ich verwende viele Grafiken, die bei deren Urheberrecht ich mir im besten Fall unsicher bin!_"                                                                                        |
| Auffindbarkeit                      | "_Ich finde keine Inhalte, die ich in meiner Lehre gewinnbringend integrieren kann!_"   |
| <!-- Style="color:red" --> Aufwand  | <!-- Style="color:red" --> "_Da muss man ja Informatik studiert haben!_"                |
| <!-- Style="color:red" -->Abdeckung | <!-- Style="color:red" -->"_Da fehlen mir aber die Schnittstellen für meine Tools XY!_" |


### Idealer Prozess 

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

| Anforderung                  | txt | Begründung                                               |
| ---------------------------- | --- | -------------------------------------------------------- |
| `verwahren/vervielfältigen ` | ++  | vorteilhaft wegen geringer Größe                         |
| `verwenden`                  | +   | analoge / digitale Verteilung an Studieren unkompliziert |
| `verarbeiten`                | ++  | verarbeitbar ohne zusätzliche Software                   |
| `vermischen`                 | +   | einfache Kombination von Textfragmenten per Copy&Paste   |
| `verbreiten`                 | +   | gut exportierbar                                         |

> **Moment, ein reines Textdokument ist als OER Inhalt perfekt? Wahrscheinlich nicht!**

********************************************************************************

{{1-2}}
********************************************************************************

> _1. Die 5V Definition fokussiert das Open in OER lässt aber das Education beiseite._
>
> _2. Die Verwaltung und Auffindbarkeit von OER Inhalten ist dadurch nicht erfasst._


Erweiterte 7V Definition an OER Inhalte:

| Anforderung                                            | txt                           | Begründung                                               |
| ------------------------------------------------------ | ----------------------------- | -------------------------------------------------------- |
| `verwahren/vervielfältigen `                           | ++                            | vorteilhaft wegen geringer Größe                         |
| `verwenden`                                            | +                             | analoge / digitale Verteilung an Studieren unkompliziert |
| `verarbeiten`                                          | ++                            | verarbeitbar ohne zusätzliche Software                   |
| `vermischen`                                           | +                             | einfache Kombination von Textfragmenten per Copy&Paste   |
| `verbreiten`                                           | +                             | gut exportierbar                                         |
| <!-- Style="color:green" --> verwalten / versionieren  | ++                            |                                                          |
| <!-- Style="color:green" -->   (motivierend) verpacken | <!-- Style="color:red" --> -- | keine zeitgemäßen Formate und interaktiven Inhalte       |

> __Offensichtlich brauchen wir Formate, die neben den positiven Aspekten von Textdarstellungen auch das erweiterte Set von Anforderungen abdecken.__

********************************************************************************

### Wie lösen das andere Autorenkollektive?

Wikipedia ist ein gutes Beispiel für eine Plattform, die die 5V-Freiheiten umsetzt und dabei eine große Menge an Inhalten bereitstellt. Die Inhalte sind in einem offenen Format (MediaWiki) gespeichert und können von jedem bearbeitet und weiterverwendet werden.

Wikipedia nutzt dabei eine einfache Textsprache (Wikitext), die es ermöglicht, Inhalte zu formatieren und zu strukturieren. 

```markdown     Ausschnitt aus dem Wikipedia Artikel "Informatikunterricht"
== Lehrinhalte ==
Der Umgang mit EDV ist heute nicht nur allgemeine Berufsvorbereitung bzw. allgemeine Studienvorbereitung, 
sondern zählt zur [[Allgemeinbildung]].<ref name="Micheuz 2001">[[#Literatur|Lit.]] Micheuz 2001, 
zitiert nach {{Internetquelle |url=http://www.schulinformatik.at/fachdidaktik/03-wozu-infount.pdf |
titel=Wozu Informatikunterricht? |hrsg=schulinformatik.at |format=PDF; 31&nbsp;kB |abruf=2010-01-10}}</ref> 
Häufig wird in diesem Zusammenhang der Begriff ''[[Computerführerschein]]'' verwendet.
```

https://de.wikipedia.org/w/index.php?title=Informatikunterricht&action=edit

> Der Wikipedia-Ansatz hat mit Blick auf Lehrmaterialien aber entscheidende Nachteile. Die Inhalte sind:

- nicht auf die individuellen Bedürfnisse von Lehrenden und Lernenden zugeschnitten,
- statisch und nicht interaktiv,
- nicht in einem Format, das eine einfache Integration in Lernmanagementsysteme (LMS) ermöglicht,
- ...


## LiaScript - Kernkonzepte 


                        {{0-1}}
*******************************************************

> __1. Wir trennen Darstellung und Inhalt! Alle Elemente werden soweit wie möglich durch eine rein textuelle Repräsentation ausgedrückt.__

```markdown @embed.style(height: 550px; min-width: 100%; border: 1px black solid)
# Vom Text zur Darstellung

__Text__

Hallo Welt!

__Mathematik__

$f(x) = x^2$

__Tabellen__

| x | B(x) | C(x) |
|---|:----:|:----:|
| 1 |   2  |   3  |
| 4 |   5  |   6  |

```

*******************************************************

                        {{1-2}}
*******************************************************

> __2. Lehre lebt von Interaktion__

```markdown @embed.style(height: 550px; min-width: 100%; border: 1px black solid)
# Lehre lebt von Interaktion

__Tabellen als Grafiken__

| X | B(y) | C(y) |
|---|:----:|:----:|
| 1 |   2  |   3  |
| 4 |   5  |   6  |

__Quizze__

Wann wurde die TU Bergakademie gegründet?

- [(X)] 1765
- [( )] 1896
```

*******************************************************

                        {{2-3}}
*******************************************************

> __3. Der Browser kann viel mehr als Webseiten anzuzeigen.__

````markdown @embed.style(height: 550px; min-width: 100%; border: 1px black solid)
<!--
import: https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md
-->

# Browserfeatures / JavaScript

__Sprache__

> Click to run!
>
> {{|> Deutsch Female}}
> Hallo liebe LiaScript Interessierte!

__Datenspeicherung__

``` abc
X:353
T: GLUECK AUF DER STEIGER KOEMMT
N: E1512
O: Europa, Mitteleuropa, Deutschland
R: Staende -, Bergmanns - Lied
M: 4/4
L: 1/16
K: G
| G8F4A4 | G8z8 | B8A4c4 | B8z4G2A2 | B4B4B4A2B2 | c4A3AA4
A2B2 | c4c4c4B2c2 | d4B3BB4A4 | G8F8 | G4e4d4c2A2 | B8A8 | G8z8
```
@ABCJS.eval
````

*******************************************************

                        {{3-4}}
*******************************************************


> __4. Wir brauchen Werkzeuge für die Umsetzung in verschiedenen Umgebungen.__

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii
+------------------+
| # Digital Systems|\                                      .-----------.
| (SoSe 2021)      +-+                              ╔══════|   LMS  X  |══════╗
|                    |  --------------------------> ║      '-----------'      ║
| Task 1             |                              ║ Digital Systems 2021    ║
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


*******************************************************

## Zusammenfassung

LiaScript löst den Inhalt vom LMS und erlaubt die Anwendung von Methoden der verteilten Softwareentwicklung.

- Beschreibungssprache
- Verteilte Entwicklung
- Serverlose Infrastruktur
- Dynamische Inhalte


Weitere Informationen finden Sie unter der Projektwebseite [https://liascript.github.io/](https://liascript.github.io/) in der [Dokumentation](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1) oder dem [Youtube-Channel](https://www.youtube.com/channel/UCyiTe2GkW_u05HSdvUblGYg)

> __Jetzt wird es spannend und Sie sind gefragt ...__
> 
> __Rufen Sie bitte den Link http://bit.ly/4kWiUFh auf, um den LiveEditor zu starten.__