# Git Basics – Übersicht der wichtigsten Befehle

| Befehl | Beschreibung |
|--------|--------------|
| `git init` | Erstellt ein neues Git-Repository |
| `git status` | Überprüft Working Directory & Staging Area |
| `git add` | Fügt Dateien aus Working Directory zur Staging Area hinzu |
| `git diff` | Zeigt Unterschiede zwischen Working Directory & Staging Area |
| `git commit` | Speichert Änderungen dauerhaft im Repository |
| `git log` | Zeigt die Commit-Historie |
| `git show HEAD` | Zeigt den letzten Commit |
| `git checkout HEAD FILENAME` | Verwirft Änderungen an einer Datei |
| `git reset commit_SHA` | Setzt auf einen früheren Commit zurück |
| `git reset HEAD filename` | Entfernt Dateien aus der Staging Area |
| `git stash` | Speichert aktuellen Stand zwischen |
| `git stash pop` | Stellt letzten Stash wieder her |
| `git branch -a` | Zeigt alle Branches |
| `git branch BRANCHNAME` | Erstellt einen neuen Branch |
| `git log --oneline` | Kompakte Ausgabe der Commit-Liste |
| `git log -S "keyword"` | Suche nach Commits anhand eines Begriffs |
| `git log --oneline --graph` | Graphische Anzeige der Commit-Historie |
| `git commit --amend --no-edit` | Ändert letzten Commit ohne neue Nachricht |

---

## Git konfigurieren

```sh
git config --global user.name "NAME"
git config --global user.name
git config --global user.email "YOUR_EMAIL"

\

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kabusch940/git_practice.git
git push -u origin main