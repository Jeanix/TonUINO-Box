# TonUINO Anleitung

Das Lesegerät für die Karten befindet sich auf der oberen Holzfläche vor den 3 Tasten. Auf der Rückseite des TonUINO befindet sich der USB-C Anschluss für Strom bzw. zum Bespielen des MP3-Players über einen Computer.

## 1. Die Bedienung
Zur Benutzung des TonUINO, muss dieser nunächst an Stom angeschlossen werden. Daraufhin benötigt er etwa 5 Sekunden, bis er einsatzbereit ist (es ertönt ein kurzer Hinweiston).

### 1.1 Karten abspielen
Um eine Karte abzuspielen, wird die gewünschte Karte einfach auf den dafür vorgesehenen Platz gelegt oder kurz darüber gehalten. Der TonUINO beginnt dann den von der Karte vorgegebenen Inhalt wiederzugeben. Die Karte kann während der Wiedergabe auch vom TonUINO heruntergenommen werden.

### 1.2 Tasten nutzen
Einige Funktionen der TonUINO lassen sich mit den 3 Tasten bedienen. Hierbei kann es sich je nach Situationen unterscheiden, ob kurz oder lange gedrückt werden muss.

|  |  kurz  | lange |
|----:|:----:|:----:|
| **${\textsf{\color{0022dd}Blau}}$**  | Play / Pause | Aktion abbrechen |
| **${\textsf{\color{00dd22}Grün}}$**  | leiser       | zurück           |
| **${\textsf{\color{dd2200}Rot}}$**   | lauter       | weiter           |		

Es lässt sich also beispielsweise mit der grünen/roten Taste die Lautstärke ändern, mit der blauen Taste die Wiedergabe pausieren und wieder starten oder mit einem langen Druck auf die grüne/rote Taste der vorherige bzw. nächste Titel auswählen (nicht in jedem Wiedergabe-Modus möglich). 

## 2. Admin-Menü
Um ins Admin-Menü zu gelangen, wird der TonUINO eingeschaltet und anschließend der blaue Admin-Chip über den Kartenleser gehalten. Die Sprachausgabe bestätigt, dass sich der TonUINO nun im Admin-Menü befindet.

### 2.1 Die Einstellungen im Admin-Menü
Die Funktionen werden mit der grünen/roten Taste ausgewählt, bestätigt wird mit einem kurzen Druck auf die blaue Taste. Abgebrochen werden kann jederzeit mit einem langen Druck auf die blaue Taste.

### 2.2 Eine Karte neu konfigurieren
Wird eine bisher ungenutzte Karte über den Kartenleser gehalten, fragt der TonUINO automatisch, was mit dieser gemacht werden soll.

Eine bereits zugewiesene Karte kann auch neu konfiguriert werden. Dazu wird im Admin-Menü die Funktion „Karte neu konfigurieren“ gewählt.

### 2.3 Wiedergabemodi
Der TonUINO bietet verschiedene Wiedergabemodi an. Im Admin-Menü werden diese jeweils kurz erklärt, bevor sie bestätigt werden.



## 3. MP3-Players
Der MP3-Player hat 32GB Speicherplatz. Um ihn zu bespielen, muss der TonUINO mit einem Computer verbunden werden. Er wird dann wie ein USB-Stick erkannt (und gleichzeitig als Lautsprecher). 

> [!CAUTION]
>**Achtung:** Es sind zwei Ordner vorhanden, welche auf keinen Fall verändert werden dürfen! Diese heißen „mp3“ und „advert“. Darin befinden sich z.B. die Sprachdateien für den TonUINO.

### 3.1 Bespielen des MP3-Players
Um die eigenen MP3-Dateien zu strukturieren, können max. 99 Ordner angelegt werden. Der Ordnername muss immer zweistellig sein und darf von "01" bis "99" benannt werden. Es darf in der Reihenfolge keine Nummer fehlen. In jedem Ordner dürfen maximal 255 MP3-Dateien liegen. Diese müssen immer mit einer dreistelligen Nummer beginnen, gefolgt von weiteren beliebigen Zeichen.

> [!IMPORTANT]
> **Hinweis:** Die Karten werden immer auf Ordner und Lieder programmiert. Das bedeutet, dass wenn z.B. die Reihenfolge der Lieder in einem Ordner geändert wird, die Karte neu angelernt werden muss, da sie sonst nicht mehr den richtigen Titel wiedergibt.

> [!NOTE]
> **Beispiel:** Dateistruktur auf dem MP3-Player:
> 
> ```
> | - 01
> | |--001_Lied_1.mp3
> | |--002_Lied_2.mp3
> |
> | - 02
> | |--001_Lied_3.mp3
> | |--002_Lied_4.mp3
> | |--003_Lied_5.mp3
> |
> | - 03
> | |--001_Lied_6.mp3
> | |--002_Lied_7.mp3
> | |--003_Lied_8.mp3
> |
> | - advert (nicht ändern!)
> |
> | - mp3 (nicht ändern!)
> ```

### 3.2 Bessere Ausnutzung des Speichers des MP3-Players
Es kann Sinn ergeben, den Spezialmodus "Von-Bis, Album" zu nutzen, da so verschiedene Alben im gleichen Ordnern gespeichert werden und trotzdem verschiedenen Karten zugeweisen werden können. So können trotz der nur 99 möglichen Ordner mehr als 99 Alben mit den Karten verwaltet werden.

> [!NOTE]
> **Beispiel:** Dateistruktur auf dem MP3-Player für drei Alben in einem Ordner:
>  
> ```
> | - 01
> | |--001_Album1_Lied_1.mp3
> | |--002_Album1_Lied_2.mp3
> | |--003_Album1_Lied_3.mp3
> | |--004_Album2_Lied_1.mp3
> | |--005_Album2_Lied_2.mp3
> | |--006_Album2_Lied_3.mp3
> | |--007_Album3_Lied_1.mp3
> | |--008_Album3_Lied_2.mp3
> ```
>
>Über das Admin-Menü werden die drei Karten im Spezialmodus "Von-Bis, Album" wie folgt konfiguriert:
>
>```
>Karte 1: Ordner 1, Datei 001 bis 003
>Karte 2: Ordner 1, Datei 004 bis 006
>Karte 3: Ordner 1, Datei 007 bis 008
>```
