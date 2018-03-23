# M300_LB1

## Service Beschreibung:
Auf einem Ubuntu Server ein Wordpress installieren.
Benötigte Sotware: Apache, Mysql, PHP + Wordpress

## Installation:
Über das Vagrantfile wird die Virtuelle Maschine installiert.
In der Vagrant shell wird das Skript "script.sh" ausgeführt.
Dieses Skript installiert Apache, Mysql, PHP und Wordpress. Dabei wird auch das Tastaturlayout auf Schweizerdeutsch gestellt.

Das Skript erstellt den **Benutzer: svewer** mit dem **Passwort: sve_wer1**

Das Skript erstellt **die Datenbank: wordpress** und den **Datenbankbenutzer: wordpressuser** mit dem **Passwort: password**

**Achtung! : Die Datei shell.sh muss sich im gleichen Verzeichnis befinden wie das Vagrantfile.**

## Testen:
Das Wordpress sollte auf der Hostmaschine über folgende URL aufgerufen werden: http://localhost:8080
Die Setup Konfiguration von Wordpress soll erscheinen.

![wordpress](https://github.com/xxSvenxx/M300_LB1/blob/master/wordpress.PNG)

Dem Benutzer sollte es auch möglich sein, die Wordpress Seite anzupassen.
