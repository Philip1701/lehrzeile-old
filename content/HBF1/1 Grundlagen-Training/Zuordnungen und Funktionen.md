---
title: "Zuordnungen und Funktionen"
draft: false
weight: 203
toc: true
math: true # für die Nutzung von KaTeX
count: 0 # für die Nummerierung der Aufgaben
---

## Der Begriff der Zuordnung

Eine Zuordnung ist eine allgemeine Beziehung zwischen zwei Mengen.
Sie beschreibt, wie - nicht notwendig allen - Elementen einer Ausgangsmenge $A$ Elemente jeweils ein oder mehrere Elemente aus einer Zielmenge $B$ zugeordnet werden.
Eine Zuordnung kann dabei ein- oder mehrdeutig sein. Das bedeutet, dass ein Element aus der Ausgangsmenge durchaus auch mehreren Elementen der Zielmenge zugeordnet sein kann, wie die folgende Abbildung zeigt:

<a name="abb1"></a>
![image](https://de.bettermarks.com/wp-content/uploads/media/kem_FuD_FuDGWGB_1.jpg)
*Abb. 1: Pfeildiagramm*

{{< source type="image" text="bettermarks" src="https://de.bettermarks.com/wp-content/uploads/media/kem_FuD_FuDGWGB_1.jpg" lastcall="13.08.2025" >}}

### Verdeutlichung an einem Beispiel

{{< box-question title="Beispiel #1:" >}}

- Menge $A$: Menge an Schülerinnen und Schülern
- Menge $B$: Menge aller Sitzplätze im Klassenzimmer
- Zuordnung $A \rightarrow B$: Den Schülerinnen und Schülern wird ein Sitzplatz zugewiesen.

{{< /box-question >}}

**Wichtig:** Im Falle einer Zuordnung wie dieser darf es vorkommen, dass Sitzplätze frei bleiben, Schülerinnen und Schüler leer ausgehen (also keinen Sitzplatz erhalten) oder zwei oder mehrere Schülerinnen und Schüler ein und demselben Sitzplatz zugewiesen werden.

### Darstellungsformen

Es gibt verschiedene Darstellungsmöglichkeiten von bzw. für Zuordnungen:

- Wortbeschreibungen wie z.B.:
$$\text{"Jeder Schüler bekommt einen Sitzplatz."}$$
- Zuordnungstabellen:
{{< margin -2.5em >}}
| Schüler | A | B | C | D | E | F | ... |
|---|---|---|---|---|---|---|---|
| Sitzplatz | 1 | 17 | 3 | 5 | 2 | 20 | ... |

{{< margin -2em >}}

- Pfeildiagramme (siehe [Abb. 1](#abb1))
- Graphen im Koordinatensystem:

<a href="abb2"></a>
![ZUM.de](https://projekte.zum.de/images/thumb/5/59/Graph_Schnecke.jpg/300px-Graph_Schnecke.jpg)
*Abb. 2: Graph einer Zuordnung*

## Der Funktionsbegriff

{{< box-notice title="" >}}
Eine Funktion ist eine eindeutige Zuordnung. Der Begriff ist wie folgt definiert:

<u>Jedem</u> $x$-Wert (Eingabewert bzw. Argument) wird <u>genau ein</u> $y$-Wert (Ausgabe- bzw. Funktionswert) zugeordnet.
{{< /box-notice >}}

Notation:

- $f(x)$ oder $y=f(x)$

{{< margin 1em >}}

Beispiel:

- $f(x)=2x+3 \rightarrow$ Einsetzen von $x=4$ ergibt $f(4) = 2 \cdot 4 + 3 = 11$.

### Veranschaulichung

Im Grunde kannst dir eine Funktion ein wenig so wie eine Maschine bzw. eine _blackbox_ vorstellen:

<a name="abb3"></a>
![image](https://madipedia.de/images/thumb/4/43/Funktionsmaschine-groß.jpg/300px-Funktionsmaschine-groß.jpg)
*Abb. 3: "Funktions-Maschine"*

{{< source type="image" text="madipedia" src="https://madipedia.de/images/thumb/4/43/Funktionsmaschine-groß.jpg/300px-Funktionsmaschine-groß.jpg" lastcall="13.08.2025" >}}

Was passiert hier?

1. Der Eingabewert $x$ wird oben in diese Maschine hineingeworfen.
2. Dieser wird dann durch die Funktion $f$ verarbeitet.
3. Der Funktionswert $f(x)$ wird unten ausgegeben.

### Wichtige Begriffe im Zusammenhang mit Funktionen

{{< box-notice title="" >}}
Im Zusammenhang mit Funktionen solltest du dir die folgenden Begriffe merken:

- die **Definitionsmenge** beschreibt die Menge aller möglichen Eingabewerte $x$
- der Begriff der **Wertemenge** beschreibt die Menge aller möglichen Ausgabe- bzw. Funktionswerte $y$
- die **Funktionsvorschrift** ist die „Rechenregel“, wie bspw. $f(x)=2x+3$, nach der der Eingabewert "verarbeitet" wird

{{< /box-notice >}}

### Zurück zum Beispiel

Um den Unterschied zwischen einer Zuordnung und einer Funktion verstehen zu können, schauen wir uns noch einmal das erste Beispiel von vorhin an und modifizieren es nun:

{{< box-question title="Beispiel #1 - in abgewandelter Form:" >}}
Menge $A$: Menge an Schülerinnen und Schülern
    
Menge $B$: Menge aller Sitzplätze im Klassenzimmer

Funktion $A \rightarrow B$: <u>Jeder</u> Schülerin bzw. jedem Schüler wird <u>genau ein</u> Sitzplatz fest zugewiesen.
{{< /box-question >}}

**Wichtig:** Wenn es sich - wie in diesem veränderten Beispiel - um eine Funktion handelt, dann dürfen zwar auch Sitzplätze frei bleiben, jedoch darf es keine Schülerin bzw. keinen Schüler geben, der oder dem kein Sitzplatz zugewiesen wird. Es darf sogar vorkommen, dass alle Schülerinnen und Schüler denselben Sitzplatz zugewiesen bekommen.

{{< box-notice >}}
Jede Funktion ist eine Zuordnung, aber nicht jede Zuordnung ist eine Funktion.
{{< /box-notice >}}