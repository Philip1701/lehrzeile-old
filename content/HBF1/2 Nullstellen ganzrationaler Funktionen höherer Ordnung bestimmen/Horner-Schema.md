---
title: "Horner-Schema"
description: ""
summary: ""
draft: false
weight: 303
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

Da das Verfahren der Polynom relativ zeitaufwendig ist, stellt das sogenannte **Horner-Schema** eine effizientere Alternative dar.
Mit Hilfe des Horner-Schemas wird der Grad der Polynomfunktion $f(x)$ schrittweise verringert.

Im folgenden Video wird das Horner-Schema erklärt.

{{< youtube 4ieqRkmqiIg >}}

{{< job name="" numbered="false" style="enum-arabic" name="Beobachtungsauftrag" >}}
    <li>Schaue dir das folgende Video zunächst einmal aufmerksam an.</li>
    <li>Betrachte das Video nun ein zweites Mal und übertrage dir dabei die Beispielaufgabe mitsamt Notizen in deine Unterlagen.</li>
{{< /job >}}

{{< job name="" numbered="true" style="enum-alph" title="Übung macht den Meister" entry="Bestimme zunächst alle Nullstellen mit dem Taschenrechner und überprüfe diese anschließend, indem du jeweils das Horner-Schema anwendest." >}}
    <li>$f_{1}(x)= -x^3 +2x^2 +11x -12$</li>
    <li>$f_{2}(x)= 10x^5 -40x^4 +10x^3 + 60x^2$</li>
{{< /job >}}

{{< solution numbered="true" style="enum-alph" >}}
    <li>$f_{1}(x)= -x^3 +2x^2 +11x -12 \\ \Rightarrow \qquad x_1=-3, \quad x_2=1, \quad x_3=4$</li>
    <li>$f_{2}(x)= 10x^5 -40x^4 +10x^3 + 60x^2 \\ \Rightarrow \qquad x_1=0, \quad x_2=0, \quad x_3=-1, \quad x_4=2, \quad x_5=3$</li>
{{< /solution >}}
