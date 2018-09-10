---
layout: post
pretitle: A11y-Ressourcen und Slides vom Frontend RheinMain Meetup Nr. 17
title: Accessibility Talk-Highlights 2018
published: true
---

<blockquote class="twitter-tweet" data-lang="de"><p lang="de" dir="ltr">Riesendank an Boris, über 2 Stunden Accessibility aus High-level- und technischen Perspektiven zu durchdringen! Das war spannend und wurde äußerst kompetent vermittelt. (1/2) <a href="https://t.co/LTR99h36qA">pic.twitter.com/LTR99h36qA</a></p>&mdash; Frontend RheinMain (@frontend_rm) <a href="https://twitter.com/frontend_rm/status/1030357210721935362?ref_src=twsrc%5Etfw">17. August 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


Aus den geschätzten 1,5 Stunden zu Boris Diakurs Accessibility-Session am 16.08. bei den [Codemonauts](https://codemonauts.com/) wurden am Ende dann doch deutlich über 2(!) hochinteressante Stunden, in denen Boris es schaffte, alle Aspekte dieses Themenkomplexes fundiert, praxisorientiert, so knapp wie möglich und so ausführlich wie nötig zu vermitteln. Anhand eines Großprojektes, bei dem Accessibility-Themen (leider wie so oft) erst spät adäquat implementiert wurden, zeigte er, wie sowohl mit kleinen Anpassungen wichtige Basics berücksichtigt werden konnten und auch welche Aufwände in modernen Webprojekte investiert werden müssen und sollten, um bestmögliche Zugänglichkeit zu erreichen. Auch wenn es immer schwer ist, den Vortragsfolien zu folgen, wenn man an dem Abend nicht da sein konnte, sind die Slides dennoch sehr gut  zu lesen, daher eine absolute Lese-Empfehlung von uns :-)

Bittesehr:

[!["Web Accessibility"]({{ site.url }}/attachments/2018-08-16/img/a11y.png)]({{ site.url }}/attachments/2018-08-16/slides/2018-08-16-Frontend_RheinMain_Web_Accessibility_Boris_Diakur.pdf)

Anett von den [Codemonauts](https://codemonauts.com/) und ich, Jan, haben dies zum Anlasse genommen, in diesem Artikel die A11y-Highlights aus diesjährigen Frontend-Konferenzen zusammenzutragen. Am Ende findet Ihr noch ein paar weitere Ressourcen. Bitte diesen Artikel gerne teilen / weiterleiten, denn dieses zugegebenermassen nicht immer einfache Thema sollte viel mehr Beachtung im "daily business" bei uns Webworkern finden. Genug der Worte - los geht's.

# Marcy Sutton: “Empathy-Driven Development”
 
Dieser Talk zeigt Tools und Techniken zum Einstieg in die barrierefreie Webentwicklung insbesondere mit JavaScript. (Mit Live-Coding! :) Alle Ressourcen sind auch im [github-Repository](https://github.com/marcysutton/empathy-driven-development) zugänglich.)

<iframe width="705" height="396" src="https://www.youtube.com/embed/l95VFLj3e2w" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Valerie Woolard Srinivasan: “Logging Off: Improving Low-Connectivity Experiences on the Web”

In unserer modernen, westlichen Welt haben wir selten Probleme mit (sehr) langsamen Internetverbindungen. In einer Welt, in der aber immer mehr Menschen auf das Internet von mobilen Endgeräten und schlechter(er) Infrastruktur zugreifen, muss man sich auch über diese Nutzer Gedanken machen.
Dieser Talk zeigt Grundlagen zum Design für “low-connectivity” Nutzer und warum das so wichtig ist.

<iframe width="705" height="396" src="https://www.youtube.com/embed/G96ie93tn5Q" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Florence Okoye: “Hey you, do you even design?”

Weniger technische Instruktionen und mehr Denkanstöße liefert dieser Talk zu den Stichworten “Empathy Driven Design”, Programmierethik, Nachhaltigkeit und soziale Auswirkungen. Florence zeigt wie schlechtes Design beim Nutzer versagt, unter Umständen gefährdet und was es bedeutet für das moderne Web zu entwickeln.

<iframe width="705" height="396" src="https://www.youtube.com/embed/Bmm4-2SJ8qQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Shwetank Dixit: “Augmenting Empathy: Simulating Low-Vision Conditions with CSS, SVG and WebRTC”

Sehbehinderung ist ein Überbegriff für viele verschiedene Arten von visueller Einschränkung. Shwetank hat mit sehbehinderten Menschen und ihren Familien gesprochen, um die unterschiedlichen Arten von Sehbehinderungen bzw. visuellen Einschränkungen besser zu verstehen und darauf basierend ein Tool gebaut, welches - mit CSS, SVG und WebRTC - verschiedene Sehbehinderungen simuliert.

<iframe width="705" height="396" src="https://www.youtube.com/embed/aWoeK2SFSpI" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Dag-Inge Aas: “Accessible by Law! Generating Colors with JS and CSS Custom Properties”

In Norwegen müssen alle Webseiten nach dem Gesetz barrierefrei sein. Dag-Inge hat daraufhin mit Confrere einen Service geschaffen, der es Menschen erleichtert, für ihre Brand bzw. Onlinepräsenz Farben zu wählen, die trotzdem noch ausreichend Kontrast haben. Mit CSS Custom Properties und etwas JavaScript können sie nun Farbpaletten und Komponenten erzeugen, die die WCAG-Kriterien erfüllen.

<iframe width="705" height="396" src="https://www.youtube.com/embed/zi6L0ZqrKfA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Laura Carvajal: "Common Ways We Break Accessibility and How to Avoid Them"

Die Accessibility-Fails, die Laura Carvajal (Financial Times) sehr prägnant u.a. anhand von A11y-Audits von Testern mit physischen und visuellen Einschränkungen bei der Bedienung z.B. von amazon.com und kayak.com zeigt, sind elementare Guidelines, die heute längst selbstverständlich sein sollten: Sichtbarer Focus-Ring statt "outline: 0", Erreichbarkeit von Navigationslementen per Tab-Taste, geordnete Überschriften (Abbildung der Seitenhierarchie) sowie Video- & Bild-Bechriftungen, um nur die Basics zu nennen.

<iframe width="705" height="396" src="https://www.youtube.com/embed/O_OJfY4Jax4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Weitere Ressourcen

- Event: [Accessibility Club](https://accessibility-club.org/) am 5. November am Vorabend der [beyond tellerrand](https://beyondtellerrand.com/events/berlin-2018) in Berlin
- Buch: [Accessibility for Everyone](https://abookapart.com/products/accessibility-for-everyone)(A Book Apart)
- [Linksammlungen](http://grochtdreis.de/weblog/category/barrierefreiheit/) von Jens Grochtdreis zu Accessibility

 
