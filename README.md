# Stundenprotokoll

[1. Dienstag, 13. August 2019](#1)

[2. Mittwoch, 14. August 2019](#2)

[3. Donnerstag, 15. August 2019](#3)

[4. Dienstag, 20. August 2019](#4)

[5. Mittwoch, 21. August 2019](#5) 

[6. Donnerstag, 22. August 2019](#6)

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

### <a name="5"></a> Mittwoch, 21. August 2019
Heute beschäftigten wir uns wieder etwas mit GitHub, denn wir wollten den gestern erstellten Code in das Protokoll von gestern einfügen. Dazu mussten wir den Screenshot davon, den wir auf dem Desktop gepeichert hatten, auf GitHub hochladen. Es gibt dafür die Funktion "Upload files". Anschließend konnten wir den somit erstellten Link des Bildes kopieren und in dieser Datei einfügen.

Außerdem wollten wir etwas konkretere Projektplanungen entwickeln und recherchierten ein wenig über mögliche Projekte. Zu vielen möglichen Projekten gibt es allerdings sehr detaillierte Anleitungen im Internet und wir würden gerne etwas eigenes machen. Also gibt es nun die Überlegungen über zum Beispiel einen Kran oder einen Leuchtturm mit speziellen Fähigkeiten.

### <a name="6"></a>Donnerstag, 22. August 2019

Nach weiteren Überelegungen hatten wir dann die Ideee ein Parkhaus zu entwerfen und zu programmieren. Der Vorteil daran ist, dass wir immer nur kleine Projekte nachheinander haben und wenn dann mal eines nicht funktioniert, ist nicht gleich das ganze Projekt gescheitert. Unser erster Schritt ist die Schranke. Deshalb war dann das Thema für diese Stunde der Servomotor. Zuerst haben wir recherchiert worauf man beim Softare-Programmieren achten sollte und uns dann mit der Hardware auseinandergesetzt. Wir haben eine leicht verständliche Anleitung gefunden und diese einfach mal umgesetzt.

https://funduino.de/nr-12-servo-ansteuern

![2. Sketch](https://github.com/dennis602/Dennis/blob/master/sketch%20servo.PNG?raw=true)


Am Ende der Stunde hat sich dann nach einen Komplikationen und falsch verbundenen Kabeln der Motor bewegt. Ein erster Schritt zum Parkhaus
