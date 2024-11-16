#SEW_ProbeTest-01

#Flower Processing 

In diesem Programm zeichnen wir eine Blume in Processing. Ähnlich wie der Baum in den vergangenen Unterrichtseinheiten?

Ja! Dieser Algorithmus funktioniert ähnlich. Die Blüten der Blume werden mittels Rekursion gezeichnet. Der Stängel lässt sich mithilfe eines bestimmten Kommandos zeichnen. Wichtige bzw. unbekannte Kommandos funktionieren folgendermaßen:

fullScreen() – Aufruf in der SETTINGS Methode. Wichtig ist, dass das size() Kommando entfernt wird. Mittels „Esc“ kann man das Fullscreen-Fenster wieder verlassen.

curve() – Zeichnen des Stängels. Diese Methode benötigt 8 Parameter: (Kontrollpunkt x1, Kontrollpunkt y1, Punkt x2, Punkt y2, Punkt x3, Punkt y3, Kontrollpunkt x4, Kontrollpunkt y4)

Ellipse () – Zeichnen der Blüten. Diese Methode benötigt 4 Parameter:
(Punkt x, Punk y, Durchmesser 1, Durchmesser 2)

Die restlichen Codefragmente sollten bereits bekannt sein. Hinweis: Stellen Sie die Bildwiederholungsrate auf 1, um die Anzahl der neuen Blumengenerierung zu vermindern. An folgender Ausgabe können Sie sich orientieren: 
![image](https://github.com/user-attachments/assets/444978f1-2f13-48fc-bff1-844c91e5841c)

Folgende mathematischen Zusammenhänge können hilfreich sein:

![image](https://github.com/user-attachments/assets/54cf3678-9f8c-4df7-9ac3-d4b1ab863011)


#SortAndSearch 
In diesem Programm gibt der Benutzer Zahlen im Intervall [1;25] ein. Dabei beträgt das Maximum 10 Zahlen. Während der Eingabe kann die Eingabe jedoch jederzeit mit der Eingabe einer 0 abgebrochen werden. Wichtig ist auch, dass jede Zahl eindeutig ist und nicht doppelt vorkommt. Gehe dazu folgendermaßen vor:

Eingabe des Benutzers (z.B. 9)
Suchen der Zahl im Array mittels binärer Suche (Prüfen auf Duplikate)
Prüfen auf gültigen Bereich
Alles gültig -> speichern im Array
Sortiere das Array mithilfe eines Insertion-Sort Nach der Eingabe soll das sortierte Array ausgegeben werden (Nullen sind nicht auszugeben). Zusätzlich soll der Benutzer erfahren, welche Zahlen gerade und welche ungerade sind. Gib jeweils auch die Anzahl der gerade- bzw. der ungeraden Zahlen aus. Wichtig ist, dass sie auf die unten angefügte Ausgabe achten und versuchen diese möglichst äquivalent nachzustellen.
Ausgabe: Geben Sie 10 Zahlen im Bereich [1,25] ein (0 für Abbruch der Eingabe):

Zahl 1: 23 Zahl 2: 40 Ungültige Eingabe! Zahl 2: 2 Zahl 3: 23 Ungültige Eingabe! Zahl 3: 5 Zahl 4: 7 Zahl 5: 16 Zahl 6: 13 Zahl 7: 0

Sortiert: 2, 5, 7, 13, 16, 23,

Gerade Zahlen: 2, 16, Anzahl: 2

Ungerade Zahlen: 5, 7, 13, 23, Anzahl: 4
