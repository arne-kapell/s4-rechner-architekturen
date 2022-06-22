## Einfache Matrix

* verwendet für größere Zahl an LEDs ([Leuchtdioden](Leuchtdioden.md))
* gemultiplexte Matrix
  ![led-matrix.png](led-matrix.png)
* LEDs immer nur kurz an
* kurzzeitig sehr hoher Strombedarf (bis zu einigen Ampere) um ausreichende Helligkeit zu erreichen

## 7-Segment

* meist mehrstellig
* 2 Versionen:
  * Gemeinsame-Kathode
    ![7segment-gk.png](7segment-gk.png)
  * Gemeinsame-Anode
    ![7segment-ga.png](7segment-ga.png)
* durch gemeinsamen Anschluss kann 8-facher Strom fließen :arrow_right:  Ausgangspins des anzusteuernden ICs mit Transistoren verstärken
  * Variante gemeinsame Anode besser geeignet (Ausgangspins von Mikrocontrollern i.d.R stark genug um Kathoden der LEDs ohne Transistor direkt anzusteuern)
  * Versorgung des Mikrocontrollers muss mit der Versorgung der LEDs übereinstimmen (Transistoren funktionieren sonst nicht)

\#rechnerarchitekturen #displays 
