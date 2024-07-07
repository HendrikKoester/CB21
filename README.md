Repository klonen:
  Öffne ein Terminal (Git Bash, Command Prompt oder Terminal).
  Navigiere zu dem Ordner, in dem du das GitHub-Repository klonen möchtest:
    cd /pfad/zu/deinem/zielordner
  Klone das Repository mit dem folgenden Befehl:
    git clone https://github.com/dein-benutzername/dein-repo.git    (Ersetze https://github.com/dein-benutzername/dein-repo.git durch die URL deines GitHub-Repositories.)


Änderungen committen und pushen:
  Nachdem du deine Änderungen vorgenommen hast, öffne erneut dein Terminal und navigiere zu deinem geklonten Repository: 
    cd /pfad/zu/deinem/gekloenten/repo
  Überprüfe die Änderungen:
    git status
  Füge die geänderten Dateien hinzu:
    git add .
  Committe deine Änderungen:
    git commit -m "Beschreibung der Änderungen"
  Pushe deine Änderungen zu GitHub:
    git push origin main
    
