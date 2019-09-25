# Stundenprotokoll

[1. Dienstag, 13. August 2019](#1)

[2. Mittwoch, 14. August 2019](#2)

[3. Donnerstag, 15. August 2019](#3)

[4. Dienstag, 20. August 2019](#4)

[5. Mittwoch, 21. August 2019](#5) 

[6. Donnerstag, 22. August 2019](#6)

[7. Dienstag, 27. August 2019](#7)

[8. Mittwoch, 28, August 2019](#8)

[9. Donnerstag, 29. August 2019](#9)

[10. Dienstag, 10. September 2019](#10)

[11. Mittwoch, 11. September 2019](#11)

[12. Donnerstag, 12. September 2019](#12)

[13. Dienstag, 24. September 2019](#13)

[14. Mittwoch, 25. September 2019](#14)

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


Wir mussten angeben, welcher Pin des Controllers als Output fungieren soll, also, wo eine Spannung abgegeben wird. Wir nahmen Pin 13 und führten von der gleichen Zeile auf dem Breadboard den Widerstand auf eine weitere Zeile. In dieser Zeile schlossen wir nun die Anode (längerer Kontakt) der LED an, schlossen die Kathode in eine weitere Zeile und führten von dort ein Kabel wieder zurück zum Controller in den GND Eingang, um den Stromkreis zu schließen. 

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


Am Ende der Stunde hat sich dann nach einen Komplikationen und falsch verbundenen Kabeln der Motor bewegt. Ein erster Schritt zum Parkhaus.

### <a name="7"></a>Dienstag, 27. August 2019

Heute ging es darum, den Sketch von letzter Stunde noch einmal genau anzuschauen und zu verstehen. Das klappte problemlos, sodass wir ohne Schwierigkeiten ohne Anleitung das gleiche nocheinmal durchführen konnten. 

![Servo angesteuert](https://github.com/dennis602/Dennis/blob/master/IMG_20190827_124143%20(1).jpg?raw=true)

Somit machten wir den nächsten Schritt: Den Bewegungssensor, der die Schranke öffnen soll, wenn ein Fahrzeug vorbei fährt. Dazu lasen wir uns mit dem folgenden Link ein:

https://funduino.de/nr-8-bewegungsmelder

Wir wollten vorerst eine LED zum leuchten bringen, sobald eine Bewegung registriert wird. Also nutzen wir auch ein Breadboard, auf dem wir die LED wie am [4. Dienstag, 20. August 2019](#4) befestigten. Dann folgten wir der Anleitung, also versorgten wir den Sensor per 5V Anschluss des Arduinos mit Strom und schalteten einen Stromkreis so, dass der Arduino bei einem Siganl des Sensors die LED mit Strom versorgen kann. Welche Pins belegt werden, muss mit dem Sketch übereinstimmen. Da die Stunde schon fast zu Ende war, machten wir das alles sehr schnell. Es funktionierte aber direkt, also werden wir uns das ganze morgen erneut angucken.

![Bewegungsmelder LED](https://github.com/dennis602/Dennis/blob/master/Arduino%20Bewegungsmelder.jpg?raw=true)

Der nächste Schritt ist, ein Servo per Bewegungsmelder zu steuern.

### <a name="8"></a>Mittwoch, 28. August 2019
Anfangs haben wir den Aufbau der letzten Stunde wiederholt. Doch diese Stunde hatten wir das Ziel einen Servomotor mit dem Bewegungsmotor zu verbinden. Wir haben dann den gleichen Aufbau wie am [7. Dienstag, 27. August 2019](#7) genommen, nur die LED  auf dem Breadboard mit einem Servo ausgetauscht. Um zwei Geräte (Servo und Bewegungsmelder) per Arduino mit Strom zu versorgen, leiteten wir das 5V Kabel auf die + Seite des Breadboards, wo wir anschließend beide Geräte anschließen konnten. 

![Schaltung Servo mit Bewegungsmelder](https://github.com/dennis602/Dennis/blob/master/IMG_20190828_121518.jpg?raw=true)

Den Sketch haben  wir dann aus denen für den Bewegungsmelder und dem für den Servomotor zusammengesetzt. Der Sketch hat leider nicht funktioniert, doch weil die Stunde vorbei war, konnten wir ihn nicht reparieren.


### <a name="9"></a>Donnerstag, 29. August 2019
Heute probierten wir das Problem von gestern zu lösen. Wir nahmen den gleichen Ansatz, und zwar zwei funktionierende Sketche kombinieren. Wir schauten uns also die Sketche zum Bewegen eines Servomotors an und den zum Aufleuchten einer LED per Bewegungsmelder. Nach einigen Fehlermeldungen konnten wir mit Hilfe von Herrn Buhl den Sketch fehlerfrei kriegen. 

![Sketch Servo-Bewegungsmelder](https://github.com/dennis602/Dennis/blob/master/sketch_servo_bewegungsmelder_29.08.19.PNG?raw=true)

Es funktionierte leider nicht ganz wie gewünscht. Der Servo bewegte sich zwar nach der Registrierung, jedoch nicht nach der im " delay(...) " angegebenen Zeit. Um dies zu überprüfen werden wir nächstes Mal das Ganze mit einer LED noch einmal testen, um den Fehler zu lösen. 



Die folgende Woche ist der Informatikunterricht ausgefallen.



### <a name="10"></a>Dienstag, 10. September 2019
Diese Stunde ist der Untrricht ebenfalls ausgefallen.

### <a name="11"></a>Mittwoch, 11. September 2019
Heute haben wir erneut einen Motor mit einem Bewegungsmelder verbunden und im Sketch nach unseren Fehlern gesucht, weil es noch nicht ganz funktioniert hat. Anstatt, dass der Motor auf Bewegung auf und dann nach einiger Zeit wieder zu geht, ging er in immer gleichen zeitlichen Abständen auf und zu. Um nach möglichen Fehlern zu suchen, haben wir an den Bewegungsmelder statt einen Motor eine LED gebaut und den alten funktionierenden Sketch genommen. Das hat wieder funktioniert und die Lampe ging auf Bewegung an, doch leider blieb sie länger an als wir wollten.

### <a name="12"></a>Donnerstag, 12. September 2019
Heute haben wir erneut einen Motor mit einem Bewegungsmaelder verbunden. Unser Problem mit der nicht zu kontrollierenden Zeit haben wir gelöst, wir konnten am Bewegungsmelder selbst ein Rad drehen und somit die Zeit verändern. In den Sketch haben wir mit der Hilfe von Herrn Buhl einen sogenannten serial Print eingefügt, der zeigt, an welcher Stelle des Programms der Code gerade ist und somit sehr viel mehr Überblick verschafft. Außerdem hat das reagieren des Motors auf Bewegung endlich geklappt. Wir können jetzt also einen Motor nur durch Bewegung steuern.
![Sketch Bewegungsmelder und servo mit serial Print](https://github.com/dennis602/Dennis/blob/master/servo_bewegung_funktioniert.PNG?raw=true)

Die folgende Woche waren wir auf Studienfahrt.

### <a name="13"></a>Dienstag, 24. September 2019
Als erstes überprüften wir, ob alles was wir uns letzte Stunde erarbeitet haben noch so funktioniert, wie es sollte. Alles hat geklappt und somit konnten wir uns Gedanken machen, wie es nun weiter geht. Unser gesamtes Ziel ist es ja, ein Parkhaaus mit einer Schranke zu haben, die aufgeht, sobald ein Auto vorbei fährt. Ist kein Parkplatz mehr frei, soll sie geschlossen bleiben. Dazu haben wir bis jetzt also die Schranke.
Um diesen Mechanismus zu unterbrechen, sobald das Parkhaus voll ist, wollen wir einen weiteren Sensor, und zwar einen Ultraschallsensor verwenden, der den Schrankenmechanismus unterbricht, sobald wenige Zentimeter vor ihm ein Objekt steht. Beginnen wollen wir wieder mit einer LED, um uns mit dem Sensor vertraut zu machen. Die Anleitung dazu haben wir bei iSurf unter den Arduino-Dokumenten gefunden und werden morgen damit starten. Die Hardware dafür haben wir heute schon herausgesucht.

### <a name="14"></a>Mittwoch, 25. September 2019
Heute fingen wir direkt an, den Sketch für den Ultraschallsensor zu entwickeln. Als Vorlage nutzten wir den Sketch aus den Arduino-Dokumenten, wie gestern beschrieben. Diesen passten wir an unsere Verkabelung an, indem wir die richtigen Pins als Input, Output und die Sensorpins richtig definierten. Anschließend haben wir mit unseren bisherigen Vorkenntnissen den Sketch etwas umgeschrieben und verändert, damit er funktioniert. Damit der Arduino den Abstand berechnen kann, mussten wir außerdem die entsprechene Formel einfügen, die wir im Internet gefunden haben.

https://www.mymakerstuff.de/2016/05/24/arduino-tutorial-der-ultraschallsensor/

Der funktionierende Sketch sah also folgendermaßen aus:

![Sketch Ultraschallsensor](https://github.com/dennis602/Dennis/blob/master/Sketch_Ultraschall_LED_funktioniert.PNG?raw=true)

Im void loop muss also angegeben werden, wie oft der Ultraschallsensor Signale aussenden soll.

Nun schalteten wir noch die Hardware über ein Breadboard, mit einer LED, die leuchtet, sobald sich 20 cm vor dem Ultraschallsensor etwas befindet. Alles hat funktioniert. 

![Aufbau 25.09.19](https://github.com/dennis602/Dennis/blob/master/Ultraschallsensor.jpg?raw=true)
