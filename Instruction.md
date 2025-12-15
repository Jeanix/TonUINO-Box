# TonUINO Anleitung

## Die Bedienung
Der TonUINO lässt sich ganz einfach mit den 3 Tasten bedienen. Diese können in manchen Situationen auch unterscheiden, ob man kurz oder lang drückt.

|  |  kurz  | lange |
|--------:|:--------:|:------:|
| **Blau**   | Play / Pause | Aktion abbrechen |
| **Grün**  |  Leiser  |   Zurück |
| **Rot**   | Lauter |    Weiter |		

Das Lesegerät für die Karten befindet sich auf der Holzfläche vor den 3 Tasten.

Auf der Rückseite befindet sich der USB-C Anschluss für Strom bzw. zum Bespielen des MP3-Players über einen Computer.

## Karten abspielen
Um eine Karte abzuspielen, muss der TonUINO zuerst eingesteckt werden. Er benötigt etwa 5 Sekunden, bis er einsatzbereit ist (es ertönt ein kurzer Hinweiston). Danach kann die gewünschte Karte auf den dafür vorgesehenen Platz gelegt werden oder die Karte muss kurz darüber gehalten werden.

Der TonUINO beginnt den von der Karte vorgegebenen Inhalt wiederzugeben. Die Karte kann während der Wiedergabe auch vom TonUINO heruntergenommen werden. Nun kann man mit der grünen/roten Tasten die Lautstärke ändern, mit der blauen Taste die Wiedergabe pausieren und wieder starten oder mit einem langen Druck auf grün/rot den vorherigen bzw. nächsten Titel auswählen (nicht in jedem Wiedergabe-Modus möglich). 

## Admin-Menü
Um ins Admin-Menü zu gelangen, schaltet man den TonUINO ein und hält den blauen Admin-Chip über den Kartenleser.

Im Admin-Menü kann auch eine PIN vergeben werden, die dann jedes Mal abgefragt wird, wenn man das Admin-Menü aufruft. Die Nummer wird dann über die grüne/rote Taste eingegeben.

## Die Einstellungen im Admin-Menü
Die Funktionen werden mit den Lautstärketasten ausgewählt, bestätigt wird mit einem kurzen Druck auf die blaue Taste. Abbrechen kann man mit einem langen Druck auf die blaue Taste.

## Eine Karte neu konfigurieren
Eine ungenutzte Karte kann einfach über den Kartenleser gehalten werden. Dann fragt der TonUINO, was mit dieser gemacht werden soll.

Eine bereits zugewiesene Karte kann auch neu konfiguriert werden. Dazu wählt man im Admin-Menü die Funktion „Karte neu konfigurieren“.

## Wiedergabemodi
Der TonUINO bietet verschiedene Wiedergabemodi an. Im Admin-Menü werden diese jeweils kurz erklärt, wenn man sie auswählt.

## Bespielen des MP3-Players
Der MP3-Player hat 32GB Speicherplatz. Um ihn zu bespielen, muss der TonUINO mit einem Computer verbunden werden. Er wird dann wie ein USB-Stick behandelt (und gleichzeitig als Lautsprecher). Es sind zwei Ordner vorhanden, welche auf keinen Fall verändert werden dürfen! Diese heißen „mp3“ und „advert“.

Um die eigenen MP3-Dateien zu strukturieren, können max. 99 Ordner angelegt werden. Der Ordnername muss immer zweistellig sein und darf von "01" bis "99" benannt werden. Es darf in der Reihenfolge keine Nummer fehlen. In jedem dieser Ordner dürfen maximal 255 MP3-Dateien liegen. Diese müssen immer mit einer 3-stelligen Nummerierung beginnen, danach dürfen, falls gewünscht, weitere beliebigen Zeichen folgen (z.B. "_Lied_123" für eine bessere Übersichtlichkeit).

**Beispiel:**

```
| - 01
| |--001_Lied_1.mp3
| |--002_Lied_2.mp3
|
| - 02
| |--001_Lied_3.mp3
| |--002_Lied_4.mp3
| |--003_Lied_5.mp3
|
| - 03
| |--001_Lied_6.mp3
| |--002_Lied_7.mp3
| |--003_Lied_8.mp3
|
| - advert (nicht ändern!)
|
| - mp3 (nicht ändern!)
```

**Hinweis:** Die Karten werden immer auf Ordner und Lieder programmiert, dass bedeutet, wenn man z.B. die Reihenfolge der Lieder in einem Ordner ändert, muss die Karten neu angelernt werden, da sie sonst nicht mehr den richtigen Titel wiedergeben.

## Bessere Ausnutzung des Speichers des MP3-Players
Es kann Sinn ergeben, den Spezialmodus "Von-Bis, Album" zu nutzen, da man so verschiedene Alben nicht in einzelnen Ordnern ablegen muss, um diese zu trennen, sondern man kann verschiedene Alben auch in einem Ordner speichern und kann sie aber trotzdem verschiedenen Karten zuweisen. So kann man trotz der nur 99 möglichen Ordner mehr als 99 Alben mit den Karten verwalten.

**Beispiel:**

Die MP3-Dateien werden wie folgt auf dem MP3-Player gespeichert:

```
| - 01
| |--001_Album1_Lied_1.mp3
| |--002_Album1_Lied_2.mp3
| |--003_Album1_Lied_3.mp3
| |--004_Album2_Lied_1.mp3
| |--005_Album2_Lied_2.mp3
| |--006_Album2_Lied_3.mp3
| |--007_Album3_Lied_1.mp3
| |--008_Album3_Lied_2.mp3
```

Und über das Admin-Menü werden die 3 Karten im Spezialmodus "Von-Bis, Album" wie folgt konfiguriert:

**Karte 1:** Ordner 1, Datei 001 bis 003\
**Karte 2:** Ordner 1, Datei 004 bis 006\
**Karte 3:** Ordner 1, Datei 007 bis 008

