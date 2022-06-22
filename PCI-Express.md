Nachfolge-Standard des [PCI-BUS](PCI-BUS.md)

Bei Entwicklung paralleler Bussysteme entsteht Problem, dass alle Signale auf allen Leitungen zwischen allen Komponenten gleich lang unterwegs sein müssen. Abhilfe durch künstliche Verlängerung von Leiterbahnen mittels Mäander (Schlaufen zur künstlichen Verlängerung).
Diese Methode begrenzt jedoch Datendurchsatz. Steigerung nur möglich durch Aufgabe des parallelen Datendurchsatzes zu serieller Übertragung.

PCIe (ca. ab 2003) Ersetzung des BUS durch serielle Punkt zu Punkt Verbindung (Lane).
Taktfrequenz bei PCIe-1: 2,5 GHz (Verdopplung der Übertragungsrate von 32-Bit-PCI)

Zusammenschalten von bis zu 16 Lanes möglich um noch mehr Daten gleichzeitig zu übertragen. Die so übertragenen Daten treffen nicht gleichzeitig an Ziel ein uns müssen wieder korrekt Zusammengesetzt werden.

PCIe ist für Software nicht sichtbar, da die parallel-seriell-parallel Wandlung direkt von Hardware übernommen wird.

/wi

\#rechnerarchitekturen #bus-systeme 
