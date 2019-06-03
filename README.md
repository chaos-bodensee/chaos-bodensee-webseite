[![Build Status](https://travis-ci.org/chaos-bodensee/chaos-bodensee-webseite.svg?branch=master)](https://travis-ci.org/chaos-bodensee/chaosbodensee-webseite)
![Chaos Bodensee](https://github.com/chaos-bodensee/chaosbodensee-grafik/blob/master/Chaos-Bodensee.svg "Chaos Bodensee")


Status
------------
Dies ist der Quellcode der zukünftigen Webseite des Chaos Bodensee.
Diese findet man derzeit nur hier...

 Lektor CMS:
------------
Das CMS für diese Webseite ist [Lektor](https://www.getlektor.com/).
Die Installationsanleitung gibt es [hier](https://www.getlektor.com/downloads/).
Lektor ist auch als Python Modul verfügbar und kann mit ``python2 -m lektor`` verwendet werden.
Auch die Installation über pip *(in einem [virtuellen Enviroment](https://docs.python.org/3/tutorial/venv.html)* ist möglich:
```bash
virtualenv venv
. venv/bin/activate
pip install lektor
```

Zum Starten von Lektor muss man mit der Komandozeile in das root Verzeichnis der Webseite gehen
und dort mit dem Befehl ``lektor server`` startet man Lektor und öffnen auf 127.0.0.1 den Port 5000 über den die Webseite
bearbeitbar ist. Die Versionskontrolle der Webseite findet über Git statt. Daher wenn möglich Bilder erst
bearbeiten, bevor diese Veröffentlicht werden!


 Zur neuen Webseite Beitragen:
------------------------
 1. Dieses Repository Forken oder einen neuen Branch machen (übers GitHub Interface)
 2. Geforktes Repository Clonen (``git clone https://github.com/<Your_Name>/chaosbodensee-webseite.git``)
 3. Öffne deine Komandozeile im geklonten Repository-Fork (``cd chaosbodensee-webseite``)
 4. Lektor starten (``lektor server``)
 5. Webseite updaten... (``http://localhost:5000/``)
 6. Lektor Beenden (``Strg. + C``)
 7. Änderungen commiten (``git add --all; git commit -m "An der Chaos Bodensee Webseite habe ich _____ geändert"``)
 8. Änderungen hochladen (``git push``)
 9. Pull-Request Stellen (übers GitHub Interface)

 Große Dateien und Grafiken
----------------------------
Für den besseren Umgang mit größeren Dateien haben wir angefangen auf git-lfs zu setzen. Weitere Informationen dazu finden sich auf [git-lfs.github.com](https://git-lfs.github.com/). 

Kurzfassung: Ihr solltet mit eurem Packet Manager ``git-lfs`` installieren. Dann funktioniert das in der regel relativ gut!



