---
title: "Nullstellen von kubischen Funktionen"
description: ""
summary: ""
draft: false
weight: 301
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

Falls du dir nicht mehr sicher bist, wie man Nullstellen von linearen und quadratischen Funktionen bestimmt, dann schaue dir zunächst noch einmal den [Abschnitt](/hbf1/1-grundlagen-training/nullstellen-bestimmen/) aus dem Grundlagen-Training an.

<!-- Zusätzlich stehen dir hier begleitende Folien bereit:

{{< slides src="/hbf1/1-Grundlagen-Training/Nullstellen.pdf" >}} -->

## Anzahl der Nullstellen einer Polynomfunktion

Bevor wir uns mit den Verfahren zur Nullstellenbestimmung von Polynomfunktionen befassen, sollten wir zunächst noch einen Blick darauf werfen, <mark>wie viele Nullstellen</mark> eine solche Polynomfunktionen überhaupt besitzen kann. Hierzu gilt folgender Merksatz:

{{< box-notice title="" >}}
    Eine Polynomfunktion kann <b>maximal so viele</b> Nullstellen haben, <b>wie der Grad des Polynoms</b> ist.
{{< /box-notice >}}

{{< box-note title="Beispiel" >}}
    <ul>
        <li>Eine lineare Funktion - also eine Polynomfunktion vom Grad <b>eins</b> - besitzt maximal <b>eine</b> Nullstelle.</li>
        <li>Eine quadratische Funktion (Grad <b>zwei</b>) kann maximal <b>zwei</b> Nullstellen besitzen.</li>
        <li>Eine Polynomfunktion vom Grad <b>drei</b> kann maximal <b>drei</b> Nullstellen besitzen.</li>
        <li>...</li>
        <li>Eine Polynomfunktion vom Grad <b>n</b> kann maximal <b>n</b> Nullstellen besitzen.</li>
    </ul>
{{< /box-notice >}}

## Neue Verfahren zum Bestimmen von Nullstellen

Bisher hast du Funktionen kennengelernt, deren Nullstellen du entweder mithilfe einfacher Äquivalenzumformung oder mit Hilfe der p-q-Formel bestimmen konntest. Nun widmen wir uns aber kubischen Funktionen -- also Funktionen dritten Grades. Hier kommst du nur mit diesen beiden Verfahren allein leider in den meisten Fällen nicht weiter.

Wir benötigen dazu noch ein paar weitere Verfahren, die wir nun nach und nach kennenlernen werden.

## Nullstellen bestimmen durch Ausklammern und den Satz vom Nullprodukt

Hat man es mit einer linearen oder quadratischen Funktion zu tun, so lassen sich deren Nullstellen durch Äquivalenzumformung, einfaches Wurzelziehen oder die p-q-Formel bestimmen. Bei Funktionen dritten Grades (sprich: kubischen Funktionen) ist dies jedoch anders. Hier reichen diese Verfahren nicht mehr aus, sodass wir uns nun dem Bestimmen von Nullstellen durch <mark>Ausklammern</mark> und der Anwendung des <mark>Satzes vom Nullprodukt</mark> widmen.

{{< youtube oywjcZxfwS4 >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" >}}
    <li>Schaue dir zunächst aufmerksam das Video an.</li>
    <li>Betrachte das Video nun ein zweites Mal und schreibe die Beispielaufgabe mit.</li>
{{< /job >}}

{{< job name="" numbered="true" style="enum-alph" title="Übung macht den Meister" entry="Bestimme die Nullstellen der jeweiligen Funktion, indem du zunächst die kleinste Potenz ausklammerst und dann den Satz vom Nullprodukt anwendest." >}}
    <li>$f_1(x) = x^3 – 4x$</li>
    <li>$f_2(x) = x^3 + 4x^2$</li>
    <li>$f_3(x) = x^3 - 3x^2$</li>
    <li>$f_4(x) = 2x^3 - 5x^2$</li>
    <li>$f_5(x) = 0,5x^3 - x^2$</li>
{{< /job >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$f_1(x) = x^3 – 4x \qquad \Rightarrow x_1=-2, \quad x_2=0, x_3=2$</li>
    <li>$f_2(x) = x^3 + 4x^2 \qquad \Rightarrow x_1=-4, \quad x_2=0$</li>
    <li>$f_3(x) = x^3 - 3x^2 \qquad \Rightarrow x_1=0, \quad x_2=3$</li>
    <li>$f_4(x) = 2x^3 - 5x^2 \qquad \Rightarrow x_1=0, \quad x_2=2,5$</li>
    <li>$f_5(x) = 0,5x^3 - x^2 \qquad \Rightarrow x_1=0, \quad x_2=2$</li>
{{< /solution >}}

## Nullstellen durch Ausklammern und p-q-Formel bestimmen

{{< youtube z4BjIqYJCps >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" >}}
    <li>Schaue dir zunächst aufmerksam das Video an.</li>
    <li>Betrachte das Video nun ein zweites Mal und schreibe die Beispielaufgabe mit.</li>
{{< /job >}}

{{< job name="" numbered="true" style="enum-alph" title="Übung macht den Meister" entry="Bestimme die Nullstellen der jeweiligen Funktion, indem du zunächst die kleinste Potenz ausklammerst und dann die p-q-Formel anwendest." >}}
    <li>$f_1(x) = 0,25x^3 – x^2 + x$</li>
    <li>$f_2(x) = x^3 + 2x^2 - 3x$</li>
    <li>$f_3(x) = x^3 - 6x^2 + 9x$</li>
    <li>$f_4(x) = x^3 - 8x^2 + 16x$</li>
    <li>$f_5(x) = x^3 - 4x^2 - 21x$</li>
{{< /job >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$f_1(x) = x^3 + 2x^2 - 3x \qquad \Rightarrow x_1=-3, \quad x_2=0, \quad x_3=1$</li>
    <li>$f_2(x) = x^3 + 2x^2 - 3x \qquad \Rightarrow x_1=-3, \quad x_2=0, \quad x_3=1$</li>
    <li>$f_3(x) = x^3 - 6x^2 + 9x \qquad \Rightarrow x_1=0, \quad x_2=3$</li>
    <li>$f_4(x) = x^3 - 8x^2 + 16x \qquad \Rightarrow x_1=0, \quad x_2=4$</li>
    <li>$f_5(x) = x^3 - 4x^2 - 21x \qquad \Rightarrow x_1=-3, \quad x_2=0, \quad x_3=7$</li>
{{< /solution >}}
