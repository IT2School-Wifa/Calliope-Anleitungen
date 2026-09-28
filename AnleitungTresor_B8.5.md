# B8.5 Tresor mit Alarmanlage

## Schritt 1
Der Calliope mini kann offene und geschlossene Stromkreise erkennen. Um einen Stromkreis zu schließen, muss beispielsweise Pin 0 mit Masse (-) verbunden werden. Den Kontakt stellt man am besten mit Krokodilklemmen. 

Für dieses Projekt kann der Pin P0 auf der linken Seite der Platine verwendet werden. P0 wird als gedrückt registriert, wenn der Pin mit Masse (-) verbunden ist. Nutze dies für deine Alarmanlage und verwende ``||input.Pin P0 ist gedrückt|`` und ``||logic.wenn ... dann ...||``.
Überlege dir was passieren soll, wenn Pin 0 gedrückt ist und was passieren soll, wenn Pin P0 nicht gedrückt ist? 

![Calliope](https://github.com/TobiGr/Calliope-Anleitungen/blob/master/.docs/static/Stromkreislauf.png?raw=true)
