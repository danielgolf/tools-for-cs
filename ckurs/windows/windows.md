## Windows

Auf dieser Seite stellen wir euch zwei Varianten vor wie ihr C unter Windows kompilieren könnt.
Das wäre einmal die Virtual Machines (VMs) und das Windows-Subsystem für Linux (WSL).
Der Vorteil von WSL ist, dass das Freigeben von Dateien, das Ausführen von Befehlen zwischen Windows und der WSL-Umgebung
quasi nahtlos passiert. Hinzukommt, dass es schnell startet.
Der Vorteil einer VM liegt darin, dass ein komplettes Betriebssystem simuliert wird, eine VM bringt ein komplettes 
[Graphic User Interface](https://de.wikipedia.org/wiki/Grafische_Benutzeroberfl%C3%A4che) (GUI) mit sich. 
Daraus ergeben sich auch direkt die Nachteile für beide Varianten, bei WSL fehlt eine GUI. Eine VM hingegen ist Ressourcen aufwendiger, 
da ein komplettes [Operating System](https://de.wikipedia.org/wiki/Betriebssystem) (OS) simuliert werden muss.

**TL;DR**


|           |            VM            |                                   WSL                                   |
|:---------:|:------------------------:|:-----------------------------------------------------------------------:|
|  Vorteile | - GUI<br>- komplettes OS | - viel weniger Ressourcen aufwendig<br>- direkte Gewöhnung ans Terminal |  
| Nachteile | - Ressourcen aufwendig   | - fehlende GUI                                                          |  
|           |                          |                                                                         |


Für den Einstieg ist vielleicht eine VM einfacher, jedoch ist das Terminal im Informatik Studium dein bester Freund und im 
Endeffekt führt ihr den kompilier Befehl bei beiden Varianten über das Terminal aus. 
* Virtual Machines
  * VirtualBox
* [Windows-Subsystem für Linux](wsl.md)
* Testen mit SSH auf ubu18@eecs
