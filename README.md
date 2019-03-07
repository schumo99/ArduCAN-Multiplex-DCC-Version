# ArduCAN-Multiplex-DCC-Version
DCC Dekoder für Multiplex-Signale, Ampeln, Lauflichter, ....

Der ArduCAN Multiplex ist ein DCC-Decoder auf Arduino-Basis zum Eigenbau. Er steuert bis zu 48 LEDs im Multiplex-Betrieb an und kann sowohl Lichtsignale, als auch Ampeln, Lauflichter, usw. darstellen.

Features:
-	Bis zu 8 Signale (4 Haupt- und 4 Vorsignale) können gleichzeitig angesteuert werden
-	Signalverknüpfung, d.h. der Stellbefehl für ein Hauptsignal kann auch gleich das entsprechende Vorsignal mitstellen
-	Signallogik: Wenn das Hauptsignal Hp0 oder Sh1 zeigt, wird das Vorsignal am gleichen Mast ausgeschaltet
-	Alle Signalbilder frei konfigurierbar
-	Die Helligkeit aller LEDs ist frei konfigurierbar
-	Möglichkeit alle LEDs auch Blinken zu lassen (Blinkfrequenz einstellbar)
-	Auf- und Abblendmöglichkeit aller LEDs, Dunkeltastung zwischen den Signalbildern frei konfigurierbar
-	Bis zu 4 Ampelkreuzungen mit jeweils Haupt-/Nebenstrasse und Fussgängerampel sowie gelbes Blinklicht für Abbieger (frei konfigurierbar, z.B. Schaltzeiten, Helligkeit, Blinken, …)
-	Bis zu 4 Lauflichter (frei konfigurierbar, z:b. Geschwindigkeit, Zahl der beteiligten LEDs, Blendzeit, Helligkeit, ...)
-	Simulation von Licht in Häusern: Zufallsgesteuertes Ein und Ausschalten von Licht in einzelnen Räumen, Anzahl der Räume mit Licht und Lichtwechselrate frei konfigurierbar
-	DCC Adressen frei wählbar über USB-Programmierung, alternativ:  DCC-Adresse lernen über Taster

Zum download steht eine Anleitung, sowie die Software und das Platinenlayout der Hardware zur Verfügung. Über den Thread im Stummiforum oder auch über PN im Stummiforum beantworte ich gerne Fragen. Hinweise zur Verbsserung sind immer erwünscht und werden - wenn möglich - auch umgesetzt.

Platinen und programmierte Prozessoren könnt auch auch von mir bekommen.

Verwendung nur zum Eigengebrauch. Keine kommerzielle Nutzung. 

Der Verfasser übernimmt keine Haftung für eventuelle Schäden oder das Nichtfunktionieren der Schaltung. Hinweise und/oder Verbesserungsvorschläge sind immer erwünscht.
