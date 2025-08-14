---
title: "Quadratische Funktionen"
draft: false
weight: 205
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

Quadratische Funktionen begegnen dir öfter, als du vielleicht denkst. Wenn du einen Ball wirfst, eine Brücke anschaust oder eine Satellitenschüssel siehst, steckt dahinter oft eine besondere Kurve – die sogenannte **Parabel**.

## Der Graph einer quadratischen Funktion - Die Parabel

Als <mark>Parabel</mark> wird der Graph einer quadratischen Funktion bezeichnet. Parabeln sind entweder nach unten oder nach oben geöffnet und sind dabei immer charakteristisch wie ein Bogen geformt.

Den Tiefpunkt bzw. Hochpunkt einer solchen bogenförmigen Parabel bezeichnet man als <mark>Scheitelpunkt</mark>.

Die allgemeine Funktionsgleichung einer quadratischen Funktion (Parabel) hat immer die Form $f(x)=ax^2+bx+c$.

Die einfachste Parabel mit der Funktionsgleichung $f(x)=x^2$ wird als <mark>Normalparabel</mark> bezeichnet.

### Symmetrieeigenschaft und Scheitelpunkt quadratischer Funktionen

Eine Parabel ist <mark>achsensymmetrisch</mark>. Ihre Symmetrieachse ist eine vertikale Linie, die durch den Scheitelpunkt der Parabel verläuft und parallel zur y-Achse liegt. Das bedeutet, dass die linke und rechte Seite der Parabel, wenn man sie entlang dieser Achse spiegelt, perfekt übereinstimmen. Man könnte sie sozusagen entlang dieser Symmetrieachse falten, sodass anschließend beide Seiten übereinander liegen.

### Der Streckfaktor

Den Strekfaktor einer Parabel kann man ganz einfach ablesen: Er ist der Parameter $a$ vor dem $x^2$, wenn $f(x)=ax^2$ ist. Der Streckfaktor $a$ bestimmt dabei die Form der Parabel. Man spricht hierbei entweder von Streckung oder Stauchung.

{{< box-notice >}}
    Ob eine Parabel gestreckt oder gestaucht ist, erkennst du am Vorfaktor $a$:
    <ul>
        <li>$a = 1$ oder $a = -1 \Rightarrow $ der Graph ist genauso breit wie die Normalparabel</li>
        <li>$a > 1$ oder $a < -1 \Rightarrow $ die Parabel ist gestreckt</li>
        <li>$-1 < a < 1 \Rightarrow $ die Parabel ist gestaucht</li>
    </ul>
{{< /box-notice >}}

### Verschiebung der Normalparabel entlang der $y$-Achse

Zurück zur allgemeinen Funktionsgleichung $f(x)=ax^2+bx+c$. Um den Streckfaktor $a$ haben wir uns bereits gekümmert. Wofür stehen allerdings $b$ und $c$?

Vorab: Der Parameter $b$ hat keinen sichtbaren Einfluss auf die Lage der Parabel. Der Parameter $c$ beeinflusst jedoch, wie weit die Parabel <mark>nach oben oder nach unten verschoben</mark> wird.

### Die Scheitelpunktform

Neben der allgemeinen Form einer Parabel $f(x)=ax^2+bx+c$ werden Parabeln häufig auch in der sogenannten <mark>Scheitelpunktform</mark> dargestellt. Mit Hilfe der Scheitelpunktform lässt sich der Scheitelpunkt - und somit im Grunde alle wichtigen Eigenschaften einer Parabel - besonders leicht ablesen.

Die Scheitelpunktform einer quadratischen Funktion ist gegeben durch
$$ f(x) = a \cdot (x-x_s)^2 + y_s $$
wobei $x_s$ und $y_s$ die Koordinaten des Scheitelpunkts $S(x_s|y_s)$ sind.

### Verschiebung einer Parabel entlang der $x$- und $y$-Achse

