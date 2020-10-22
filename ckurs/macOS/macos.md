## MacOS
Auf dieser Seite wollen wir euch die ersten Sritte erklären, wie ihr C-Code auf einem Mac compilieren könnt. Dadurch, dass macOS ein sehr Unix nahes Betriebssytem ist, ist das zum Glück nicht alzu kompliziert

## C-Compiler
Als erstes solltet ihr euer Terminal öffnen. Dies könnt ihr am schnellsten machen indem ihr die Suchleiste mithilfe von command und space öffnet und dann einfach Terminal eingebt.

Nun könnt ihr euren Compiler installieren. Der simpelste Weg hierfür ist einfach 
```
gcc
```
oder
```
gcc --version
```
in euer Terminal einzugeben, woraufhin sich dieses Fenster öffnen sollte:

![xcode](GCC-macOS.png)

dort klickt ihr einfach auf "Intallieren" und damit habt ihr Xcode installiert und somit auch gcc.

Eine andere Methode wäre es mit [homebrew](https://brew.sh) zu installieren. Hierfür müsst ihr euch erstmal homebrew installieren. Dies macht ihr indem ihr das Terminal öffnet und den Link auf der Webseite hinein kopiert. Sobald das geschen ist müsst ihr nur noch
```
brew install gcc
```
in eurem Terminal eingeben und gcc ist fertig installiert.


### SSH
Wärend des erstens Semesters werdet ihr auch mit Vallgrind arbeiten. Wie ihr schnell feststellen werdet ist Vallgrind nur für die macOS-Versionen X86/MacOSX 10.12 und AMD64/MacOSX 10.12. erhältlich. Hierfür ist es praktisch die Uniserver zu benutzen, wenn möglich sind dafür die Rechnerräume wie zum Beispiel im TEL eine gute Anlaufstelle. Wenn der Zutritt allerdings nicht möglich ist, oder ihr aus anderen Gründen lieber an eurem Computer arbeiten wollt, gibt es die Möglichkeit per [Secure Shell](https://www.campusmanagement.tu-berlin.de/menue/dienste/daten_server/andrew_file_system/anleitungen_und_hinweise/zugriff_via_ssh_zugang/) (SSH) ([näheres](https://wiki.freitagsrunde.org/SSH)) auf die Uniserver zuzugreifen und dort Valgrind auzuführen. Der Zugriff per SSH ist auch zu empfehlen um Hausaufgaben oder ähnliches noch einmal zu kompilieren und auszuführen. Da es vorkommen kann, dass ein Programm auf eurem eigenen Computer zwar einwandfrei kompiliert, aber bei Linus Systemen eventuell Probleme aufkommen.

### Debugging
Ein debugger wäre der gdb-Debugger um diesen zu installieren downloadet ihr euch (falls noch nicht getan) Homebrew wie oben beschreiben.
Nun gebt ihr 
```
brew install gdb
```
in euer Terminal ein. Im Gegensatz zu gcc ist es hiermit aber noch nicht getan. Damit ihr mit gdb arbeiten könnt müsst ihr erst einmal ein Zertifikat aufsetzen. Wie das Ganze genau funktioniert erfahrt ihr step by step [hier](https://dev.to/jasonelwood/setup-gdb-on-macos-in-2020-489k#generate-cert).

Eine andere Möglichkeit wäre eine Integrierte Entwicklungsumgebung (IDE) (wie z.B. [CLion](https://www.jetbrains.com/de-de/clion/)) zu installieren und damit zu arbeiten. 

