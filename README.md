# Rechenscheibe Distanz für Nivellier

Wenn man mit einem Nivellier Distanzmessungen über unwegsames Gelände machen muss,
ist das durch Triangulation möglich. Wichtig hier ist, dass man sich ein Ziel, zu
dem man die Distanz bestimmen möchte, sucht, und dann rechtwinklig querab eine
zweite Messung mit einer bekannten Distanz vornehmen kann.

## Prinzip

Die Abweichung der Peilung des Ziels in Gon (ja, nivelliergeräte messen in Neugrad)
kann dann dazu verwendet werden, um die Distanz zu bestimmen.

Es gilt:

Distanz zum Ziel = tan (Winkelabweichung) * Distanz vom Messpunkt.

Die Rechenscheiben verwenden nun eine logarithmische Skala von Winkel und Distanz,
um diese Rechnung zu vereinfachen. Nicht jeder hat im Feld einen Taschenrechner
einstecken...

## Funktionsweise

Die Skalen entsprechen 

- log (distanz)
- log (tan (winkel)) 

Die Markierungen und Beschriftungen sind so gewählt, dass der Winkel (bzw. Distanz 
auf Achse) dem Ausgangswert der obigen Funktion entsprechen, die Markierungen aber
dem entsprechenden Eingangswert.

Somit entspricht z.B. 50 gon dem Winkel 0, da der tan (50g) = 1 und log (1) = 0.

Aufgrund der Logarithmus gesetze gilt:

log (a * b) = log (a) + log (b)

Da die Skalen logarithmisch gewählt sind, kann man auf der Distanzscheibe innen den
Wert des Abstandes zwischen den beiden Messungen am Pfeil (eben diese 50 Gon) wählen
und anschließend den Wert der Winkelabweichung auf der Gon-Skala suchen. Der Wert
der diesem auf der Distanz-Skala gegenübersteht, ist der gesuchte Abstand zum Ziel.

## Beispiel

Wir stehen an einem Flussufer und möchten dessen Flussbreite bestimmen. An der 
jenseitigen Uferlinie finden wir einen Baum direkt am Uferstrich, den wir anpeilen
können. Zunächst Peilen wir mit dem Nivellier den Baum an, und vermessen anschließend
mit dem Nivellier 100 Gon, in die wir ein paar Meter freies Feld haben.

Dort suchen wir uns einen zweiten Standpunkt. Mit dem Maßband oder mit Hilfe einer
Messlatte bestimmen wir die Absatände zwischen erstem und Zweiten Messpunkt.

Sagen wir, wir haben einen Abstand von 20m zwischen Beiden Stndpunkten. Auf unserer
Rechenscheibe können wir nun diesen Wert einstellen. Wir drehen also die Distanzscheibe
so, dass der Pfeil bei der Winkelskala auf den Wert 20 zeigt.

Wir bauen das Nivellier am zweiten Standpunkt auf, peilen zurück zum ersten Standpunkt
und stellen die Skala des Nivellier auf 0. Anschließend peilen wir auf den Baum und
lesen den Winkel von der Skala ab. Der Unterschied in Gon zwischen altem Messpunkt ist
nun der Wert, den wir benötigen. Wir lesen hier 80 Gon ab.

Wir suchen den Winkel auf der Winkelskala und lesen den Wert ab, der ihr auf der
Distanzskala gegenüberliegt. Dieser liegt bei 62.

Die Flussbreite, bzw. der Abstand zwischen unserem ersten Messpunkt und dem Baum
beträgt also 62m.



