# GitHub mit TortoiseGit nutzen

Installationsanweisungen: http://code.google.com/p/tortoisegit/

## Repository anlegen
Als erstes muss ein Repository (MYREPO) auf GitHub (https://github.com/new) erzeugt werden. Dieses ist in ein lokales Arbeitsverzeichnis zu klonen:
* Erstelle lokales Verzeichnis (z.B. D:\repo\myrepo\)
* Rechtsklick auf das Verzeichnis
  * Git Clone
  * URL: https://github.com/MYUSERNAME/MYREPO
  * Fertig

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