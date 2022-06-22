***E**nhanced **D**ynamic **O**utput*-RAM ([Standard-DRAM](Standard-DRAM.md))

* Addressierungsphase dauert gewisse Zeit
* Bis nach Abschluss dieser Phase sind Daten auf dem Adressbus ungültig
* Diese Wartezeit kann anderweitig genutzt werden:
  * Einführung eines extra Buffers in die Datenausgänge der RAM-Bausteine (Enhanced Dynamic Output
* Während Adressierungsphase ist in Datenbuffer noch das vorherige Datenwort gespeichert und liegt auf Datenbus
  * ➡️ Verschachtelte Adressierung möglich

Nachteile von EDO-RAM:

* immer noch Asynchrone Arbeitsweise
* Zeiten zwischen den RAS und CAS nicht gleichmäßig, jeder RAM-Baustein ist anders
  * ➡️ der langsamste Baustein bestimmt Schreib-/Leserate
  * Einbeziehung von Sicherheitsreserve für Schwankungen durch z.B. Temperaturunterschiede

\#rechnerarchitekturen #dram 
