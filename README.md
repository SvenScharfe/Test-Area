# Test-Area

---

- 👋 Hi, I’m @SvenScharfe
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
SvenScharfe/SvenScharfe is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

---

# Ubuntu Commands

- recap mit Klasse (cd, ls, mkdir, touch)

  - cd = changeDirectory (wechsel Verzeichnis)

  - mkdir = makeDirectory (erstelle Verzeichnis)

  - ls = zeige alle Datein des Verzeichnises

  - ls ./unterordner/unterordner2 - ls -l: detaillierte Liste mit Informationen wie Berechtigungen, Eigentümer, Dateigröße und Änderungsdatum an. - ls -a: Zeigt versteckte Dateien an.
  - ls -h: Zeigt die Dateigröße in einem menschenlesbaren Format (z.B. KB, MB) an, oft in Kombination mit -l (also ls -lh).

  - touch = erzeuge Datei

Ordner Löschen:

- rm -r OrdnerName

- rm -rf OrdnerName

rm: Steht für remove (entfernen).

-r: Steht für "rekursiv", was bedeutet, dass das Kommando auch Unterordner und deren Inhalte löscht.

-f: Steht für "force", was erzwingt, dass die Dateien ohne Bestätigung gelöscht werden, auch wenn sie schreibgeschützt sind.

mv myText.html moveMe.html = umbenennen

mv moveMe.html ../ = eine Ebene hoch

mv moveMe.html ../html = eine Ebene hoch und in einen anderen Ordner rein

---

# Linus Terminal Commands

| Command | Funktion                                                                                   | Optionen                                 | Beispiel                                 |
| ------- | ------------------------------------------------------------------------------------------ | ---------------------------------------- | ---------------------------------------- |
| sudo    | Wird vor einem Befehl verwendet, um diesen als Root oder Administrator auszuführen.        | apt-get, apt-install, ...                | sudo apt-get update/upgrade              |
| ls      | Identisch mit „dir“, enthält das aktuelle Verzeichnis.                                     | -a, -l, -h, -r, -alrh, --sort            | ls-ll                                    |
| lspci   | Listet alle PCI-Geräte auf.                                                                |                                          | lspci                                    |
| lsusb   | Listet alle USB-Geräte auf.                                                                |                                          | lsusb                                    |
| lsmod   | Zeigt den Status der Module im Linux-Kernel.                                               |                                          | lsmod                                    |
| cp      | Dateien kopieren. (cp = copy)                                                              | cp /dir/filename /dir/filename           |
| rm      | Löschen von Dateien. (rm = remove)                                                         | -f (um Verzeichnisse zu löschen!)        | rm /dir/Dateiname oder rm -f /ordnerName |
| mv      | Datei verschieben. (mv=move)                                                               | mv /dir/filename /dir/filename           |
| cat     | Verkettet Dateien und druckt auf der Standardausgabe. cat /dir/logfile                     |
| pwd     | Befehl zum Drucken des Arbeitsverzeichnisses                                               |                                          | cd ./pfad                                |
| cd      | Linux Befehl zum Navigieren durch Verzeichnisse                                            |                                          | cd ..                                    |
| cd ..   | Gehe aus einem Verzeichniss raus in das darüber liegende Verzeichniss                      | cd ../../pfad                            | cd ..                                    |
| mkdir   | Erstellen von Verzeichnissen                                                               |                                          | mkdir meinNeuerOrdner                    |
| touch   | Erstellt eine leere Dateien                                                                |                                          | touch index.html                         |
| cat     | Dateiinhalte auf dem Terminal anzeigen                                                     |
| clear   | Löscht die Terminalanzeige                                                                 |
| echo    | Gibt beliebigen Text aus, der auf den Befehl folgt oder schreibt diesen in eine neue Datei | echo Hallo / echo Hallo touch index.html |
| less    | Befehl zum Anzeigen von Seitenausgaben im Terminal                                         |                                          | less -v                                  |
| man     | öffnet das Handbuch für alle Befehle                                                       |                                          |

Die oberen Befehle sollte man kennen, sowie einige Optionen wie zum Beispiel:
-v um die Version eines Programes zu überprüfen wie bei node -v

## Wietere Befehle

| Command             | Beschreibung                                                                         |
| ------------------- | ------------------------------------------------------------------------------------ |
| ln                  | Erstellen Sie symbolische Links (Verknüpfungen) zu anderen Dateien                   |
| tar                 | Befehl zum Extrahieren und Komprimieren von Dateien unter Linux                      |
| head                | Gibt die angegebene Anzahl von Zeilen von oben zurück                                |
| tail                | Gibt die angegebene Anzahl von Zeilen von unten zurück                               |
| diff                | Finden Sie den Unterschied zwischen zwei Dateien (z.B. diff readme1.txt readme2.txt) |
| cmp                 | Überprüfen, ob zwei Dateien identisch sind (cmp=compare)                             |
| --comm              | Kombiniert die Funktionalität von diff und cmp                                       |
| zip                 | Zip Dateien unter Linux                                                              |
| unzip               | Dateien unter Linux entpacken                                                        |
| ssh                 | Secure Shell Befehl unter Linux                                                      |
| service             | Befehl zum Starten und Stoppen von Diensten unter Linux                              |
| ps                  | Aktive Prozesse anzeigen                                                             |
| kill und killall    | Aktive Prozesse nach Prozess-ID oder Namen beenden                                   |
| df                  | Zeigt Informationen zum Dateisystem der Festplatte an                                |
| mount               | Dateisysteme unter Linux mounten                                                     |
| chmod               | Befehl zum Ändern von Dateiberechtigungen                                            |
| chown               | Befehl zum Ändern des Besitzes von Dateien oder Ordnern                              |
| ipconfig            | Zeigt Netzwerkschnittstellen und IP-Adressen an                                      |
| traceroute          | Verfolgen Sie alle Netzwerk-Hops, um das Ziel zu erreichen                           |
| Alias               | Erstellen Sie benutzerdefinierte Verknüpfungen für regelmäßig verwendete Befehle     |
| useradd und usermod | Fügen Sie neue Benutzer hinzu oder ändern Sie bestehende Benutzerdaten               |
| passwd              | Passwörter für bestehende Benutzer erstellen oder aktualisieren                      |


---

