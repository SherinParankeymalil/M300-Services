<h1> Dokumentation M300 
<h2> LB2 - Plattformübergreifende Dienste im Netzwerk integrieren

### Inhaltsverzeichnis
- [1. Auftrag](#1-auftrag)
- [2. Aktueller allgemeiner Wissensstand](#2-aktueller-allgemeiner-wissensstand)
  - [2.1 Virtualisierung](#21-virtualisierung)
  - [2.2 Vagrant](#22-vagrant)
  - [2.3 GIT](#23-git)
  - [2.4 MarkDown](#24-markdown)
  - [2.5 Sicherheit](#25-sicherheit)
- [3. Gelerntes](#3-gelerntes)
  - [3.1 Virtualisierung](#31-virtualisierung)
  - [3.2 Vagrant](#32-vagrant)
  - [3.3 GIT](#33-git)
  - [3.4 MarkDown](#34-markdown)
- [4. Projekt Vargrant](#4-projekt-vargrant)
  - [4.1 Vagrantfile](#41-vagrantfile)
  - [4.2 Vagrantbefehle](#42-vagrantbefehle)
- [5. Sicherheitsaspekte implementieren](#5-sicherheitsaspekte-implementieren)
  - [5.1 Sicherheitsmassnahmen](#51-sicherheitsmassnahmen)
- [6. Reflexion](#6-reflexion)

## 1. Auftrag 
   
Mittels Vagrant muss eine VM aufgsetzt werden. Dabei sollten (oben aufgelistete) Aufgaben erfüllt werden. 


## 2. Aktueller allgemeiner Wissensstand 
   
Mein Wissenstand bezüglich der unten gennanten Punkten, zum Beginn des Projektes wird erläutert:  

### 2.1 Virtualisierung
Darunter wird verstanden, dass physische hardwarebasierte Komponenten als softwarebasierte virtuelle Komponenten "ummodelliert" werden. Was in diesem Modul und generell in der zukünftigen IT Umgebung eine zentrale Rolle spielt.
Bisher hatte ich in der Arbeit, sowie in der Schule viel damit zu tun.   

###  2.2 Vagrant
Ist ein Programm zur Erstellung, Verwaltung und Automatisierung von virtuellen Maschinen.   

### 2.3 GIT
Ist eine Versionsverwaltungssoftware, welche ich bei einem anderen Script Modul bereits etwas kennengelernt habe.

### 2.4 MarkDown
Bisher habe ich diese Software nicht verwendet. 
Es ist eine Sprache, welche zur Erstellung der Dokumentation benötigt wird. 

### 2.5 Sicherheit
Ist in der IT jederzeit ein wichtiger Aspekt und muss in der virutellen Umgebung genau definiert und umgesetzt werden. Hier sind Zugriffe (besonders Remote), Berechtigungen und Verbindungen besonders wichtig. 


## 3. Gelerntes
Hier wird das neu Erlernte beschrieben: 

### 3.1 Virtualisierung
Ich konnte meine Kentnisse erweitern, bezüglich der Automatisierten Erstellung einer virutellen Maschine über Vagrant. Auch das Arbeiten über die Kommandozeile mit  Vagrant Befehlen, war etwas Neues und Lehrreiches. Auch die einzelnen Aufgaben mit 

### 3.2 Vagrant
Da ich nie zuvor mit Vagrant gearbeitet habe, ist dies ein völlig neues Gebiet für mich. Intressant fand ich die Erstellung eines VM über Kommandozeile/Vagrantfile und die Vagrant Befehle. Mit Vagrant zu arbeiten, da es mir völlig unbekannt war, war mühsam aber für zukünftige Arbeiten eine sehr hilfreiche Erfahrung. 

### 3.3 GIT 
Ich wusste nicht, dass man in der GitHub Repository verschiedenste Dokumente und Anderes (SSH Key) hinterlegen konnte. Git zu erkunden hat Spass gemacht. 

### 3.4 MarkDown
Anfangs hatte ich Mühe mit MD zu arbeiten. Ich mus§ste mich über das Internet bezüglich der korrekten Beschriftung und Formatierung informiere§n, was mir am meisten Mühe bereitet hat. Das Verständnis für eine MD Doku. Wenn man die Funktionen verstanden hat, fällt es einem leichter damit zu arbeiten. Auch die Dokument Vorschau ist hilfreich, um zu sehen wie sich das Dokument danach umsetzt. Ich weiss nun, dass MarkDown eine vereinfachte Version zur Erstellung von HTML Dokumenten ist.

## 4. Projekt Vargrant
Meine VM ist eine Ubuntu 16.04 Umgebung mit apache2 Installation.

### 4.1 Vagrantfile
Wurde separat hochgeladen. 


### 4.2 Vagrantbefehle
Einige der wichtigen oder viel benötigten Befehle werden hier aufgelistet:

    + vagrant up / down = startet oder fährt entsprechende VM herunter
    + create (cloud) = erstellt neuer Container Eintrag
    + update (cloud) = aktualisiert den Container mit entsprechenden gewünschten Optionen
    + push / pull = ladet Datei hoch oder herunter
    + force = keine erneute Bestätigung notwendig
    + whoami = valiidiert der Cloud Token und gibt den zugehörigen User aus
    + status = zeigt den Status der Maschine an
    + ssh = baut eine ssh Verbindung zur VM auf
    + destroy = stoppt die VM und "zerstört"/löscht alle benötigten Prozesse für die Erstellung der VM 


## 5. Sicherheitsaspekte implementieren
Eine ufw Firewall wurde installiert und entsprechende Firewall Rules eingerichtet. Der Zugang wurde über SSH Key Tunnel gesichert.  

### 5.1 Sicherheitsmassnahmen
    * entsprechende FW Rules wurden definiert
    * Benutzerrechte und Zugriffe sind korrekt vergeben 
    --> Authentifizierung und Autorisierung
    * Zugang via SSH 


## 6. Reflexion
Durch diesen Auftrag konnte ich viel Neues über die Virtualisierung lernen. Vorallem über die automatisierte Erstellung von VMs und Cloud. Die Programme; Vagrant, GitHub und das MarkDown, konnte ich neu für mich entdecken. 











