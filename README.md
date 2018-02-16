# B-Baum

Binäre Bäume 

Bevor man versteht was ein B-Baum ist, muss man zuerst einmal verstehen was ein Binärer Baum ist. Ein binärer Baum ist eine Datenstruktur zum Ordnen von Werten. Diese Werte nennt man Knoten. Die Knoten sind untereinander alle mit nur einem Weg verbunden. Ein Knoten kann höchstens zwei nachfolgende Knoten haben. Sind beide Nachfolger eines Knotens NULL (wenn es keine gibt), nennt man dies Blatt. Den ersten Knoten nennt man Wurzel. Die Verbindungen nennt man Verzweigungen. Die Anzahl der Element lässt sich mit 2n  -1 berechnen. Wobei n für die Tiefe stehet. Die Tiefe ist die Anzahl der Konten bis zum Ende. 

Um einen Knoten zu suchen geht man folgendermaßen vor: 

Ist die Wurzel größer als das zu suchende Element, dann wandert das Element nach rechts, wenn es kleiner ist nach links. Solange bis man das Element gefunden hat.  

Um einen Knoten einzufügen geht man folgendermaßen vor: 

Man sucht den Knoten der dem Wert am nächsten kommt. Ist dieser größer als der Knoten wird eine Verzweigung nach rechts erstellt und ein neuer Knoten mit diesem Wert wird erstellt, wenn er kleiner ist nach links. 

Um einen Knoten zu löschen geht man folgendermaßen vor: 

Der Knoten wird gesucht. Ist er gefunden und hat kein Kind wird er einfach gelöscht. Hat er ein Kind wird er gelöscht und eine Verzweigung vom vorigen Knoten wird zum Kind erstellt. Hat er zwei Kinder wird der Knoten gelöscht, eine Verzweigung zu seine rechten Kind erstellt und von diesem eine Verzweigung zu dem linken Kind.  

Man unterscheidet zwischen: 

Ausgeglichenen Bäume 

Der Baum ist ausgeglichen, wenn sich die Stufenhöhe beider Seiten höchstens nur um eins unterscheiden. 

Geordnete Bäume 

Ein Baum ist geordnet, wenn die Knoten nach einer strikten Ordnung geordnet sind. Zum Beispiel nach der Ordnung <. Wenn hier ein Wert größer als der der Wurzel ist, "wandert" der Wert nach rechts, wenn nicht nach links. Das wiederholt sich solange mit den folgenden Konten, bis der Wert an seiner korrekten Position ist. 

B-Baum 

Ein B-Baum ist ein spezieller Suchbaum. Suchbäume sind Datenstrukturen bei der die Elemente in einer Baumstruktur dargestellt werden. Diese können Methoden zur Suche von einem Element durchführen. Diese Methoden geben das entsprechende Element oder ,wenn dies nicht gefunden wird, NULL zurück. Einzelne Elemente sind mit einem einzigartigen "Schlüssel" gekennzeichnet. 

Bei einem B-Baum werden die Elemente den Schlüsseln nach geordnet. Diese Schlüssel liegen zwischen der Ordnungsvariable m (Man spricht von der "Ordnung des Baumes"). Die Elemente, auch "Knoten" genannt, können Schlüsse zwischen m und 2m annehmen. Es gibt also maximal 2m Knoten. Die "Wurzel", also der Ursprung ist davon nicht betroffen. 

Beispiel: 

Ein Baum ist von der Ordnung 5. Der Baum kann also Knoten von 5-10 haben. Die Wurzel kann den Schlüssel von 1-10 haben. 