Betrachten wir die quadratische Funktion $f(x)=3(x-4)^2+5$.

Wir erkennen zunächst einmal, dass die Funktionsgleichung in der Scheitelpunktform vorliegt. Das heißt, dass sich die Koordinaten des Scheitelpunkts somit direkt ablesen lassen: $S(4|5)$.

Was heißt das nun? <br />
Die Parabel wurde also um $4$ Einheiten nach rechts sowie um $5$ Einheiten nach oben verschoben.
Außerdem lässt sich noch erkennen, dass die Parabel um den Faktor $3$ gestreckt wird.s

{{< box-notice >}}
    Ist eine quadratische Funktion in der Scheitelpunktform $ f(x) = a \cdot (x-x_s)^2 + y_s $ gegeben, so bestimmt $x_s$ die Verschiebung des Scheitelpunkts entlang der $x$-Achse.
    $y_s$ wiederum bestimmt die Verschiebung des Scheitelpunkts entlang der $y$-Achse.
    <ul>
        <li>$x_s > 0 \Rightarrow $ Verschiebung um $x_s$ entlang der $x$-Achse in positive $x$-Richtung (nach rechts)</li>
        <li>$x_s < 0 \Rightarrow $ Verschiebung um $x_s$ entlang der $x$-Achse in negative $x$-Richtung (nach links)</li>
        <li>$x_s = 0 \Rightarrow $ der Scheitelpunkt liegt auf der $y$-Achse</li>
        <li>$y_s > 0 \Rightarrow $ Verschiebung um $y_s$ entlang der $y$-Achse in positive $y$-Richtung (nach oben)</li>
        <li>$y_s < 0 \Rightarrow $ Verschiebung um $y_s$ entlang der $y$-Achse in negative $y$-Richtung (nach unten)</li>
        <li>$y_s = 0 \Rightarrow $ der Scheitelpunkt liegt auf der $x$-Achse</li>
    </ul>
{{< /box-notice >}}

## Die drei Darstellungsformen

Je nachdem, was man bestimmen möchte, eignen sich die drei Darstellungsformen -- die allgemeine Form, die Scheitelpunktform sowie die Linearfaktorform -- einer quadratischen Funktion auf unterschiedliche Art und Weise.

{{< job numbered="false" style="" title="" name="Tüftelaufgabe" >}}
    Es gibt drei Möglichkeiten, eine quadratische Funktion darzustellen: die allgemeine Form, die Scheitelpunktform sowie die Linearfaktorform. Stelle dar, wie man mathematisch zwischen diesen drei Darstellungsformen wechseln kann.
{{< /job >}}

{{< box-note title="Kurzvortrag gefällig?" >}}
    Diese Aufgabe eignet sich hervorragend für einen kurzen benoteten Vortrag, in dem du der Klasse deine Ergebnisse und Überlegungen vorstellst und so dein Können unter Beweis stellst.
{{< /box-note >}}

## Nullstellen quadratischer Funktionen - Lösen quadratischer Gleichungen

{{< box-notice >}}
    Je nach Position des Scheitelpunkts kann der Graph einer quadratischen Funktion keine, eine oder zwei Nullstellen besitzen.
    <ul>
        <li>die Parabel ist nach oben geöffnet und der Scheitelpunkt liegt oberhalb der $x$-Achse $\Rightarrow$ keine Nullstelle</li>
        <li>die Parabel ist nach unten geöffnet und der Scheitelpunkt liegt unterhalb der $x$-Achse $\Rightarrow$ keine Nullstelle</li>
        <li>der Scheitelpunkt liegt auf der $x$-Achse $\Rightarrow$ eine Nullstelle</li>
        <li>die Parabel ist nach oben geöffnet und der Scheitelpunkt liegt unterhalb der $x$-Achse $\Rightarrow$ zwei Nullstellen</li>
        <li>die Parabel ist nach unten geöffnet und der Scheitelpunkt liegt oberhalb der $x$-Achse $\Rightarrow$ zwei Nullstellen</li>
    </ul>
{{< /box-notice >}}

