# Python and Database

## Python

### Einstieg

#### Einrichtung der Python Entwicklungsumgebung

Als Entwicklungsumgebung kann MS Visual Studio Code (direkter Download aus dem Internet) oder MS Visual Studio (Unternehmensportal - kostenpflichtig, daher Abklärung mit Führungskraft) verwendet werden.  

*Anmerkung:  
In diesem Skript wird ausschließlich auf die Nutzung von MS Visual Studio Code eingegangen!*

#### I. Installation von Python 3.13.2

Man benötigt lokale Adminrechte zur Installation - diese sollten (Stand. 02.2025) mit dem Tool  

![BeyondTrust](images/beyondtrust.png) *BeyondTrust Privilege Management*  

ohne weitere Maßnahmen möglich sein.  
Bei der Installation sind folgende Haken zu setzen:  

![Python Installation](images/python_installation_01.png)

<div style="page-break-before: always;"></div>

Zum Testen der Installation folgenden Befehl in einer *PowerShell* eingeben:  

```
python.exe --version
```

Es sollte folgende Ausgabe erscheinen:  
![Python Version](images/python_installation_test.png)

#### II. Visual Studio Code Einrichtung

**Installation**  
Die Installation von VS Code ist mit Standardeinstellungen möglich. Nach erfolgreicher Installation startet man das Programm und fügt benötigte Extensions hinzu.

**Extension(s)**

- *Python* Extension von Microsoft:  

    ![Python Extension](images/Extension_Python.png)

<div style="page-break-before: always;"></div>

#### III. Einrichtung der Softwareverwaltung mit git

Git kann über das Unternehmensportal installiert werden.  

Zur Kontrolle, wie git konfiguriert ist, gibt man folgenden Befehl in eine PowerShell ein:  
    
    git config --global --edit

Daraufhin öffnet sich der Standard Editor und zeigt die Datei *.gitconfig* an.  
Dort muss ein Eintrag stehen, der folgende Informationen beinhaltet:  

    [user]
	name = <BENUTZERNAME>
	email = <BENTUZEREMAIL>@<DOMANE>

### Programmieren mit Python
