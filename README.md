# **EK HTTP Server**

Martin Simov

16.1.2024

## **Einführung**

Dieses Projekt implementiert einen einfachen HTTP-Server auf einem Arduino mit Hilfe eines Ultraschallsensors. Der Server gibt die gemessene Distanz in Zentimetern als HTTP-Antwort zurück. Dies kann beispielsweise für eine Einparkhilfe genutzt werden.

## **Projektbeschreibung**

Das Projekt verwendet einen Ultraschallsensor, um die Entfernung zu einem Objekt zu messen. Ein Arduino-Board mit WiFi-Modul wird als Server eingesetzt. Der Server erfasst die Distanz und gibt diese Informationen über eine HTTP-Anfrage zurück. Die Informationen können dann auf einer Webseite angezeigt werden.

## **Theorie**

Der Ultraschallsensor sendet einen Schallimpuls aus und misst die Zeit, die der Impuls benötigt, um vom Objekt zurückzukehren. Die gemessene Zeit wird verwendet, um die Distanz zum Objekt zu berechnen.

## **Arbeitsschritt**

Der Code liest die gemessene Distanz vom Ultraschallsensor aus und gibt diese Informationen über eine einfache HTML-Seite zurück. Der Server wird auf dem Arduino gestartet, der mit dem WLAN verbunden ist. Die HTML-Antwort enthält die gemessene Distanz und wird alle Sekunde aktualisiert, um kontinuierliche Messungen anzuzeigen.

## **Zusammenfassung**

Das Arduino-Programm implementiert einen einfachen HTTP-Server, der die Distanz von einem Ultraschallsensor misst und diese Information über eine HTML-Seite zurückgibt. Das Projekt könnte für Anwendungen wie eine Einparkhilfe verwendet werden.

## **Quellen**

https://www.youtube.com/watch?v=ApGwxX6VVzk
https://forum.arduino.cc/t/http-request-esp32-to-local-ip/1119294
