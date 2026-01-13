---
date: '2026-01-12T00:15:53+01:00'
draft: false
title: 'Funktionen'
summary: 'Erklärungen zu Funktionen'
ShowToc: true
---

- Funktionen sind Zuordnungen
- Einem Wert $x$ wird ein Wert $y$ zugeordnet
- Die Darstellung geschieht in einer Wertetabelle
- Die Darstellung findet in einem Koordinaten-System statt, durch einen Funktionsgraphen
- Der Funktionsgraph ist eine gerade Linie
- Der Verlauf des Graphen wird durch Punkte bestimmt
- Die Punkte bestehen aus Koordinaten der x- und y-Koordinate    

{{< figure src="/images/points.svg" alt="Plot" align="center" caption="**Punkt A(2/1)** und **Punkt B(-2/-1)**">}}

Der erste Wert innerhalb der Klammer, wenn wir einen Punkt bestimmen, ist $x$, der zweite Wert $y$.

$$
\begin{aligned}
&y = mx+b\\\
&m = \text{Steigung}\\\
&b = \text{y-Achsenabschnitt}
\end{aligned}
$$

Die Steigung beschreibt wie stark ein Funktionsgraph steigt oder fällt.
In der Funktionsgleichung wir die Steigung durch die Variable $m$ beschrieben

Je größer der Wert umso steiler die Steigung.

Fällt der Funktionsgraph hat $m$ ein **negatives** Vorzeichen

Eine Zuordnung des Punktes A geschieht durch die Koordinaten (2/1). Sie bilden ein Wertepaar.

Zur Berechnung der Wertepaare verwendet man eine Funktionsgleichung $y=mx+b$

### Schnittpunkt mit der y-Achse

In der Regel gehen Funktionsgraphen nicht durch den Nullpunkt.

Dies bedeutet für die Funktionsgleichung, das der Schnittpunkt mit der y-Achse angefügt werden
muss.

Die Funktionsgleichung hat damit die Form $y = mx+b$

Dies bedeutet für die Bestimmung der Steigung, dass man nicht mehr vom Nullpunkt ausgehen kann, sondern vom Schnittpunkt mit der y-Achse ausgeht.

Die Variable $b$ am Ende der Funktionsgleichung ist der Schnittpunkt des Graphen mit der
$y$-Achse.

Der Schnittpunkt mit der $y$-Achse ist in der Funktionsgleichung der Wert $b$, der meist am Ende der Gleichung angefügt ist.
$$y = mx+b$$

Er bildet in der Aufgabenstellung einen festen Anfangswert, von dem aus der Graph eingezeichnet wird.
Dies ist aber nicht immer der Fall.

### Berechnung der Nullstelle

Die Nullstelle der linearen Funktion ist die Stelle, an der $y$ den Wert $0$ hat.

An diesem Punkt schneidet oder berührt der Graph die x-Achse. 
Die Nullstelle lässt sich rechnerisch berechnen. 

    Beim Duschen werden in der Minute 12 Liter Wasser verbraucht. 
    Der Warmwasserboiler ist mit 120 Litern gefüllt.

    Nach wie vielen Minuten ist der Boiler leer?

Wir stellen eine Funktionsgleichung auf in der Form: $y = mx + b$
$$
\text{Durch das leeren des Boilers haben wir eine negative Steigung}\\\
m = -12\\\
$$

$$
\text{Wir haben anfänglich 120 Liter Wasser, das ist also unser Startpunkt}\\\
b = 120
$$


$$
\text{Die Funktionsgleichung lautet also}\\\
y = -12x + 120
$$ 

Um die Nullstelle zu berechnen, setzen wir $y = 0$: 

$$
\begin{aligned}
0 &= -12x + 120 &&| -120\\\
-120 &= -12x &&| \div (-12)\\\
10 &= x
\end{aligned}
$$

**Antwort:** Nach 10 Minuten ist der Boiler leer.

### Schnittpunkt berechnen von zwei Funktionen

Der Schnittpunkt verrät uns wann sich zwei Funktionen überschneiden, also den gleichen Wert haben.

Dies ist besonders nützlich bei Textaufgaben oder Funktionen, in denen zwei Größen verglichen werden sollen.
Um den Schnittpunkt von zwei linearen Funktionen zu berechnen, setzt man die beiden Funktionsgleichungen gleich und löst nach x auf.

Gleiches Prinzip wie bei Gleichungen.

**Beispiel:**

**Funktion (1):** $y = 2x + 3$

**Funktion (2):** $y = -x + 6$

Gleichsetzen:
$$
\begin{aligned}
2x + 3 &= -x + 6 &| + x\\\
3x + 3 &= 6 &| - 3\\\
3x &= 3 &| \div 3\\\
x &= 1
\end{aligned}
$$

Nun setzen wir $x$ in **eine** der beiden Funktionen ein, dabei ist egal welche, um $y$ zu berechnen:

**Funktion (1):** $y = 2\cdot1 + 3 = 5$

Der Schnittpunkt der beiden Funktionen ist also bei (1/5)</p>
            

{{< figure src="/images/schnittpunkt.svg" alt="Schnittpunkt" align="center">}}

### Bonus
Um die Steigung $m$ zu berechnen, können wir auch, wenn wir die Koordinaten von 2 Punkten haben, eine weitere Formel verwenden
$$
m = \frac{y_2 - y_1}{x_2 - x_1}\\\
y_2 = \text{y von Punkt A}\\\
y_1 = \text{y von Punkt B}\\\
x_2 = \text{x von Punkt A}\\\
x_1 = \text{x von Punkt B}\\\
$$

**Beispiel:**

**Punkt A(3/2) und Punkt B(-5/-2)**
$$m = \frac{2 - (-2)}{3 - (-5)} = 0.5$$

{{< figure src="/images/two_points.svg" alt="Two Points" align="center">}}
