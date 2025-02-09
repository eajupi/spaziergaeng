# Shadows Bane - Banish the Night

## Table of Contents
In dieser ReadMe wirst du Informationen zu unserem Spiel bekommen, unterteilt in folgende Unterpunkte:

1. [About the project "Shadows Bane"](#project-shadows-bane)
2. [The game](#game)
3. [Gameplay](#gameplay)
4. [Installation of the game](#installation)
5. [Found a bug?](#bug-reporting)
6. [Contributors ](#contributors)

---

## Project Shadows Bane
Shadows Bane ist ein rundenbasiertes Dark-Fantasy-Spiel, in dem der Spieler Lichtkreaturen gegen finstere Schattenwesen steuert. Das Game ist das Ergebnis unseres Kurses "Spielprojekt" von unserer Universität. 

In der Spielentwicklung musste man das Theme "Living light" berücksichtigen und dazu noch eine neue Technologie in das Spiel einbauen. Ersteres wird im nachfolgenden Punkt "Game" besprochen. Die neue Technologie ist in unserem Fall eine KI-basierte Steuerung über natürliche Spracheingaben (NLP).

Da das Spiel noch nicht fertiggestellt ist, gibt es derzeit nur eine Demo mit 2-3 Kämpfen inklusive Boss-Fight und Tutorial. Bis zur fertigstellung werden noch weitere Features folgen und natürlich auch mehr Kämpfe.

---

## Game
Das Theme wurde folgendermaßen realisiert: Zum einen wird die Map am Anfang eher Dunkel sein und der Protagonist (bei uns ein Ritter) wird sich durch die Map kämpfen und durch gewonnene Kämpfe das Licht in der Map verbreiten. Dadurch schaltet man neue Kämpfe in der Map frei, die der Ritter wieder bestreiten kann. 

Das Ziel ist es die ganze Map freizuschalten und jeden der Kämpfe anschließend zu gewinnen, sodass die Map am Ende auch von der Dunkelheit befreit ist. 

Der Ritter wird seine Kämpfe mit 2 Allies bestreiten die er durch den eingegebenen Textprompt steuern kann. Dabei wird der eingegebene Prompt von der KI interpretiert und diese sucht dann einen Move aus der zum Prompt passt. Man muss dabei beachten das jeder Ally von dir anders reagiert – finde heraus, wie du sie am besten lenken kannst.

Es gibt derzeit 5 Moves für die sich die KI entscheiden kann, Heavy Attack, Small Attack, Dodge, Communicate und Defend. Abhängig von deiner Text Eingabe wird die KI einen der 5 Moves auswählen und dein jeweiliger Ally vollzieht diesen Move dann.

---

## Gameplay 


