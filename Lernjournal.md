**D1 Verbesserungen**
1) [Eine nicht-initialisierte Variable führt bei der Ausführung zu einem Laufzeitfehler.] ist falsch ➞ Warum?   
   In Java gibt es eine Warnung und sollte deshalb initialisiert werden.
   
3) [Die Anzahl Bits in Java für den Datentyp char ist 8]  ist falsch ➞ Warum?   
Die Anzahl Bits ist 16.   

4) final double exchangeRate = 1.22;[Die Variable exchangeRate kann während der Laufzeit verändert werden .] ist falsch ➞ Warum?   
Weil "final" genau das verhindert und sagt, dass es Konstant ist.

5) [Bestimme geeigneter Datentyp zum Speicher von 2'200'500'000] ➞ Welche Datentypen sind möglich?   
"long", "float" und "double" sind geeignet, weil sie die Differenz zwischen der mind. und max. Zahl mehr als 2'200'500'000 beträgt (Wertebereich).

6) Was bedeutet i++? Was passiert mit dem Inhalt der Variable i?   
Abkürzung für + 1.


**A1 Verbesserungen**
1) Kann ein AD einen Aufruf auf ein anderes AD machen? (Funktionsaufruf)
   "Aktivität als Aufruf" ermöglichen, ein weiteres, separat definiertes AD auszuführen, d.h. aufzurufen.

2) Zeichnen Sie ein AD das folgenden Ablauf  aufzeigt:   
- Zwei Zahlen einlesen: a, b   
- * Aufruf Abstraktion: Multiplikation von a und -b bilden, B um 10 reduzieren und Resultat zurück geben   
- Resultat in d abspeichern   
- Wenn Differenz d grösser 0 ist, dann  d ausgeben und Programm beenden   
- sonst a und b tauschen (umspeichern) und zurück zu *   
