# Muellkalender_EPaper
In diesem Projekt wird die Baugruppe "M5PAPER" für die Anzeige eines Müllkalenders genutzt. Die Baugruppe ist ein E-Paper Display mit eingebauten ESP32 Microcontroller und wird von der Firma "M5Stack" produziert und vertrieben. Der Müllkalender kann gleichzeitig maximal für zwei Müllarten den Termin der Entleerung anzeigen. Die Daten werden mit Hilfe von MQTT aus einer IO_Broker Instanz ausgelesen. Die Anzeige des Displays wird alle 24 Stunden aktualisiert. Die Baugruppe ist mit einem Accu ausgestattet. Die Laufzeit reicht für ca. 3 Monate.
Der Programmcode wurde mit dem Web-Tool "M5Flow" erstellt und mit dem Programm "M5Burner" auf die Baugruppe übertragen.
![IMG_1335](https://user-images.githubusercontent.com/57326906/209949655-e5a1dccc-578e-4481-b076-21c016ce607d.jpg)
![M5Flow_Screenshot](https://user-images.githubusercontent.com/57326906/210062255-67ab6a86-dc85-4c89-bcb7-5fa8256e61c4.jpg)
