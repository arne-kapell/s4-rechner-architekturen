## SDR

***S**ingle **D**ata **R**ate*

* gemeinsamer Takt für ganzen RAM-Baustein
* kurz vor 2000 eingeführt
* alle Steuersignale beziehen sich auf Taktsignal
* Prozessoren schreiben/lesen durch zwischengeschalteten Cache Speicher im Burst Mode (also immer 16 Bytes direkt hintereinander)
  Speicherbausteine wurden insofern optimiert, dass Speicherzugriffe auf aufeinanderfolgende Adressen schnell stattfinden (durch **[Pipelining](Pipelining.md)**, **Vervielfachung der Speicherbänke** und **mehrere Buffer innerhalb des RAM-Bausteins**) :arrow_right: ~ Verdopplung der Datenrate gegenüber [EDO-RAM](EDO-RAM.md)

## DDR/QDR

*Double Data Rate*/*Quad Data Rate*

Da die synchrone Datenausgabe beim SDRAM (*Synchronous Dynamic Random Access Memory*) irgendwann wieder zu langsam wurde, gab man hier **pro Taktperiode 2 statt einem Datenwort** aus.
Bei den Nachfolgeversionen DDR 2/3/4 werden innerhalb des Bausteins immer mehr der nachfolgenden Daten im Voraus bereitgehalten (*Prefetch*).

Bei QDR-SDRAM werden dann schließlich **vier Datenworte pro Taktzyklus** ausgegeben.

\#rechnerarchitekturen #dram 
