## MacOS
Auf dieser Seite wollen wir euch die ersten Sritte erklären, wie ihr C-Code auf einem Mac compilieren könnt. Dadurch, dass macOS ein sehr Unix nahes Betriebssytem ist, ist das zum Glück nicht alzu kompliziert
* Zusätzliche Compiler Flags
* Testen mit SSH auf ubu18@eecs

## C-Compiler
Als erstes solltet ihr euer Terminal öffnen. Dies könnt ihr am schnellsten machen indem ihr die Suchleiste mithilfe von command und space öffnet und dann einfach Terminal eingebt.
Nun könnt ihr euren Compiler installieren, ihr gebt dafür in eurem Terminal
### SSH
Was jedoch beachtet werden muss, ist, dass es in manchen Fällen sein kann, dass euer Code auf eurem Computer zwar einwandfrei compiliert und ausgeführt wird, es aber bei anderen Betriebssystemen (z.B. Linux) zu Problemen führen kann. Aus diesem Grund ist es zu empfehlen die Hausaufgaben (zumindest bei späteren Abgaben) wenn möglich vor der Abgabe auf dem Uniserver via [Secure Shell](https://www.campusmanagement.tu-berlin.de/menue/dienste/daten_server/andrew_file_system/anleitungen_und_hinweise/zugriff_via_ssh_zugang/) (SSH) ([näheres](https://wiki.freitagsrunde.org/SSH)) zuzugreifen und zu testen ob dort auch alles so funktioniert wie es sollte.
### IDE oder nicht?
Ihr könnt euch nun entscheiden ob ihr eine Integrierte Entwicklungsumgebung (IDE) (z.B. [CLion](https://www.jetbrains.com/de-de/clion/)) oder einen Texteditor (z.B. [Atom](https://atom.io)) und das Terminal nutzt. An sich ist CLion zum Beispiel leichter zu handhaben, wenn es darum geht euren Code zu debuggen. Man muss hierbei jedoch beachten, dass manche Sachen, wie zum Beispiel pipen, in CLion nicht funktionieren. Also wenn ihr denkt, dass das Programm eigentlich ohne Probleme aufgerufen werden sollte und es das nicht tut, probiert am besten mal aus es anders auszuführen.
