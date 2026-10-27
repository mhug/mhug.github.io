---
title: TEIKiss – Proof of Concept 
date: 2026-09-25
links:
  - type: site
#    url: https://github.com/deutschestextarchiv/gbfemmes
weight: 100
summary: Zu einer konzeptionellen Trennung von Daten und Diensten 

image:
  caption: 'Screenshot der statischen [Text-Bild-Ansicht](https://www.deutschestextarchiv.de/teikiss/output/sophie-tieck/tieck_klagen_1807.TEI-P5.html)'
  focal_point: Smart
  preview_only: false


---

### TEIKiss - PoC

Die DFG Antrags- und Job-Ausschreibungslandschaft folgt gewissen
Zyklen: Mal ist alles interdisziplinär, mal geht nichts ohne
DH-Kenntnisse, mal geht es nicht unter einer virtuellen
Forschungsinfrastruktur. Entgegen Letzterem habe ich als Mitarbeiter
des Deutschen Textarchivs in den letzten Jahren das Konzept
einer strikten Trennung von Daten und Diensten wie eine Monstranz vor
mir hergetragen. Die dahinterliegende Überlegung: In Zeiten von
degressiver Förderung muss der Fokus auf der nachhaltigen
Bereitstellung von Forschungsdaten liegen. Alle darüber hinausgehenden
Services (Korpusanalyse, Datenpräsentation etc.) sind, wenn immer
möglich, davon getrennt zu denken. Vorzuziehen ist
überdies hinaus die schlanke Lösung, Stichwort: statische Seiten.

Genau in diese Kerbe schneidet eine neue Software-Entwicklung:
[TEIKiss](https://github.com/deutschestextarchiv/teikiss) – keep it simple, stupid! 
Die von Frank Wiegand an der BBAW entwickelte Software will mit validen
TEI-Daten gefüttert werden und macht daraus dann – auf Basis der
enthaltenen Informationen – eine Webpräsentation inkl.
Faksimileansicht. Einfach, simpel, nachhaltig.

<!--
Als Proof of Concept wurde ein Minikorpus erstellt. Drei bereits
digitalisierte Bücher wurden dazu skriptbasiert konvertiert, in TEI P5
aufbereitet und werden mittels TEIKiss in einer Präsentationsschicht
dargestellt. Ein wichtiges Desiderat ist – im Hinblick auf ein
entsprechend großes Korpus – die fehlende Suche. Hier gibt es im
Kontext der NFDI interessante Entwicklungen. So wurden bspw. Bestände
der Deutschen Nationalbibliothek (DNB) über die am
Leibniz-Institut für deutsche Sprache in Mannheim (IDS) entwickelte
Korpussuche KoRaP zugänglich gemacht. 
-->
