# Mini-Projekt
# Mini-Projekt Docker Webserver

Dieses Projekt erstellt ein eigenes Docker Image mit NGINX und hostet eine einfache Webseite.

## Projektziel

- Webserver Container erstellen
- Webseite im Container ausführen
- Zugriff über Browser auf Port 8080
- Webseiten Dateien lokal speichern
- Logdateien lokal speichern

## Projektstruktur

mini-webserver-docker

Dockerfile -> erstellt das Image  
docker-compose.yml -> startet den Container  
website -> HTML und CSS Dateien  
logs -> Webserver Logs  

## Container starten

Im Projektordner ausführen:

docker compose up --build

## Webseite öffnen

http://localhost:8080

## Logs

Die Logdateien befinden sich im Ordner:

logs/
