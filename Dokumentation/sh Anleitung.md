# Installation und Start von CrypTool 2 auf Linux

Diese Anleitung führt dich Schritt für Schritt durch den Download, die Installation und den Startprozess von CrypTool 2 unter Linux.

---

## Schritt 1: ZIP-Datei herunterladen

Lade zunächst das ZIP-Archiv aus GRIPS herunter und warte bis es fertig ist. 
Link: !!! BITTE AUSFÜLLEN !!!

## Schritt 2: Entpacken 

In deinem Downloads-Ordner solltest du nun ein .zip Archiv haben, welches du ein mal mit Doppelklick entpacken kannst. Daraufhin gehst du in den Cryptool2-Ordner. Dort hast du 2 Dateien:
cryptool.sh
Programm

Falls du KEIN Desktop-Manager hast:
cd ~/Downloads
unzip Cyptool2.zip -d Cryptool2
cd Cryptool2


## Schritt 3: Startdatei ausführen

Als nächstes muss ein Doppelklick auf die cryptool.sh erfolgen. Das startet dein Terminal und auch damit die Installation!
### Wichtig: 
Verfolge das Terminal und drücke bei Nachfrage y oder n. Das Script benötigt zum Installieren von Dateien, dein Passwort, welches du bei Nachfrage angeben musst.

Falls du KEIN Desktop-Manager hast:
Standort Cryptool2 Ordner:
./cryptool.sh

Note: Falls die Nachricht auftaucht es werden erhöhte Rechte benötigt, bitte gebe folgendendes ein:
chmod +x ./cryptool.sh
./cryptool.sh

Ab dort verfolgst du auch nur die Installation und bestätigst alle Anfragen.

## Schritt 4: Installation

Nun wird Wine + Winetricks installiert und auch damit verschiedene Bibliotheken. Dies könnte eine weile dauern und auch manchmal Fehlerhafte anzeigen ausgeben (Einfach ignorieren lol)
Wenn der Prozess durchläuft startet Cryptool2 automatisch! Falls dies aus unvorhergesehenen Gründen nicht passiert führe bitte die cryptool2.sh erneut aus

## Starten von Cryptool2

Jedes mal wenn man Cryptool2 starten möchte, muss man einfach nur wieder zurück in den Schritt 3. Dies prüft ob alles installiert ist und startet das Programm mit allen Abhängigkeiten.


