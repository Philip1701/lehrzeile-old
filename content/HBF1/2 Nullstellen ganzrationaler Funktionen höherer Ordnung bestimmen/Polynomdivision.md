---
title: "Polynomdivision"
description: ""
summary: ""
draft: false
weight: 302
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

Die <mark>Polynomdivision</mark> ist ein mathematisches Rechenverfahren, bei dem ein Polynom durch ein anderes dividiert wird. Ein Polynom wiederum ist ein algebraischer Term, der sich als Summe von Vielfachen von Potenzen einer Variablen darstellen lässt.

Das Verfahren der Polynomdivision funktioniert ähnlich wie die Division von Zahlen mit Rest.

## Polynomdivision bei Polynomen dritten Grades

Mit Hilfe des nachfolgenden Videos lernst du, wie man die Polynomdivision funktioniert.
Die Polynomdivision benötigst du unter anderem, um die Nullstellen von Funktionen zu bestimmen.

Zunächst schauen wir uns dazu ein Beispiel einer Funktion dritten Grades an.

{{< youtube 4I640yIiBbU >}}

{{< job numbered="false" style="enum-arabic" name="Beobachtungsauftrag" >}}
    <li>Schaue dir zunächst aufmerksam das Video an.</li>
    <li>Betrachte das Video nun ein zweites Mal und schreibe die Beispielaufgabe mit.</li>
    <li>Übe noch einmal die schriftliche Division am Beispiel $7800:24$.</li>
{{< /job >}}

{{< job numbered="true" style="enum-alph" title="Üben und Vertiefen" entry="Führe die jeweilige Polynomdivision durch." >}}
    <li>$(x^3 – 6x^2 + 11x – 6) : (x – 1)$</li>
    <li>$(x^3 + x^2 – 4x – 4) : (x + 1)$</li>
    <li>$(25x^3 + 15x^2 – 9x + 1) : (x + 1)$</li>
    <li>$(x^3 – 10x^2 + 29x – 20) : (x – 5)$</li>
{{< /job >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$(x^3 – 6x^2 + 11x – 6) : (x – 1) = x^2 - 5x + 6$</li>
    <li>$(x^3 + x^2 – 4x – 4) : (x + 1) = x^2 - 4$</li>
    <li>$(25x^3 + 15x^2 – 9x + 1) : (x + 1) = 25x^2 – 10x + 1$</li>
    <li>$(x^3 – 10x^2 + 29x – 20) : (x – 5) = x^2 – 5x + 4$</li>
{{< /solution >}}

## Polynomdivision bei Polynomen vierten Grades

Das Verfahren der Polynomdivision funktioniert natürlich auch mit Polynomen höheren Grades. Im Folgenden lernst du, wie man damit die Nullstellen von Polynomen vierten Grades bestimmt.

{{< youtube CNiS387yEOc >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" >}}
    <li>Schau dir das folgende Video zunächst einmal aufmerksam an.</li>
    <li>Schaue das Video nun ein zweites Mal, schreibe dabei die Beispielaufgabe mit und mache dir zu den jeweiligen Rechenschritten Notizen.</li>
    <li>Lege dir nun deine Notizen zur Seite und löse mit deren Hilfe die Beispielaufgabe $(x^4-3x^2+5x-4):(x-2)$ selbst.</li>
{{< /job >}}

{{< job numbered="true" style="enum-alph" title="Übung macht den Meister" entry="Führe die jeweilige Polynomdivision durch." >}}
    <li>$(2x^4 + 4x^3 + 3x^2 + 6x) : (x + 2)$</li>
    <li>$(2x^4 + 3x^3 + x^2 - 3x - 3) : (x + 1)$</li>
    <li>$(-4x^4 - 2x^3 - 4x^2 - 2x + 4) : (2x + 2)$</li>
    <li>$(6x^4 - 48x^2 + 96) : (2x^2 - 8)$</li>
    <li>$(5x^4 - 80) : (x^2 - 4) $</li>
{{< /job >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$(2x^4 + 4x^3 + 3x^2 + 6x) : (x + 2) = 2x^3 + 3x$</li>
    <li>$(2x^4 + 3x^3 + x^2 - 3x - 3) : (x + 1) = 2x^3 + x^2 - 3$</li>
    <li>$(-4x^4 - 2x^3 - 4x^2 - 2x + 4) : (2x + 2) = -2x^3 + x^2 - 3x + 2$</li>
    <li>$(6x^4 - 48x^2 + 96) : (2x^2 - 8) = 3x^2 - 12$</li>
    <li>$(5x^4 - 80) : (x^2 - 4) = 5x^2 + 20$</li>
{{< /solution >}}

## Fragen und "Fallstricke" bei der Polynomdivision

Die Polynomdivision wenden wir an, um Nullstellen von Funktionen zu berechnen, wenn andere Verfahren -- wie etwa die pq-Formel -- nicht klappen. Mit ihrer Hilfe vereinfachen wir die Funktionen also so weit, bis wir andere Verfahren anwenden können.

#### Was tun wir, wenn wir keine Nullstelle gegeben haben?

Wenn wir die Nullstellen einer Funktion bestimmen wollen, aber keine Nullstelle gegeben haben, dann müssen wir vorab eine Nullstelle "erraten", um die Polynomdivision durchführen zu können.

_Wie das geht?_

Möglichkeit #1: Wir schauen uns die Teiler des Absolutgliedes an (der Summand "ohne x") und probieren diese nacheinander aus.

Möglichkeit #2: Wir nutzen unseren Taschenrechner.

#### Was passiert nach der Polynomdivision mit dem Ergebnis?

Wenn du die Polynomdivision durchgeführt hast, dann kannst du wiederum -- mithilfe unterschiedlicher Verfahren -- die Nullstellen dieses Polynoms bestimmen. Hierzu eignen sich je nach Grad des Polynoms Verfahren wie das Wurzelziehen, Ausklammern, Äquivalenzumformung, die p-q-Formel oder erneut die Polynomdivision.

#### Und was ist, wenn die Polynomdivision nicht aufgeht?

In manchen Fällen kann es sein, dass die Polynomdivision nicht ohne Rest aufgeht. Man spricht hier vom sogenannten Restpolynom. Das bedeutet, dass die Funktionen keine weiteren Nullstellen besitzt. Was es darüber hinaus mit dem Restpolynom auf sich hat, damit befassen wir uns später.
