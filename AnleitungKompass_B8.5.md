# S6.5 Kompass

## Kalibrierung des Kompass 
Der Kompass muss nach dem Einschalten kalibriert werden. Nutze dazu folgenden Baustein: 
``||input.Kompass kalibrieren||``

```blocks
input.calibrateCompass()
```

```ghost
input.calibrateCompass()
basic.showString("hi!")
basic.forever(function () {
    Himmelsrichtung = input.compassHeading()
    if (Himmelsrichtung >= 45 && Himmelsrichtung < 135) {
        basic.showString("O")
    } else {
    }
})
```

## Aufgabe 2 - Erstellung Variable
Ihr benötigt einen Platzhalter für die Himmelsrichtung in eurem Programm. Einen Platzhalter bezeichnet man in der Mathematik und in der Informatik auch als Variable.
Erstelle nun eine unter dem Bereich Variablen und speichere anschließend in der Variablen die Kompassausrichtung.


## Aufgabe 3 - Von Kompassausrichtung zu den Himmelsrichtungen 
Die folgende Abbildung hilft euch den Winkel der Kompassausrichtung in Himmelsrichtungen zu übersetzen.

Für die Programmierung sind die Blöcke aus dem Bereich Logik relevant. Denkt dran einen Text oder ähnliches für die Himmelsrichtungen auszugeben, damit man bei der Verwendung des Kompass die Himmelsrichtung erkennt.

![Kompassausrichtung](/static/Kompassausrichtung.png)
