# Titel

_ausstehend:_

> "Micro-Frontend", "Portal", "App-Shell", "Integration von Micro-Frontends", "Evaluation Richtung Qualitätsanforderungen, wie Sicherheit, Performance, Nutzbarkeit, Wartbarkeit oder techn. Rahmenbedingungen" 

## Motivation

_TODO:_

In der heutigen Zeit sind Microservices im Backend häufig das Mittel der Wahl. Microservices sorgen für eine lose Kopplung und erhöhen die Unabhängigkeit beim Deployment einzelner Funktionen.

Bietet ein Microservice Schnittstellen für eine Oberfläche an, so werden heutzutage die Schnittstellenangebote von Microservices in einem Application-Monolithen zusammengeführt. Dieser Monolith erhöht allerdings die Abhängigkeiten zwischen den darunterliegenden Microservices. 

![aus "iframes – der heilige Gral bei verteilten Webanwendungen"](https://heise.cloudimg.io/width/1043/q70.png-lossy-70.webp-lossy-70.foil1/_www-heise-de_/developer/imgs/06/2/7/3/0/9/6/2/Abbildung_1-e605c863eaedd610.png)
_Quelle: https://www.heise.de/developer/artikel/iframes-der-heilige-Gral-bei-verteilten-Webanwendungen-4496075.html_

Eine Lösung sind "Micro-Frontends", die die jeweiligen Funktionen eines Microservices unabhängig von anderen Services anbieten können.
Allerdings stellt sich die Frage nach der richtigen Integration und Orchestrierung der einzelnen Micro-Frontends zu einer vollwertigen Anwendung.

### Aufgabe

_TODO:_

Diese Arbeit soll Möglichkeiten zur Integration und Orchestrierung von Micro-Frontends beleuchten.

Es soll ein Kriterienkatalog erstellt werden, der wichtige Qualitätsanforderungen, wie Sicherheit, Performance, Nutzbarkeit, Wartbarkeit etc. enthält und die verschiedenen Ansätze für Micro-Frontends vergleichbar macht.

Die eXXcellent möchte am Ende eine Zusammenfassung der Integrationsmöglichkeiten mit deren Vor- und Nachteilen. Der Kriterienkatalog kann zur Entscheidungsfindung im Projekt und zur Angebotsphase beim Kunden Verwendung finden.
Die Implementierungen der Prototypen dienen als Referenz.

### Ansatz

_TODO:_

Folgende Ansätze sollen beleuchtet werden:
- Aufstellung der verschiedenen Ansätze für Micro-Frontends (Literatur).
- Vorstellung der verschiedenen Konzepte (Literatur).
- Kriterienkatalog erarbeiten.
  - Isolation der Micro-Frontends
  - Kommunikation/ Datenaustausch zwischen Portal->Micro-Frontend, zwischen Micro-Frontend->Micro-Frontend
- Konzept, Mockups, Funktionsbeschreibung etc. für einen Prototypen skizzieren, mit dem die Kriterien geprüft werden können.
- Prototypen mit bestimmten Technologien und Frameworks implementieren
  - Angular (z.B. als SPA und Web Component)
  - React
  - Vue.js
  - Vanilla JS, HMTL

Integration der Prototypen in einem "Portal" per
- Hyperlink
- iFrame
- Web Component
- Single Single Page Application Framework
  - Mono-Repo- bzw. Workspace-Ansatz zur Sicherstellung der einheitlichen Dependency-Nutzung



#### Tags:

- **`Definition`**
- ⭐ lesenswert

### Literatur

- ...

### Referenzen

2019-08-21:

- ⭐ Möglichkeiten zur Integration von Micro-Frontends: https://www.heise.de/developer/artikel/Raus-aus-der-Legacy-Falle-Single-Page-Applications-und-Micro-Apps-4165029.html?seite=all
- Integrationspattern: https://www.heise.de/developer/artikel/Integrations-Patterns-bei-JavaScript-Anwendungen-3970085.html?seite=all
- iFrames: https://www.heise.de/developer/artikel/iframes-der-heilige-Gral-bei-verteilten-Webanwendungen-4496075.html

