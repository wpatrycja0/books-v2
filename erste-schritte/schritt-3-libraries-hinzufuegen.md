# Schritt 3: Libraries herunterladen

## Libraries herunterladen und hinzufügen {#library-add}

> Du hast die Ardunio IDE erfolgreich heruntergeladen und installiert?

|Ja natürlich! | Nein, habe ich noch nicht..|
|--------------|------------------------------|
|Dann bist du hier genau richtig und du kannst mit dem zweiten Schritt, dem hinzufügen der Libraries starten! |Wenn du nicht weißt was die Arduino IDE ist oder du sie noch nicht installiert hast schau dir zuerst [Schritt 1](erste-schritte/schritt-1-software-installieren) an und folge dort allen Anweisungen.|

>"Library" - Was ist das eigentlich und wofür brauche ich das? 

Eine Library ist wie der Name schon sagt eine Sammlung von etwas - eine Sammlung von Methoden um genauer zu sein. Methoden sind in der Programmierung kleinere Abschnitte von Code die auf ein Objekt angewendet werden können. 
Bei der senseBox zum Beispiel kann eine Methode aufgerufen werden um die LEDs auf dem MCU ein- und auszuschalten. Es gibt eine Menge solcher Standardmethoden, die von einer Vielzahl an Programmmen benutzt werden. Um diese Methoden nicht alle einzeln in den Programmcode übertragen zu müssen, können sie in Libraries abgelegt werden. 
Eine Library ist also eine Datei, in der viele Methoden gespeichert werden. Man kann Libraries in seinen Code einbinden. Dafür reicht es wenn sie im Arduino-Ordner für Libraries gespeichert sind und man sie dann mit einer einzigen Zeile zu Beginn des Programmcodes einbindet. Das sieht in Arduino für die Library mit dem Namen "senseBoxIO" wie folgt aus: 

```c
#include <senseBoxIO.h>;
```

Ist die Library eingebunden, können alle in ihr enthaltenen Methoden im Code benutzt werden. 

Für die senseBox solltet Ihr zu Beginn unbedingt die senseBox-Library einbinden, um alle grundlegenden Methoden gegeben zu haben.





