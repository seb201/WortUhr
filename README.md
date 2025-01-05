# WortUhr

## Was ist eine Wort Uhr?
Eine Wortuhr ist eine besondere Art von Uhr, die die Zeit nicht durch Ziffern oder Zeiger anzeigt, sondern in Form von Wörtern darstellt. Sie funktioniert typischerweise so, dass eine Matrix aus Buchstaben verwendet wird, und durch das Beleuchten bestimmter Buchstaben oder Wörter wird die aktuelle Uhrzeit in Klartext angezeigt. Ein Beispiel für eine Anzeige könnte sein:

<img width="800" alt="Screenshot" src="https://github.com/user-attachments/assets/fef14a0e-1e47-40e6-a330-9178eeebfdcb" />

## Was macht die HTML-Datei?

Öffnet man die HTML-Datei mit einem Webbrowser startet die Wort Uhr.

## Was kann man einstellen?

In der HTML-Datei können verschiedene Einstellungen vorgenommen werden:<br>

Abstand zur Oberkante&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```height: 10%;```<br>
Hintergrundfarbe&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```background-color: black;```<br>
Schriftfarbe&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```color: rgb(255, 255, 255);```<br>
Schriftart&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```font-family: Arial Narrow, sans-serif;```<br>
Schriftschnitt&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```font-weight: light;```<br>
Abstand zwischen den Buchstaben in Prozent&emsp;```gap: 1%;```<br>
Schriftgröße in Prozent&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```font-size: 470%;```<br>
Zeichenabstand Horizontal&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;```width: 100%;```<br>
Abdunkelung der nicht benötigten Wörter&emsp;&emsp;&emsp;```opacity: 0.2;```<br><br>

Falls die Textgröße nicht zur Bildschirmgröße passt, sollte als erstes im Browser die Zoomstufe angepasst werden. Dadurch kann das ändern im Programmcode evtl. gespart werden.<br>

Zu Debugzwecken lassen sich auch verschiedene Uhrzeiten testen:<br>

Debug einstellen&emsp;&emsp;&emsp;&emsp;```const useDebugTime = true;```<br>
Stunde einstellen&emsp;&emsp;&emsp;&emsp;```const debugHours = 11;```<br>
Minute einstellen&emsp;&emsp;&emsp;&emsp;```const debugMinutes = 23;```<br>