{{< youtube yuoe6BN-1YQ >}}

{{< youtube IM1WtnTYJK4 >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" entry="Die beiden Videos beschäftigen sich mit dem Bestimmen von Nullstellen quadratischer Funktionen - mit und ohne p-q-Formel." >}}
    <li>Schaue dir zunächst aufmerksam das Video an.</li>
    <li>Betrachte das Video nun ein zweites Mal und schreibe die Beispielaufgabe mit.</li>
{{< /job >}}

{{< box-note title="Zur Erinnerung:" >}}
    Wie genau das mit dem Ausklammern, dem Satz vom Nullprodukt und der p-q-Formel funktioniert, ist bereits im Abschnitt <a class="link" href="/hbf1/1-grundlagen-training/terme-und-gleichungen/">Terme und Gleichungen</a> beschrieben.
{{< /box-note >}}

## Schnittpunkte von Parabel und Gerade

{{< youtube W9tPX_gcGJ4 >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" entry="" >}}
    <li>Schaue dir zunächst aufmerksam das Video an.</li>
    <li>Betrachte das Video nun ein zweites Mal und schreibe die Beispielaufgabe mit.</li>
{{< /job >}}

{{< job name="" numbered="true" style="enum-alph" title="Übung macht den Meister" entry="Bestimme jeweils die Schnittpunkte von Parabel und Gerade." >}}
    <li>$f_1(x) = x^2 - 2x - 3, \qquad g_1(x)= 2x + 2$</li>
    <li>$f_2(x) = 2x^2 + 4x - 2, \qquad g_2(x)= -2x - 2$</li>
    <li>$f_3(x) = -\frac12 x^2 - 2x, \qquad g_3(x)= 2x + 8$</li>
{{< /job >}}

{{< source text="mathe-total.de" src="https://www.mathe-total.de/new15a/Schnittpunkt-von-Geraden-und-Parabeln.pdf" lastcall="13.08.2025" >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$S_1(5|12) \qquad S_2(-1|0)$</li>
    <li>$S_1(0|-2) \qquad S_2(-3|4)$</li>
    <li>$S_1(-4|0)$ (Berührpunkt, da die Gerade $g$ eine Tangente an die Parabel $f$ ist)</li>
{{< /solution >}}

## Schnittpunkte von zwei Parabeln

{{< youtube w_lhORlfZ20 >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" entry="" >}}
    <li>Schaue dir zunächst aufmerksam das Video an.</li>
    <li>Betrachte das Video nun ein zweites Mal und schreibe die Beispielaufgabe mit.</li>
{{< /job >}}

{{< job name="" numbered="true" style="enum-alph" title="Übung macht den Meister" entry="Bestimme jeweils die Schnittpunkte der beiden Parabeln." >}}
    <li>$f_1(x) = 2x^2 + 3x + 7, \qquad p_1(x)= 4x^2 - 5x - 3$</li>
    <li>$f_2(x) = 3x^2 - 5x, \qquad p_2(x)= 2x^2 - x - 4$</li>
    <li>$f_3(x) = 2x^2 - 4x + 10, \qquad p_3(x)= x^2 - 2x - 2$</li>
{{< /job >}}

{{< source text="matheportal.com" src="https://matheportal.com/wp-content/uploads/2023/09/loesung-zu-aufgaben-zu-schnittpunkten-von-quadratischen-funktionen-1.pdf" lastcall="13.08.2025" >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$S_1(-1|6) \qquad S_2(5|72)$</li>
    <li>$S_1(2|2)$ (Berührpunkt)</li>
    <li>kein Schnittpunkt</li>
{{< /solution >}}

## Zusammenfassung: Unterschied zwischen linearen und quadratischen Funktionen

{{< tiktok 7313675899507854624 >}}