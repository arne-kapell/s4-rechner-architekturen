Prozessoren sind in Verarbeitungsklassen unterteilbar:

|Verarbeitungsklasse|Assemblerbefehle / Taktzyklus|
|-------------------|-----------------------------|
|nicht skala|\<1|
|skalar|1|
|superskalar|\>1|

(vereinfacht) 4 Verarbeitungsschritte pro Befehl:

1. Befehl hohlen (<span style="color:yellow">IF</span> - **I**nstruction **F**etch)
1. Befehl dekodieren (<span style="color:cyan">ID</span> - **I**nstruction **D**ecoding)
1. Befehl ausführen (<span style="color:magenta">EX</span> - **EX**ecution)
1. Befehl wegschreiben (<span style="color:green">WB</span> - **W**rite **B**ack)

![cpu-nonskalar.png](cpu-nonskalar.png)

Mit Pipeline ist es möglich, dass der Prozessor pro Taktzyklus einen Assemblerbefehl abarbeiten kann (skalar):
![cpu-skalar.png](cpu-skalar.png)

## Fazit

Zusammenspiel von ...

* mehrfachen Pipelines ([Pipelining](Pipelining.md))
* mehrfachen pipelineübergreifenden Execution-Units
* [Out Of Order Execution](Out%20Of%20Order%20Execution.md)
* Branch-Prediction-Unit ([Branch Prediction](Branch%20Prediction.md))
* Speculative Execution

... sorgt für Performance Steigerung

Alle Optimierungen Zusammen bilden Sicherheitslücke (Stichwörter: Spectre, Meltdown).

\#rechnerarchitekturen #steuerwerk
