# B-Baum

Binäre Bäume 

Bevor man versteht was ein B-Baum ist, muss man zuerst einmal verstehen, was ein Binärer Baum ist. Ein binärer Baum ist eine Datenstruktur, bei der ein Element zwei Nachfolger hat. Die Elemente nennt man Knoten. Sind beide Nachfolger eines Knotens NULL (wenn es keine gibt), nennt man diese Blatt. Den ersten Knoten nennt man Wurzel. 

Man unterscheidet zwischen: 

Ausgeglichene Bäume  

Der Baum ist ausgeglichen, wenn sich die Stufenhöhe beider Seiten nur um höchstens um eins unterscheiden. 

Geordnete Bäume 


Ein Baum ist geordnet, wenn die Knoten nach einer Strikten Ordnung geordnet sind. Zum Beispiel nach der Ordnung <. Wenn hier ein Wert größer als der der Wurzel ist, "wandert" der Wert nach rechts, wenn nicht nach links. Das wiederholt sich solange mit den folgenden Konten, bis der Wert an seiner korrekten Position ist. 

Ein B-Baum ist ein spezieller Suchbaum. Suchbäume sind Datenstrukturen bei der die Elemente in einer Baumstruktur dargestellt werden. Diese können Methoden zur Suche von einem Element durchführen. Diese Methoden geben das entsprechende Element oder wenn dies nicht gefunden wird NULL zurück. Einzelne Elemente sind mit einem einzigartigen "Schlüssel" gekennzeichnet.  

Bei einem B-Baum werden die Elemente den Schlüssel nach geordnet. Diese Schlüssel liegen zwischen der Ordnungsvariable m (Man spricht von der "Ordnung des Baumes").  Die Elemente, auch "Knoten" genannt, können Schlüsse zwischen m und 2*m annehmen. Es gibt also maximal 2*m Knoten. Die "Wurzel", also der Ursprung ist davon nicht betroffen.  

Beispiel:  

Ein Baum ist von der Ordnung 5. Der Baum kann also Knoten von 5-10 haben. Die Wurzel kann den Schlüssel von 1-10 haben.  
