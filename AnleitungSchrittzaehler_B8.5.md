# B8.5 Schrittzähler

## Schritt 1: Variable erstellen
Ihr benötigt einen Platzhalter in eurem Programm, der sich die bisherigen Schritte merkt. Einen Platzhalter bezeichnet man in der Mathematik und in der Informatik auch als Variable. Erstellt nun eine unter dem Bereich Variablen. Wie viele Schritten sind beim Start in der Variablen gespeichert?


```ghost
input.onButtonEvent(Button.A, input.buttonEventClick(), function () {
    Schritte = 0
})
input.onGesture(Gesture.Shake, function () {
    Schritte += 1
    basic.showNumber(Schritte)
    basic.showString("hi!")
    basic.showIcon(IconNames.Heart)
    if (Schritte == 50) {
     music.play(music.tonePlayable(262, music.beat(BeatFraction.Whole)), music.PlaybackMode.UntilDone)
     music.play(music.stringPlayable("", 120), music.PlaybackMode.UntilDone)
     basic.setLedColor(0xff0000)
     }
})
let Schritte = 0
Schritte = 0
basic.forever(function () {
})
```

## Schritt 2: Schritte erhöhen
Der Calliope merkt, wenn er geschüttelt wird. Man kann also sagen, dass durch einen Schritt der Calliope einmal geschüttelt wird. Nutzt den Block ``||input.wenn geschüttelt|`` und programmiere das sich die Anzahl der Schritte in der Variablen erhöhen.

## Schritt 3: Schritte anzeigen 
Überlegt euch wann die Schritte angezeigt werden sollen. Vielleicht nach jedem gemachten Schritt oder nach jedem zehnten Schritt? Zusätzlich könnte auch ein Licht ausgegeben werden. Setze deine Ideen im Programmcode um. 

## Schritt 4: Schrittziel erreicht
Überlegt euch ein Schrittziel und lasst den Calliope einen Ton oder ein Bild auf der LED Matrix ausgeben, wenn das Schrittziel erreicht ist. 

## Schritt 5: Anzahl der Schritte zurücksetzen
Überlegt euch einen Weg, wie man die Anzahl der Schritte auf 0 zurücksetzen kann, ohne dass das gesamte Programm über den Reset-Knopf des Calliopes zurückgesetzt werden muss.
