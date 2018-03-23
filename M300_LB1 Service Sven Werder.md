# M300_LB1

**Service Beschreibung:**
Auf einem Ubuntu Server ein Wordpress installieren.
Benötigte Sotware: Apache, Mysql, PHP + Wordpress

**Installation:**
Über das Vagrantfile wird die Virtuelle Maschine installiert.
In der Vagrant shell wird das Skript script.sh ausgeführt.
Über dieses Skript wird Apache, Mysql, PHP und Wordpress installiert. Dabei wird auch das Tastaturlayout auf Schweizerdeutsch gestellt.

**Achtung! : Die Datei shell.sh muss sich im gleichen Verzeichnis befinden wie das Vagrantfile.**

**Testen:**
Das Wordpress sollte auf der Hostmaschine über folgende URL aufgerufen werden: http://localhost:8080
Die Setup Konfiguration von Wordpress soll erscheinen.
