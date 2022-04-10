# Mobile Engineering - Android App Entwicklung mit Kotlin
Dieses Repository enthält die Laboraufgaben für die Präsentation Android App Entwicklung mit Kotlin.
Die Laboraufgabe ist den in Java geschrieben Code in Kotlin umzuschreiben. Das Ergebnis ist ein 
funktionsfähiges TicTacToe-Spiel.

## Vorbereitung
Folgende Tools werden benötigt:
- [Android Studio IDE](https://developer.android.com/studio)
- [Git](https://git-scm.com/downloads)

## Aufgaben
Die Aufgaben sind in der Klasse `MainActivity`. Ihr findet diese unter dem Pfad
`app/src/main/java/de/team/kotlin/tictactoe/MainActivity.kt`.

In der Klasse sind die Methoden `onClick(v: View)` und `resetBoard()`. Diese beiden Methoden 
enthalten auskommentierten Java Code der in Kotlin umgeschrieben werden soll. 

## Testen/Spielen
Das Spiel kann (so wie es ist) auf dem Emulator gestartet werden. 
Der fehlende Code der Methode `onClick` schreibt ein `X` bzw. ein `O` in die Felder.

Der fehlende Code der Methode `resetBoard` stellt den Ausgangspunkt des Spiels wieder her, um eine
neue Runde TicTacToe zu spielen.

Solltest du kein Device für dein Emulator haben, kannst du ihn über über die Device Manager View 
(rechts oben) in Android Studio herunterladen. 
Eine Anleitung findest du [hier](https://www.javatpoint.com/android-emulator).


## Einrichtung
Ihr könnt das Beispiel über Android Studio herunterladen. 

Öffnet Android Studio und drückt im Dialog auf _Get From VCS_ 

![picture alt](https://github.com/dzygann/me-kotlin/blob/main/images/image-1.png)

Im Feld URL tragt ihr die URL von dem Repository ein: 
```
https://github.com/dzygann/me-kotlin.git
```
Dann drückt ihr auf den Button _Clone_

![picture alt](https://github.com/dzygann/me-kotlin/blob/main/images/image-2.png)

Im nächsten Schritt lädt Android Studio alle notwendigen Komponenten herunter.
Damit ist die initiale Einrichtung abgeschlossen.
