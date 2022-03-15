Gesicherte Datenablage Server Client Anwendung
Eine gesicherte Datenablage für den Sicheren Austausch von Dateien.
Dabei wird die Privatsphäre der User und ein besonderes Augenmerk auf die Sicherheit gelegt. Die Anwendung soll Client und Serveranwendung basiert sein. 
Ein besonderes Augenmerk soll auf die Verschlüsselung gelegt werden. Zum einen werden die Daten Symmetrisch verschlüsselt, aber auch asymmetrische Verschlüsslung ist im Einsatz.
Jede Client Anwendung generiert einen symmetrischen Schlüssel bei der erst Initiation der Applikation.
Jeder User bekommt auch auf dem Server einen eigenen symmetrischen Schlüssel auf dem Server, welcher Die Daten ein zweites Mal verschlüsselt.
Die Authentifikation erfolgt über eine zwei Stufen Identifikation.
Der Token wird verwendet um den wechsel der SSL-keys zu initieren bei der übertragung der Dateien.

 
Bei der Arbeit wird nach IPERKA vorgegangen.

Information

Wie kann man Dateien Aufsplitten in Java?
Read line funktioniert bei grösseren Datein. Jedoch bei Dateien die kleiner sind wird es Probleme geben.

"Randomisierte" übertragung der Pakette und wieder zusammensetzung von diesen?


Wie können multiple SSL-Schlüssel verwendet werden und Server und Client benutzen die Selben?
Der Token wird zusamen mit der Zeit Gehasht und dabei kann man eine unterteilung generieren.
Der Token wurde vom Server Generiert und ist daher auf beiden Seiten vorhanden.


