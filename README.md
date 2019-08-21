# Stundenprotokoll

[1. Dienstag, 13. August 2019](#1)

[2. Mittwoch, 14. August 2019](#2)

[3. Donnerstag, 15. August 2019](#3)

[4. Dienstag, 20. August 2019](#4)


### <a name="1"></a>Dienstag, 13. August 2019
Herr Buhl stellte uns einige Optionen für Projekte und verschiedene Vorkenntnisgruppen vor. Da wir beide keine Vorkenntnisse besitzen hatten wir beide Lust, das Programmieren an etwas Praktischem zu erlernen. Deshalb wollten wir für unser Projekt einen Arduino verwenden. 

Herr Buhl stellte uns außerdem GitHub vor. Ein Programm, auf dem wir Stundenprotokoll führen und eine Projektseite für unser Halbjahresprojekt anlegen sollen. Anschließend sahen wir uns einige Projekte des letzten Jahrgangs an, um mögliche Ideen zu finden.

### <a name="2"></a> Mittwoch, 14. August 2019
Heute hatten wir die konkrete Aufgabe, einen GitHub Account zu erstellen und uns etwas mit dem Programm vertraut zu machen. Also haben wir einen Account erstellt und angefangen, das Protokoll zu verfassen. Hilfe für den Umgang mit GitHub bekamen wir, indem wir den Text von Herrn Buhl öffneten und auf "Raw" stellten.

### <a name="3"></a> Donnerstag, 15. August 2019
Heute haben wir angefangen, uns mit Arduino auseinanderzusetzen, um erste Grundkenntnisse zu erlangen. Wir wollten sowohl Soft- als auch Hardware und das Verbinden der beiden verstehen.

https://funduino.de/anleitung#1Vorwort_zur_Arduino_Anleitung

Wir haben uns mit der Hardware, also dem Controller und dem Breadboard auseinandergesetzt. Zum Beispiel, welche Kontakte auf dem Breadboard verbunden sind und wie man eine LED anschließt. Dort haben wir zum Beispiel gelernt, dass der lange Kontakt einer LED der Plus- und der kurze Kontakt der Minuskontakt ist oder, dass die Stelle Strom abgibt, die als Ausgang definiert ist.

### <a name="4"></a> Dienstag, 20. August 2019
Heute haben wir die ersten praktischen Schritte mit dem Arduino gemacht. Zuerst laßen wir uns mit dem Link von letzter Woche (s. [3. Donnerstag, 15. August 2019](#3)) zum Thema LED anschließen und einen einfachen Sketch programmieren ein. Zum korrekten Anschließen der LED an das Breadboard nahmen wir auch ein Video zur Hilfe.

https://www.youtube.com/watch?v=G4ZlfsbDtQo

Wir erstellten zuerst den Sketch, den wir dann auf den Arduino übertrugen.

![1. Sketch](https://github.com/dennis602/Dennis/blob/master/1.%20Sketch.PNG)


Wir mussten angeben, welcher Pin des Controllers als Output fungieren soll, also, wo eine Spannung abgegeben wird. Wir nahmen Pin 13 und führten von der gleichen Zeile auf dem Breadboard den Widerstand auf eine weitere Zeile. In dieser Zeile schlossen wir nun die Anode (längerer Kontakt) der LED an, schlossen die Kathode in eine weitere Zeile und führten von dort ein Kabel wieder zurück zum Controller in den GND Eingang. 

digitalWrite(...) --> Befehl, wie HIGH oder LOW
delay(...) --> Befehl, das der Zustand für eine Anzahl an Millisekunden so bleibt.

Wir brachten also heute die LED zum Blinken. Außderdem haben wir durch das Nacheinanderschreiben der Befehle ein SOS-Signal programmiert.
