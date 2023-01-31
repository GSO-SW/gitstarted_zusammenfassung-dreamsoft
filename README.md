# git Zusammenfassung
In dieser Readme.md soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.  Sie dürfen die gesamte Datei verändern (Sie dürfen alle vorhandenen Text entfernen). **Schaffen Sie eine gute Lerngrundlage bzw. ein Nachschlagewerk!**


:dart: Ziele:
- Programmieralltag simulieren
  - **nicht** im Browser arbeiten
  - Clonen Sie das Repo (url ist in der Adressezeile) und arbeiten Sie lokal
  - .md-Dateien können mit jedem Texteditor geöffnet werden
- Training des Teamworks: 
  - bearbeiten Sie nur die Datei Readme.md (keine Unterordner, keine weiteren Dateien etc.)
  - häufige commits
  - häufiges pushen/pullen
  - eigene Branches
    - lokal einrichten, anschließend pushen
    - auf github einrichten, anschließend pullen und auschecken
- Markdown kennenlernen
  - Markdown-Dateien (.md) enthalten eine einfache Syntax zur Formatierung von Texten. Dateien namens `readme.md` werden von GitHub automatisch auf der Startseite eines Repositorys angezeigt. [Mehr Infos zu Markdown](https://oliverbrux.de/blog/markdown-was-ist-das-eigentlich)
  - In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
  - Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

## offene Fragen
Listen Sie hier Ihre offenen Fragen, Unklarheiten, Wünsche etc. auf.
- ...
- ...

## TODO
Inspiration, was man hier alles eintragen könnte
- Begriffe definieren und erklären (z.B. repository, branch, Umgang mit merge-Konflikten etc.)
- git Befehle für die Arbeit mit lokalen Repositories auflisten (z.B. `git init` bis `git merge --abort`)
- git Befehle für die Arbeit mit entfernten Repositories auflisten (z.B. `git clone` bis `$ git push --set-upstream origin/develop`)
-
# Git Befehle

Git init: Mit dem Befehl git init wird ein neues Git-Repository erstellt.
Er kann zur Konvertierung eines bestehenden, nicht versionierten Projekts in ein Git-Repository oder zum Initialisieren eines neuen, 
leeren Repositorys genutzt werden.

Git status: Der Befehl git status gibt den Status des Arbeitsverzeichnisse und der Staging Umgebung zurück.
So kannst du sehen, welche Änderungen sich in der Staging-Umgebung befinden, welche nicht und welche Datein nicht von Git verfolgt werden.

Git log: Der Befehl git log listet die Historie der Commits eines Projektes in umgekehrter chronologischer Reihenfolge auf,
wenn man ihn ohne weitere Argumente ausführt, dass heißt die letzten Commits stehen oben.
