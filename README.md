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

# Terminal Übung

Dies ist eine kleine Übung um den Umgang mit dem Terminal in Unbuntu etwas zu üben. Solltest du auf einem Windows oder Mac unterwegs sein, dann löse die Aufgaben bitte mit dem jeweiligen Terminal (Windows: Eingabeaufforder/CMD/Bash/Powershell).

Notiere immer den verwendeten befehl immer hinter Command:

## Hauptaufgabe

1. Erstelle einen neuen Ordern mit dem Namen `myFirstProject`
   - Command: **mkdir myFirstProject**
2. Gehe in den eben erstellten Ordner
   - Command: **cd myFirstProject**
3. Erstelle 3 Dateien mit den Namen `data1.txt`, `data2.txt` und `data3.md`
   - Command: **touch data1.txt** **touch data2.txt** **touch data3.md**
4. Schreibe in die `data1.txt` mit Nano einen Text und speichere ihn.
   - Command: **nano**
5. Erstelle einen Ordner mit dem Namen `Markdown` und verschiebe die `data3.md` in den Ordner.
   - Command: **mkdir Markdown**
   - Command: **mv /dir/filename /dir/filename**
6. Gehe in den Markdown Ordner und schreibe in die Datei eine Überschrift. Recherchiere hierfür wie man in Markdown eine h1 Überschrift schreibt.
7. Gehe aus dem Markdown Order raus und lösche die `data2.txt` (google nach Unbuntu terminal remove oder nutze Die Untelagen von mir)
   - Command: **cd ..** **rm -r data2.txt**

## Bonus

1. Erstelle einen weiteren Ordner neben dem Markdown Ordner, der Markdown2 heißt.
2. Verschiebe die `data3.md` aus dem Markdown Ordner in den Markdown2 Ordner. (mv für move)
   - Command: **mv /Markdown/data3.md /Markdown2/data3.md**
3. Lösche den Markdown Ordner
   - Command:
4. Verschiebe die Datei `data.txt` in einen Ordner mit dem Namen `TextDateien`, den es noch nicht gibt.
   - Command:

---

