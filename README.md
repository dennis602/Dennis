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

[15. Donnerstag, 26. September 2019](#15)

[16. Dienstag, 01. Oktober 2019](#16)

[17. Mittwoch, 02. Oktober 2019](#17)

[18. Dienstag, 22. Oktober 2019](#18)

[19. Mittwoch, 23. Oktober 2019](#19)

[20. Donnerstag, 24. Oktober 2019](#20)


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

### <a name="15"></a>Donnerstag, 26. September 2019
Heute haben wir mit den LEDs und dem Ultraschallsensor noch etwas weiter gearbeitet, indem wir versucht haben, je nach Entfernung, verschiedene LEDs zum leuchten zu bringen. Also haben wir den Sketch von gestern weiter bearbeitet und noch zwei weitere "if" Befehle für zwei weitere LEDs eingefügt und die Hardware soweit angepasst. Da die Software Entfernungen wie (20<distance<30) nicht angenommen hat, wollten wir einfach, dass pro 10 cm eine LED mehr leuchtet und ab 40 cm keine mehr. 
Leider hat das alles nur mäßig gut funktioniert, manchmal gab es Probleme. Zum Beispiel, dass die LEDs gar nicht mehr ausgingen, sondern erst etwas später.
Um das nachzuvollziehen, könnten wir nächstes Mal noch einen Serial.Print einfügen, um den Status des Arduinos nachvollziehen zu können.

### <a name="16"></a>Dienstag, 01.Oktober 2019
Heute war die 12b auf Exkursion.


### <a name="17"></a>Mittwoch, 02.Oktober 2019

Heute wollten wir den funktionierenden Sketch für den Ultraschallsensor mit dem für den Bewegungsmelder/Servo verbinden. Hierzu haben  wir einfach den Ultraschall-Sketch in den Bewegungsmelder-Sketch eingefügt. Unser Ansatz waren mehrere "If" Bedingungen aneinandergereiht, um zu bewirken, dass der Bewegungsmelder-Servo-Sketch nur  funktioniert, wenn der Ultraschallsensor mehr als eine vorher definierte Entfernung misst. Um zu erkennen, was passiert haben wir einen serial print eingefügt. Das Programm Arduino hat den Sketch überprüft und angenommen. Laut Arduino gibt es in unserem Sketch keine Fehler. Leider hat es nicht funktioniert, wir vermuten einen Fehler in der Hardware. Trotzdem sind wir unserem Ziel, einen Servomotor, der durch Bewegegung gesteuert wird, mit einem Ultraschallsensor zu aktivieren oder zu deaktivieren ein großer Stück dichter gekommen.


### <a name="18"></a>Dienstag, 22.Oktober 2019

Heute war die erste Stunde nach den Herbstferien. Aus diesem Grund mussten wir uns auch erst wieder in das Thema einlesen und eindenken. Als nächstes haben wir einen neuen Ansatz verfolgt, um unser Problem von vor den Ferien zu lösen. Der neue Ansatz ist eine so genannte  "Do While" Schleife im Sketch. Diese befindet sich im Loop des Sketches. In den " Do" Teil haben wir die Anweiseungen für den Bewegungsmelder und den Servo geschrieben und in den "While" Teil die Bedingung, dass die Entfernung größer als 3cm sein muss. Gedacht war also, dass der "Do" Teil nur funktioniert, wenn der Ultraschallsensor eine Entfernung über 3cm feststellt. Leider hat auch dieser Ansatz noch nicht ganz funktioniert, der Servo hat sich zwar auf unsere Handbewegung hin bewegt, doch leider auch wenn ein Gegenstand dichter als 3cm am Ultraschallsensor war. Das sollte eigentlich nicht passieren.


### <a name="19"></a>Mittwoch, 23.Oktober 2019

Heute haben wir weiter probiert unseren Plan in die Tat umzusetzen. Zuerst haben wir eine "While" Schleife gemacht und in den While-Teil die Bedingung distance größer als 3cm eingefügt. Wir wollten, dass zuerst die Entfernung kontrolliert wird und nur wenn diese groß genug ist, also kein "Auto" vor dem Sensor steht, soll der Bewegungsmelder-Servo-Sketch aktiviert werden. Leider hat das nicht so funktioniert wie wir wollten. Danach haben wir nochmal den Ansatz mit mehreren If Bedingungen ausprobiert. Wir haben in der ersten If Bedingung die Entfernung geregelt und in der zweiten dann der Bewegungsmelder. Um einen Überlick zu erhalten haben wir einen Serialprint eingefügt. Und auf einmal hat alles funktioniert. der Servo reagiert auf Bewegung, aber nur wenn der Ultraschallsensor eine Entfernung über 3cm feststellt. Ein paar Kleinigkeiten ruckelten noch im Servo aber im großen und ganzen hat jetzt alles so funktioniert wie wir es wollten.

![Aufbau 23.10.19](https://github.com/dennis602/Dennis/blob/master/bild_23.10.19.jpg)


### <a name="20"></a>Donnerstag, 24.Oktober 2019

Heute haben wir zu dem funktionierenden Sketch von gestern noch LED´s eingebaut, um eine Ampel darzustellen. Eine grüne LED leuchtet, wenn der Parkplatz frei ist und eine rote LED leuchtet, wenn der Parkplatz besetzt ist. Dazu haben wir im Void Setup die pinModes für die LED´s angegeben und im Void Loop an entsprechender Stelle digitalWrite(pin, HIGH bzw. LOW) eingefügt. Alles hat funktioniert, sodass wir unseren Sketch ersteinmal fertig hätten. Nur einen Kritikpunkt gibt es: Misst der Ultraschallsensor eine Entfernung von unter 3 cm und der Bewegungsmelder nimmt eine Bewegung war, passiert nichts. Das soll auch so sein, doch ist direkt danach die Entfernung vor dem Ultraschallsensor wieder mehr als 3 cm, führt der Servo die Bewegung noch aus. Das ist jedoch unvermeidlich, da der Bewegungsmelder das Signal einer Bewegung eine Weile lang sendet, damit der Servo nicht direkt wieder zurück dreht. Wird also in dieser Zeit die Entfernung wieder größer, wird die Bewegung noch ausgeführt. Das lässt sich aber wiegesagt nicht vermeiden, ist aber auch kein Problem, gerade im Zusammenhang, wenn wir wirklich ein Parkhaus bauen. Dort geht dann also die Schranke auch nach Ankunft eines Autos noch auf, sobald der Parkplatz innerhalb von der Bewegungsmeldersendezeit wieder frei wird.

