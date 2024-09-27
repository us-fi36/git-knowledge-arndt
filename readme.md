# Git Wissensspeicher


## Git Befehle

### git init
Initialisiert ein neues Git-Repository.  
<pre>git init -b <i>Branchname</i> // Benennt die erste Branch (Standart: main)</pre>  
  
  
### git status
Gibt den aktuellen Status des Repository wieder, zeigt Änderungen in der Staging-Area und die aktuelle Branch an.  
  
  
### git add
Verschiebt Änderungen in die Staging-Area, wodurch sie vom nächsten commit behandelt werden können.  
<pre>git add . // Verschiebt alle Änderungen in die Staging-Area
git add <i>Dateiname</i> // Verschiebt die benannte Datei</pre>   
  
  
### git commit
Übernimmt alle Änderungen in der Staging-Area und fügt sie dem lokalen Repository hinzu.  
<pre>git commit -m <i>Kommentar</i> // Fügt den Commit-Kommentar direkt hinzu</pre>
  
  
### git clone
Lädt das angegebene Repository herunter (Zielverzeichnis optional).
  

### git remote
Management der Remote Repositories und deren aktuelle Verknüpfungen.
<pre>git remote add <i>Name Zieladresse</i> // Erstellt ein verknüpftes Repository am Ziel her (zB. github)  
git remote rename <i>alterName neuerName</i> // benennt um</pre>
  

### git rm
Entfernt Änderungen aus der Staging-Area. Dies ist das Gegenstück zu <i>git add</i> und hat dieselbe Syntax.


### git pull
Fordert den neuesten Stand der aktuellen Branch vom Remote-Repository an.
  
  
### git push
Aktualisiert das Remote-Repository, indem alle Commits übertragen werden.