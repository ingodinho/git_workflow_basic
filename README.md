# Workflow für die Arbeit mit Git/Github

Dies ist eine Schritt-für-Schritt-Anleitung für einen einfachen Workflow in der Arbeit mit Git in Verbindung mit Github. Dieser Workflow ist für kleine Projekte als einzelner Entwickler gedacht.


## Schritt 1: Lokales Repository einrichten

1. Erstelle/Initialisiere mit dem Befehl `git init` ein lokals Repository in deinem Projektordner

## Schritt 2: Arbeit durchführen/Änderungen vornehmen 

1. Führe deine Änderungen am Code oder den Dateien aus.
2. Füge die geänderten Dateien zum Commit hinzu: `git add <file-name>` (oder verwende `git add .`, um alle geänderten Dateien hinzuzufügen).
3. Mache einen Commit mit einer aussagekräftigen Beschreibung: `git commit -m "<Beschreibung der Änderungen>"`.

## Schritt 3: Remote Repository erstellen und einrichten

1. Erstelle ein neues Repository auf Github

## Schritt 4: Lokales Repository mit Remote-Repository (Github) verbinden
Die folgenden Schritte werden auf der Seite von Github nach Erstellung eines Repositories auch zum kopieren angezeigt:

1. Das remote repository lokal hinzufügen: `git remote add orgin <github-link>`
2. Den Hauptbranch umbenennen (ist eine konvention): `git branch -M main`
3. Die Änderungen aus Schritt 2 hochladen: `git push -u origin main`

## Schritt 5: Weitere Arbeiten durchführen
Nachdem Schritt 4 einmal erfolgreich durchgeführt worden ist, wiederholen wir bei nachfolgenden Änderungen nur noch Folgendes:

1. Die Punkte wie in Schritt 2 angegeben.
2. Die neuesten Änderungen wieder hochladen: `git push` oder in Langform `git push orgin main`

## Schritt 6: Veröffentlichen einer Seite

1. Gehe in deinem Repository auf den Tab "Settings".
2. Klicke links in der Menüleiste (Code and Automation) auf "Pages".
3. Bei "Build and deployment", sollte "Source" ausgewählt sein.
4. Wähle dann deinen branch aus. (Ist in der Regel main.)
5. Klicke auf "Save".
6. Nun kann es ein paar Minuten dauern, bis oben auf der Seite "Your site is life..." erscheint.
7. Der Link führt dich auf die deployte Seite. 
