# WortUhr

## Was ist eine Wort Uhr?
Eine Wortuhr ist eine besondere Art von Uhr, die die Zeit nicht durch Ziffern oder Zeiger anzeigt, sondern in Form von Wörtern darstellt. Sie funktioniert typischerweise so, dass eine Matrix aus Buchstaben verwendet wird, und durch das Beleuchten bestimmter Buchstaben oder Wörter wird die aktuelle Uhrzeit in Klartext angezeigt. Ein Beispiel für eine Anzeige könnte sein:

<img width="800" alt="Screenshot" src="https://github.com/user-attachments/assets/fef14a0e-1e47-40e6-a330-9178eeebfdcb" />
<br><br>
Ich wollte mir aus einem alten Android Tablet (Google Nexus 7) eine Wortuhr bauen. Leider konnte ich keine passende App finden und so habe ich mir einfach selbst eine Wortuhr programmiert. Angezeigt wird die HTML-Datei über die App Fully Kiosk Browser, dieser kann das Tablet automatisch morgens einschalten und abends wieder ausschalten.<br><br>
<img width="800" alt="Screenshot" src="https://github.com/user-attachments/assets/d1c903d6-03f8-4a14-82a1-7aa2b5a64361"<br><br>

## Was macht die HTML-Datei?

Öffnet man die HTML-Datei mit einem Webbrowser startet die Wort Uhr.

## Was kann man einstellen?

| Eigenschaft                             | Wert                                   |
|-----------------------------------------|---------------------------------------|
| Abstand zur Oberkante                   | `height: 10%;`                        |
| Hintergrundfarbe                        | `background-color: black;`            |
| Schriftfarbe                            | `color: rgb(255, 255, 255);`          |
| Schriftart                              | `font-family: Arial Narrow, sans-serif;` |
| Schriftschnitt                          | `font-weight: light;`                 |
| Abstand zwischen den Buchstaben in %    | `gap: 1%;`                            |
| Schriftgröße in %                       | `font-size: 470%;`                    |
| Zeichenabstand Horizontal               | `width: 100%;`                        |
| Abdunkelung der nicht benötigten Wörter | `opacity: 0.2;`                       |
| Zeilenabstand                           | `line-height: 1.25;`                  |
| Abstand zwischen den Zeilen in %        | `--row-spacing: 8.6%;`                |



Falls die Textgröße nicht zur Bildschirmgröße passt, sollte als erstes im Browser die Zoomstufe angepasst werden. Dadurch kann das ändern im Programmcode evtl. gespart werden.<br>

Zu Debugzwecken lassen sich auch verschiedene Uhrzeiten testen:<br>

Debug einstellen&emsp;&emsp;&emsp;&emsp;```const useDebugTime = true;```<br>
Stunde einstellen&emsp;&emsp;&emsp;&emsp;```const debugHours = 11;```<br>
Minute einstellen&emsp;&emsp;&emsp;&emsp;```const debugMinutes = 23;```<br>
