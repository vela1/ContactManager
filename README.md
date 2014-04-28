ContactManager
==============

Die Anwendung „Contact Manager“ ermöglicht es dem Benutzer Kontaktdaten zu verwalten. Die
Kontaktdaten werden aus einer oder mehreren CSV-Datei(en) eingelesen (Import) bzw. manuell
durch den Benutzer erstellt. Die Datenhaltung erfolgt vorerst mit Hilfe einer Datei (Persistenz). Es ist
jedoch abzusehen, dass diese Lösung in einer der nächsten Versionen auf eine Datenbanklösung um-
gestellt wird.

Erste Ideen und Entwürfe wurden bereits diskutiert und in Form einzelner UML Diagramme doku-
mentiert. Die Entwürfe sind jedoch nicht vollständig und sollen währen der Entwicklung ergänzt /
korrigiert oder falls nötig neu erstellt werden.

Folgende wichtige Funktionen wurden im Gespräch mit dem Auftraggeber identifiziert:


- Basisfunktionen:

1. Kontakte anzeigen
2. Kontakte erstellen
3. Kontakte löschen
4. Kontakte finden über alle Kontaktinforamtionen
5. Kontakte filtern nach Kategorie
6. Kontakte exportieren (csv, später datenbank)
7. Kontakte importieren (csv, später datenbank)

- Featurefunktionen:

8. Manager Info


Projektbeschreibung

Die Entwicklung erfolgt versioniert (Git!) in Teams mit 2-3 Mitgliedern. Die Liefe-
rung(en) erfolgen in mehreren Versionen aufgeteilt (vgl. Sprints od. Meilensteine).
Dazu müssen Sie die Lieferungen mit priorisierten Funktionen abstimmen und planen!

Tools und Frameworks:

  1. laut Vorgabe:
  - Apache Maven
  - Apache Log4J
  - Java 1.7
  - JUnit 4.11 mit Mockito

  2. zusätzliche Tools und Frameworks:
  - JavaFX (GUI)
  - openCSV (import, export from file)


Die Entwicklung muss gemäß anerkannter Software Engineering Prinzipien und Methoden erfolgen. 
Dazu zählen u.a.: 

- Anforderungsmanagement
- Erstellung
- Pflege von Unit Tests
- Bereitstellung passender Testdaten
- Beachtung von OO-Entwurfsprinzipien wie „Don‘t Repeat Yourself“
- Separation of Concerns
- Single Responsibility Principle
- Modularisierung
- Kapselung und Wiederverwendung (u.a. durch Einsatz von Entwurfsmustern) etc.




