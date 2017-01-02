# megalotopia
Hintergrund:
  Dieses Projekt stellt eines Weiter- und zugleich Neuentwicklung meines Abschlussprojektes im Rahmen der FIAE-Ausbildung dar.

Megalotopia:
  Ziel des Projektes ist die Schaffung einer bequemen Möglichkeit der Ersteinrichtung von Windowscomputern. Abhängig vom Nutzungsszenario soll es eine Variante mit einer GUI geben oder eine Variante welche zur unbeaufsichtigen Einrichtung gedacht ist.
  Eine Auswahl der Dinge die abgearbeitet werden sollen:
    * Installation von Treibern
    * Installation von Updates
    * Installation/Einrichtung von Programmen,
    * Konfiguration von Einstellungen innerhalb von Windows.
    
  Kerne dieses Projektes wie die Verwaltung einer Art Softwarebibliothek sollen xml basiert sein.
  
  Funktionsablauf GUI-Variante:
  Der Nutzer wählt anhand einer möglichst intuitiv gestalteten Oberfläche welche Funktionen/Einstellungen umgesetzt werden sollen. Ein besonderer Schwerpunkt liegt hier auf einer möglichst großen DAU-Kompatibilität. Sobald alle Einstellungen "markiert" wurden, werden diese im Anschluss vom Programm abgearbeitet.
  
  Funktionsablauf unbeaufsichtigte Variante:
  Der Nutzer (in diesem Falle eine bereits mit dem Programm vertraute Person) wählt ähnlich wie in der GUI-Variante einzelne Funktionen/Einstellungen aus, nur das es hier an manchen Stellen erweiterte Funktionen gibt. Am Ende wird eine xml-Datei generiert die alle zu setzenden Änderungen enthält. Diese Datei kann im Anschluss nochmals überarbeitet/modifiziert werden. Ist der Nutzer zufrieden mit dem was die xml-Datei umsetzen soll, so kann mit dieser über verschiedene Wege eine Art interpreter gefüttert werden, der die xml Datei schliesslich umsetzt. xml-Datei und der Interpreter können über verschiedene Wege verteilt werden. 
