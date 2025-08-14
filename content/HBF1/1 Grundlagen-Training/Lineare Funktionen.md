---
title: "Lineare Funktionen"
draft: false
weight: 204
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

## Linearität

Was bedeutet Linearität eigentlich?

> Ein linearer Zusammenhang beschreibt eine Beziehung zwischen zwei Variablen, bei der sich die eine Variable mit konstanter Rate ändert, wenn sich die andere Variable ändert. Dies kann als eine gerade Linie in einem Diagramm[^1] dargestellt werden.

[^1]: Hiermit ist hier ein kartesisches Koordinatensystem gemeint.

## Die Funktionsvorschrift einer linearen Funktion

Jede Funktionsgleichung einer linearen Funktion hat die Form[^2] $$f(x) = m \cdot x + b$$

$m$ steht hierbei für die Steigung der Geraden, $b$ wiederum für den sogenannten y-Achsenabschnitt.

[^2]: Manchmal liest man hier auch $y = m \cdot x + b$. Ab sofort verwenden wir jedoch die Notation mit $f(x)$.

## Der Graph einer linearen Funktion

{{< box-notice title="" >}}
    Der Graph einer linearen Funktion ist immer eine **Gerade**.
{{< /box-notice >}}

Geraden können steigen, fallen oder waagerecht im Koordinatensystem liegen. Dies hängt unmittelbar von der Steigung $m$ ab.
Dabei gibt es drei verschiedene Möglichkeiten:

1. $m > 0$: die Gerade steigt
2. $m = 0$: die Gerade verläuft waagerecht (parallel zur x-Achse)
3. $m < 0$: die Gerade fällt

Der y-Achsenabschnitt $b$ wiederum beschreibt diejenige Stelle, an der der Funktionsgraph die y-Achse schneidet.

<!-- Playlist: https://youtube.com/playlist?list=PLF29x0idI4lU6F9lF8CBWHnrhfak852OT&si=Of4IvBm1-UQHAlSL -->
{{< youtube 50E1gIunhzE >}}

{{< job numbered="false" style="enum-arabic" name="Beobachtungsauftrag" >}}
    <li>Schaue dir zunächst aufmerksam das Video an und rufe dir die Vorgehensweise in Erinnerung.</li>
    <li>Zeichne den Graphen der Funktion $f(x)=-2x+3$.</li>
{{< /job >}}

## Steigung und y-Achsenabschnitt bestimmen

Nehmen wir an, die beiden Punkte $P_1$ und $P_2$ mit $P_1(x_1|y_1)$ und $P_2(x_2|y_2)$ liegen auf dem Graphen der linearen Funktion $f$.
Die Steigung $m$ der Geraden lässt sich dann berechnen mit

$$m = \frac{\Delta y}{\Delta x} = \frac{y_2-y_1}{x_2-x_1} \quad \text{bzw.} \quad m = \frac{y_1-y_2}{x_1-x_2}.$$

Eine Anleitung, wie das am praktischen Beispiel funktioniert, findest du hier:

{{< youtube 5L7O_3giIps >}}

{{< job numbered="true" style="enum-arabic" title="bettermarks" >}}
    <li>{{< bettermarks uebungscode="3YBP" seriesID="1666766210978546048" title="Steigung einer Geraden ablesen" >}}</li>
    <li>{{< bettermarks uebungscode="AL61" seriesID="1666767508096418048" title="Funktionsgleichung zum Graphen einer linearen Funktion bestimmen" >}}</li>
    <li>{{< bettermarks uebungscode="GME1" seriesID="1666766751972458880" title="Funktionsgleichung zu einer Geraden bestimmen" >}}</li>
{{< /job >}}

## Von der Funktionsgleichung zur Wertetabelle

Eine Funktionsgleichung ist eine mathematische Formel, welche die Beziehung zwischen $x$ und $y$ definiert.
Eine Wertetabelle wiederum ist eine tabellarische Darstellung, die die Zuordnung zwischen $x$-Werten und den entsprechenden $y$-Werten eben jener Funktion zeigt. Solch eine Wertetabelle hilft dir unter anderem dabei, den Graphen der Funktion zu zeichnen.

{{< youtube qGToWDAYyxw >}}

{{< job numbered="true" style="enum-alph" title="Üben und Vertiefen" columns="2" entry="Erstelle jeweils eine Wertetabelle für die folgenden Funktionen" >}}
    <li>$f_1(x)= 4x - 3$</li>
    <li>$f_2(x)= -\frac14 x + 10$</li>
    <li>$f_3(x)= 0,25x$</li>
    <li>$f_4(x)= 1$</li>
{{< /job >}}

## Den Graphen einer linearen Funktion zeichnen

Wie du den Graphen einer linearen Funktion zeichnest, lernst du hier:

{{< youtube 50E1gIunhzE >}}

{{< job numbered="true" style="enum-arabic" title="bettermarks" >}}
    <li>{{< bettermarks uebungscode="321G" seriesID="1666778532463771904" title="Graphen linearer Funktionen mit gleichen Steigungen oder gleichen y-Achsenabschnitten zeichnen">}}</li>
    <li>{{< bettermarks uebungscode="Y7JQ" seriesID="1666779187962183936" title="Graph einer linearen Funktion zu gegebener Funktionsgleichung zeichnen" >}}</li>
    <li>{{< bettermarks paper="true" uebungscode="2BYU" seriesID="1666750685397410817" title="Graphen linearer Funktionen auf Papier zeichnen - Achseneinteilung geeignet wählen" >}}</li>
{{< /job >}}

