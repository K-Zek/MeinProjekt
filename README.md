
1. Einrichtung des GitHub-Repository "MeinProjekt"
 -Einloggen in GitHub
 -Erstellen des Repositories durch klicken auf "+New" und Benennung (siehe Bild 1)
 
2. SHH-Schlüssel war bereits vorhanden (siehe Bild 2)

3. Lokales Klonen des Repositorys + Konfigurieren von Git + Erstellen der initialen Commits
 -Öffnen von Git Bash + Eingabe des Befehls "git clone git@github.com:K-Zek/MeinProjekt.git" zum klonen des Remote Reposietory
 -Konfigurieren von Git mit git config Behfehlen (Username und Useremailadresse)
 -Erstellen einer "main.py" Datei in main, das stagen dieser und anschließendem commiten (Initial commit) (siehe Bild 3)

4. Erstellen eines "feature"-Branches + Hinzufügen einer neuen Datei zu diesem Branch + Committen der Änderungen 
 -Erstellen eines Feature-Branches und wechsel zu diesem
 -Erstellen einer "utils" Ordners, einer "database.py" in dieser 
 -Stagen und Commiten von database.py
 -Hinzufügen  on Text in main.py
 -Stagen und commiten der Änderungen (siehe Bild 4)

5.Mergen des "feature"-Branches in den "master"-Branch + Beheben des dabei auftretenden Merge-Konflikts 
 -Wechsel zu main-Branch
 -Hinzufügen von Text in main.py (selber Text)
 -Stagen und commiten dieser 
 --> Recursive merge
 - Schließen des Editors (siehe Bild 5)
 
 -Wiederholen der Schritte 4 und 5 um einen Merge-Konflikt zu provozieren (siehe Bild 6)
-Behebung des Merge-Konflikts durch Zusammensetzen der Texte (siehe Bild 7 bis 10)
 