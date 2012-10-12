# GitHub mit TortoiseGit unter Windows nutzen

Installationsanweisungen: http://code.google.com/p/tortoisegit/

Dokumentation: http://git-scm.com/documentation

## Globale Git Einstellung
Öffnet die Kommandozeile und tippt folgende Kommandos ein
```
git config --global user.name "YOUR GIT USERNAME"
git config --global user.email YOUR_GITHUB_EMAILADRESS
```

## Repository anlegen
Als erstes muss ein Repository (MYREPO) auf GitHub (https://github.com/new) erzeugt werden. Dieses ist in ein lokales Arbeitsverzeichnis zu klonen:
* Erstelle lokales Verzeichnis (z.B. D:\repo\myrepo\)
* Rechtsklick auf das Verzeichnis
  * Git Clone
    * URL: https://github.com/MYUSERNAME/MYREPO

## Lokale Arbeitskopie aktualisieren
* Rechtsklick auf das Verzeichnis
  * TortoiseGit -> Pull...
    * Remote: origin
    * Remote Branch: master
  
## Lokale Arbeitskopie commiten
* Rechtsklick auf das Verzeichnis
  * Git Commit -> "master"
* Rechtsklick auf das Verzeichnis
  * TortoiseGit -> Push...
    * Branch
      * Local: master
      * Remote: master
    * Destination
      * Remote: origin