#  Installation der ToDo-App
## Schritt 1: Clonen des Repositories
Öffne den Terminal als Administrator und nutze den befehl `git clone <URL des Repositories>`.
## Schritt 2: Installation und Konfiguration von Docker
Du kannst Docker auf ![Dieser Website](https://docs.docker.com/get-started/get-docker) installieren.
## Initialisierung der Docker Assets
Nutze im Terminal den Command `cd docker-nodejs-sample`.
Danach, wenn du in deinem directory bist, tippe im Terminal `docker init` ein. 
Dir werden nach diesem Schritt einige Fragen gestellt, hier sind die antworten: 
>>`? What application platform does your project use? Node <br>
? What version of Node do you want to use? 18.0.0. <br>
? Which package manager do you want to use? npm. <br>
? What command do you want to use to start the app: node src/index.js. <br>
? What port does your server listen on? 3000. <br>
## Schritt 3 - Starte die Applikation
1. Gib im Terminal (wieder im Directory "docker-nodejs-sample") den `docker compose up --build` Befehl ein, um die Applikation zu Starten:
2. Der folgende [Link](http://localhost:3000) führt zu der Todo Applikation.
3. Wenn man die Applikation stoppen möchte, muss man im Terminal die Tastenkombination `ctrl + c` benutzen.
4. Um es ganz abzuschalten, muss man den Befehl `docker compose down`



