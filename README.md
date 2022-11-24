# cheat-scheet

## navigation

the `§ pwd` command (print working directory) writes the full pathname of the current working directory to the standard output.

The `§ cd` (“change directory”) command is used to change the current working directory in Linux and other Unix-like operating systems. It is one of the most basic and frequently used commands when working on the Linux terminal

If you type `§ cd .`, you will change into the current directory or, in other words, the command will do nothing.

Suppose you are currently in the /usr/local/share directory. To switch to the /usr/local directory (one level up from the current directory), you would type: `$ cd ../`

`§ cd` - followed by a dash will bring you to the recent directory you were in.

## List Commands

`ls lists` all files and directories in the working directory.

`ls -a` lists all contents in the working directory, including hidden files and directories.

`ls -l` lists all contents of a directory in long format.

`ls -t` orders files and directories by the time they were last modified.

`ls -latr` sort them by time, but in reverse order.

`ls -R` to see all directory and files.

`tree list` content of directories in a tree-like format.

`tree -d` list directories only.

`ls -lh` shows sizes in a human-readable format.

## Ubuntu

 `sudo` Stands for "super user, do". Grants super user rights for the duration of the current command and often results in a system password entry request.

 `sudo apt update` Re-downloads the current package update list.

 `sudo apt install` (search term) Shows a list of all packages that match the search term.

`sudo apt install`(software name) Installs the package with the corresponding software name.

`sudo apt remove` (software name) Removes the main data of the corresponding software package without removing the configuration data. When reinstalling the same software, it will again receive the same configuration data.

`sudo apt autoremove` Removes dependency packages that are not used anymore by any installed software packages.

`sudo pkill` (process name) Stops and closes running process with the corresponding name.

## Datei Manupilation

Operating system which is used to create, change and modify timestamps of a file

`touch` <dateiname>

Steht für make directory und dient zum Anlegen von einem oder mehreren Verzeichnissen.

`mkdir` <ordnername>

To remove objects such as files on from the file system

`rm` <dateiname>

To remove or delete a file.

`rm -r` <ordnername>

It supports moving one or more files or folders with options for taking backups and preserving attributes

`cp` <dateiname>

Mit diesen befehl werden die Darten in ein Ortner verschomen die auf der gleichen ebene sind.

`mv` <dateiname>

Mit diesen befehl werden die Darten Unbenant. Wobei drauf zuachten ist das der neue nahme nicht schon vorhanden ist, den ansnsten wird diese datei überschriben.

`mv` <dateiname> <anderer dateiname>

Datei oder URL mit dem Standard-Programm des Benutzers öffnen

`xdg-open` <dateiname>

Less ist ein Befehl, der den Inhalt einer Datei anzeigt oder einen Befehl seitenweise in Ihrem Terminal ausgibt. Less ist am nützlichsten, um den Inhalt großer Dateien oder die Ergebnisse von Befehlen anzuzeigen, die viele Ausgabezeilen erzeugen. Der von less angezeigte Inhalt kann durch Eingabe von Tastaturkürzeln navigiert werden.

`less`

Das sind exit Befehle. Wenn man zum Beispiel mit dem less Befehl eine Datei anzeigt, kann man mit q wieder zurück zur normalen Konsole springen. Oft, wenn man sonst nicht weißt wie man zu der normalen Konsole zurück kommt hilft strg+c .

`strg-c`

Das sind exit Befehle. Wenn man zum Beispiel mit dem less Befehl eine Datei anzeigt, kann man mit q wieder zurück zur normalen Konsole springen. Oft, wenn man sonst nicht weißt wie man zu der normalen Konsole zurück kommt hilft strg+c .

 `q`

## Help

Help which is used for listing all possible commands that are pre-installed in Ubuntu

`help`

Display user manual of any runnable command on the terminal

`man`

`Nano`
Easy to use command line editor for Unix and Linux OS

## Nano

`npm`
To install JS software or files with node package manager. -g means to install the package globally, to use it with every file-system. Ater -g you have to write the name of the software.

`npm install -g`

Deinstall JS Software or Files, which were installed globaly with node package maker. Ater -g you have to write the name of the software.

`npm uninstall -g`

Install JS software or files with node package manager.
