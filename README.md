# Beschreibung
Im fünften und letzten Assignment sollen die fehlenden Funktionalitäten von __QuizQuest__ umgesetzt werden. 
Die Grundlage dazu stellt der Code von Assignment 4 dar. 
Bauen Sie auf diesen Code auf und erweitern Sie die Funktionalität gemäß der Angabe.
Der Code von Assignment 4 soll verwendet werden, und anschließend in dieses Repository gepusht werden.

Die Gestaltung (Design) ist Ihnen frei überlassen, die nachfolgenden Funktionalitäten müssen hinsichtlich Businesslogik vollständig erfüllt sein. 

# Quiz spielen (10 Punkte)
Wenn ein Spiel mit dem "Open"-Button geöffnet wird, soll dieses geöffnet werden. 
Das Quiz soll nun starten - falls es zum ersten Mal geöffnet wird, soll bei der ersten Frage begonnen werden, ansonsten bei der zuletzte beantworteten Fragen fortgefahren werden. 
Es soll ein neues Template erstellt werden, das folgende Informationen enthält: 

1. Frage
2. Antwortmöglichkeiten (mindestens zwei, maximal vier) als Buttons

Sobald auf einen der Antwortmöglichkeiten (d. h. einen der Buttons) geklickt wird, wird die Antwort abgesendet. 
Eine Naviation (d. h. ein vorspringen bzw. zurückkehren) ist nicht vorgesehen. 

# Quiz-Übersicht (4 Punkte)
Alle Spiele die von einem Player abgeschlossen sind, können nicht erneut gespielt werden.
Wenn ein Spiel abgeschlossen wurde, soll mit einem Klick auf "Open" eine Spielübersicht geöffnet werden.
Diese Übersicht enthält folgende zwei Bereiche:

**1. Übersichtsbereich**

Der Übersichtsbereich hat folgende Informationen augelistet:

- Name des Quizzes
- Zeitspanne der Verfügbarkeit (von wann bis wann ist das Spiel verfügbar)
- Anzahl der Fragen im Quiz
- Anzahl der richtig beantworteten Fragen

**2. Antwortbereich**
Im Antwortbereich soll eine Kompaktansicht aller Fragen erfolgen. 
Alle Fragen in dem Quiz werden untereinander angezeigt. 
Es soll zuerst die Frage angeführt sein.
Danach werden die Antwortmöglichkeiten aufgelistet. 
Die vom User gewählte Antwort wird unterstrichen.
Falls die Antwort richtig ist, wird diese in grüner Textfarbe angedruckt (und unterstrichen).
Sollte die vom User gewählte Antwort falsch sein, wird diese in roter Farbe gedruckt (und unterstrichen) sowie die korrekte Antwort in grüner Farbe markiert.
Die Fragen werden durch eine horizontale Linie voneinander getrennt.


# Leaderboard (3 Punkte)
Es soll ein neuer Menüpunkt hinzugefügt werden: Leaderboard.
Dieser Menüpunkt soll sowohl für alle sichbar sein (unabhängig davon ob ein User eingeloggt bzw. ausgeloggt ist). 
Das Leaderboard soll tabellarisch folgende Informationen über die ersten zehn Personen enthalten:

- Platzierung (1 bis 10)
- Name des Players
- Herkunft des Players
- Punkteanzahl

Die Platzierung bildet die Punkteanzahl - das heißt die Person mit den meisten Punkten soll den Platz 1 einnehmen, bis hin zum Platz 10. 

# Abgabe
Die Abgabe muss bis zur Deadline, am **4. Juni 2024, 23:59 Uhr** in dem gemeinsamen Github-Repository erfolgen
