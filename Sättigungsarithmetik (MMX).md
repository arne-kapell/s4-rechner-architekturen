***M**atrix **M**ath E**X**tensions* oder ***M**ulti **M**edia E**X**tensions*

* fast zeitgleich mit SIMD ([SISD - SIMD](SISD%20-%20SIMD.md)) von *Intel* eingeführt
* Verhinderung möglichen Über-/Unterlaufs
* Ergebnis bleibt auf dem Größt-/Kleinstmöglichen Registerwert stehen

## Beispiel für 8-Bit-Sättigungsarithmetik

|||
|--|--|
|ohne Sättigung|$187+175=106+ \textcolor{red}{\text{Carry-Bit}} =106+256=362$|
|mit Sättigung|$187+175=255$|

\#rechnerarchitekturen #rechenwerk 
