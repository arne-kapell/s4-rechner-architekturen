## Band

Magnetbänder waren **erste [Magnetische Massenspeicher](Magnetische%20Massenspeicher.md)**. Anfangs umgesetzt durch zweckentfremdete Audio-Tonbänder.
Auch heute noch bewährtes **Backup-Medium**, trotz bzw. auch wegen sequenziellem Zugriff (Zugriffszeiten können im Minutenbereich liegen).

|Laufwerkstyp|Speichergröße|
|------------|---------------|
|LTO-1|100GB|
|...|...|
|LTO-8|12TB|

## Diskette

Zwischenlösung zwischen Magnetbandspeicher und Magnetplatte. Ähnlichkeiten mit Magnetband jedoch Vorteil des wahlfreien Zugriffs.

* direkter Kontakt Schreiblesekopf und Medium :arrow_right: starker Verschleiß und geringe Lebensdauer
* weiterentwickelt zu immer kleinerem Format und höherer Speicherdichte

|Übliche Größen|Eingeführt|Speicher-Kapazität|
|-----------------|-----------|-------------------|
|8 Zoll|1970er|80kB bis 256kB|
|5,25 Zoll|1980er|360kB bis 1,2MB|
|3,5 Zoll|1980er|720kB bis 1,4MB|

## Platte

Funktionsweise wie bei Band oder Diskette allerdings mit kontaktlosem Schreib-/Lesekopf. Dieser schwebt wegen des Bernoulli-Effektes an der rotierenden Platte über jener und berührt diese nie. Beim Ausschalten fährt der Kopf in eine Datenfreie *Landing-Zone*.

Vorteile:

* hohe Rotationsrate :arrow_right: kurze Zugriffszeiten (~halbe Umdrehung)
* hohe Übertragungsrate

Innenraum einer Festplatte ist mit staubfreiem Gas (z.B. Helium) gefüllt, Staubpartikel würde zu *Headcrash* führen.

Speicherentwicklung kontinuierlich verbessert:

* Große Verbesserung durch GMR-Effekt (Giant Magneto Resistance): quantenmechanischer Effekt mit dem Zweck einen kleineren Lesekopf zu konstruieren. Ab 1995 konnte diese Technik in Platten genutzt werden.
* Weitere Steigerung 2008 durch Magnetisierung des Schreibkopfes
* 2013 SMR (Shingled Magnetic Recording) um mehr magnetische Bits auf eine Platte zu bekommen. Bei Magnetisierung einzelner Bits musste immer Sicherheitsabstand eingehalten werden. Schreibkopf ist größer als Lesekopf. Beim Lesen der nun kleineren Magnetzonen macht dies kein Problem, weil der wesentlich kleinere GMR-Lesekopf keine Probleme damit hat.

Aktuelle Festplatten speichern zwischen 2 Lücken aktuell (2018) ca. 40 MB Daten.

### Ausblick auf zukünftige Generationen

Ausnutzung aller in der Vergangenheit eingeführten Technologien liefern maximale Größe von 18 TB (2021).

* HAMR (Heat Assisted Magnetic Recording): Laser erhitzt zu schreibendes Material. Dadurch sinkt benötigte magnetische Feldstärke.
* MAMR (Microwave Assisted Magnetic Recording): direkt bei Schreibkopf Material aufgeweicht durch elektromagnetische Mikrowellenstrahlung.

\#rechnerarchitekturen #systemaufbau 