## Von der Wertetabelle zur Funktionsgleichung

Ist die Funktionsgleichung $f(x)$ gesucht, gibt es verschiedene Möglichkeiten, diese aufzustellen.
Eine Möglichkeit - die hier vorgestellt wird - besteht darin, eine Wertetabelle heranzuziehen und so zur Funktionsgleichung zu gelangen.

{{< youtube M5VnezyzfiY >}}

{{< job numbered="true" style="enum-arabic" title="bettermarks" >}}
    <li>Betrachte dir zunächst das obige Video.</li>
    <li>Schaue dir das Video nun ein zweites Mal an und schreibe die Beispielaufgaben in Ruhe mit. Mache dir dazu auch entsprechende Notizen.</li>
    <li>Teste dein Können mit Hilfe der folgenden Aufgaben bei bettermarks:<br />{{< bettermarks uebungscode="U5TA" seriesID="1667066778770997376" title="Funktionsgleichung zu gegebener Wertetabelle bestimmen" >}}</li>
{{< /job >}}

## Lineare Funktion durch zwei Punkte

Ist lediglich der Graph der Funktion $f$ gegeben, so besteht eine zweite Möglichkeit, die Funktionsgleichung $f(x)$ zu bestimmen. Hierzu kann man zunächst mehrere Punkte am Graphen der Funktion ablesen, um anschließend die Funktionsvorschrift zu ermitteln.

{{< youtube kPofqbNlkM4 >}}

{{< job numbered="true" style="enum-arabic" title="bettermarks" >}}
    {{< bettermarks uebungscode="E9X8" seriesID="1667069123965747328" title="Geradengleichung aus zwei Punkten bestimmen" >}}
{{< /job >}}

## $x$-Werte zu gesuchten $y$-Werten bestimmen

In einem der vorherigen Abschnitte hast du bereits gelernt, wie man eine Wertetabelle erstellt, wenn man bereits die Funktionsgleichung $f(x)$ gegeben hat. Man sucht also nach den zugehörigen $y$-Werten zu gegebenen $x$-Werten. Oftmals möchte man aber auch den umgekehrten Weg gehen und sucht nach dem $x$-Wert zu einem gegebenen $y$-Wert. Wie das geht, lernst du hier:

{{< youtube GIruIAbLGFU >}}

{{< job numbered="true" style="enum-arabic" title="bettermarks" >}}
    <li>Wiederholung vorheriger Abschnitte:<br />Schaue dir das nachfolgende Video an und vollziehe das Aufstellen der Funktionsgleichung sowie das Bestimmen der $y$-Werte nach.</li>
    <li>Halte nun das Video an der Stelle <code>6:20</code> an und bestimme den $x$-Wert zum gegebenen $y$-Wert $3,5$. Kontrolliere anschließend deine Lösung, indem du das Video zu Ende schaust.</li>
{{< /job >}}

{{< youtube -PxVXkSHOaE >}}

## Nullstellen linearer Funktionen

Im nachfolgenden Video lernst du, wie man die Nullstellen einer linearen Funktion bestimmt.

{{< youtube GQdMXu3mILA >}}

{{< job numbered="true" style="" title="bettermarks" >}}
    {{< bettermarks uebungscode="3MMB" seriesID="1667069577038659840" title="Nullstellen rechnerisch bestimmen" >}}
{{< /job >}}

## "Punktprobe"

Mit Hilfe der Punktprobe überprüft man rechnerisch, ob ein Punkt auf dem Graphen einer Funktion (z. B. dem einer linearen oder quadratischen Funktion) liegt. Bei der Punktprobe setzt man die Koordinaten des gegebenen Punktes in die Funktionsgleichung $f(x)$ ein und schaut, ob man eine wahre oder falsche Aussage erhält:

- wahre Aussage → der Punkt liegt auf dem Graphen
- falsche Aussage → der Punkt liegt <u>nicht</u> auf dem Graphen

<br />

{{< youtube latplHtUXlA >}}

{{< job numbered="true" style="" title="bettermarks" >}}
    {{< bettermarks uebungscode="VQG7" seriesID="1668591632372466048" title="Mit Punktprobe prüfen, ob ein Punkt auf einer Geraden liegt" >}}
{{< /job >}}

{{< box-question title="Nachgedacht:" >}}
    Mit Hilfe dieser Methode kann man nicht nur herausfinden, ob ein Punkt auf einer Geraden liegt. Damit lässt sich auch herausfinden, ob ein Punkt oberhalb oder unterhalb des Graphen der Funktion liegt.
{{< /box-question >}}

{{< job numbered="false" style="" title="" name="Tüftelaufgabe" >}}
    Finde durch -- z. B. durch eine entsprechende Recherche oder durch Ausprobieren -- heraus, wie man überpüfen kann, ob ein Punkt oberhalb oder unterhalb des Graphen einer Funktion liegt. Fertige dir entsprechende Notizen an.
{{< /job >}}

{{< box-note title="Kurzvortrag gefällig?" >}}
    Diese Aufgabe eignet sich hervorragend für einen kurzen benoteten Vortrag, in dem du der Klasse deine Ergebnisse und Überlegungen vorstellst und so dein Können unter Beweis stellst.
{{< /box-note >}}

## Nützliche Links

Weitere Informations- und Übungsmaterialien findest du hier:

- [Studyflix: Nullstellen berechnen](https://studyflix.de/mathematik/nullstellen-berechnen-1957)
