## Linux

Um die Programmiersprache C nutzen zu können, braucht ihr nur einen [Compiler](https://de.wikipedia.org/wiki/Compiler). Damit könnt ihr euren Programmcode in eine ausführbare Datei übersetzen.
Dieser Prozess kann ohne weiteres auf einen Termin ausgeführt werden.
Auf Linux-Systemen ist `gcc` der übliche [Compiler](https://de.wikipedia.org/wiki/Compiler) für die Programmiersprace C.
Bei den meisten Distributionen ist `gcc` bereits vorinstalliert. Sollte das nicht der Fall sein, könnt ihr `gcc` wie folgt installieren.

### C Compiler installieren

1. Startet ein Terminal (unter Ubuntu z.B. durch `[Strg]` + `[Alt]` + `[T]`)
2. Nutzt euren Paket-Manager zum installieren von `gcc`. Unter Ubuntu beispielsweise:
    1. `sudo apt update`, um die Paketlisten zu aktualisieren
    2. `sudo apt install gcc`, zur eigentlichen Installation
3. Durch den Befehl `gcc --version` könnt ihr überprüfen ob die Installation erfolgreich war und `gcc` nun verfügbar ist. Die Ausgabe sollte ungefähr folgendermaßen aussehen:
```
gcc (GCC) 10.2.0
Copyright (C) 2020 Free Software Foundation, Inc.
Dies ist freie Software; die Kopierbedingungen stehen in den Quellen. Es
gibt KEINE Garantie; auch nicht für MARKTGÄNGIGKEIT oder FÜR SPEZIELLE ZWECKE.
```

### Compilieren von Programmen

Mit dem Befehl
```
gcc -std=c11 -Wall -Werror hello_world.c -o hello_world
```
könnt ihr das Programm `hello_world.c`
```
#include <stdio.h>

int main() {
    printf("Hello World!\n");
    return 0;
}
```
kompilieren. Danach könnt ihr es einfach durch `./hello_world` ausführen.

Wir haben den Compiler mit verschiedenen Optionen ausgeführt. Je nach dem was ihr kompilieren wollt,
müssen diese Optionen angepasst werden. Zum Beispiel verwenden wir den `C11` Standard, es kann aber
notwendig sein z.B. den `C18` Standard zu verweden, wenn euer Programmcode die modernste Syntax verwendet.
