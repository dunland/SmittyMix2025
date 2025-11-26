# SmittyWerben 2025 Aufnahmen

aufgenommen am 9.+10. August 2025 in Hamburch  
Gitarren overdubs am 30.08., Gesang am 05.09. und 02.10.  

Ardour 8.12

## Ordnerstruktur

https://manual.ardour.org/ardourmanual.html#whats-in-a-session

wichtig für git Versionierung:
- **session.ardour** – ardour Projekt
- **session.history** - undo history for the project

Der Ordner "interchange" sollte in der Cloud gespeichert sein.

## Mixlog

26.11.2025 Aufräumarbeiten
- Juwelen, Management, Schlange, Tanker auf den Click geschoben
- Rangemarker angepasst, damit Lieder nicht abgecshnitten werden: Schlange und andere
- Automationen: bin ich nochmal durchgegangen, hier und da Ungereimtheiten ausgeräumt
    - Gesang_Vincent_Dopplung_FX gelöscht, war quatsch (Anstieg über halbes Projekt)
    - Tob_Reverb Azimuth: ebenfalls Anstieg/Abstieg über halbes Projekt`
    - digitale Reverbs und Delays entfernt
- Positionskorrekturen:
    - Mattias zweite Stimme bei Antrieb

21.11.2025  
- Gedoppelte Gitarre von Tobias:
    - Equalizer vereinheitlicht
    - Lautstärken angepasst
- Vincent Gesang:
    - minimal Bässe rausgenommen
- Tobias Gesang:
    - minimal Bässe rausgenommen
    - minimal Höhen reingemacht
- 9€:
    - Klicker nach Finale entfernt (war in Tobias' Take 1 Gitarre)

16.11.2025  
- alle Lieder durchgegangen, Gesang FX wieder rein gemacht aber sehr weit runter gezogen
- hier und da auch noch überflüssige Automationen entfernt
- digitale Reverb- und Delay-Effekte entfernt

~~01.11.2025~~
- ~~alle Lautstärken an den Fadern auf 0 hochgezogen (clipt alles wieder sehr jetzt)~~
- Drums:
	- EQ auf Toms, grobe Kompressoren
- Gesang:
	- auf die cleanen Spuren grobe EQs und Kompressoren
	- alle Lautstärken bisschen abgepasst
	- teileweise Effektautomation getestet
	- David 9€ Finale
	- alle bei Glockenmann
	- GVerb kann man nich automatisiert an und aus machen??? Schade!

17.10.2025
- Juwelen-Gitarre aus der 2. Strophe geklaut und nach vorn gesetzt

16.10.2025
- Management: Vincents-Gitarren-Tuba-Ton entfernt
- Glockenmann: letzten Basston rausgeschnitten
- viel Bassgeschnibbel
- Hihat 4,5dB leiser gemacht

12.10.2025:
- Magma Take 2 entfernt
- Magma Strophe Leadgitarre lauter
- Drums:
	- großen Lowcut auf Hihat und Ride gesetzt
	- kleinen Hi- und Lowcut auf die Toms gesetzt
- Gesang:
	- großen Lowcut, kleinen Hicut auf Dry und Wet Gruppenspuren gemacht
- alle Fader runtergedrhet, sodass nichts mehr clipt
- angefangen Gesangslautstärken zu automatisieren

11.10.2025: branch Gitarrenmix in Master übernommen
- Bass, Drums und Raummikrospuren geschnippelt, gefaded, aufgeräumt
- Start/Ende der tracks präziser gesetzt
- Davids Gesang bei der Bridge von 9€ gelöscht

05.10.2025: neuen Branch erstellt für Gitarrenmix
- Gitarren: EQ nochmal neu gemacht, einige Pannings automatisiert
- Gitarren und Bass Spuren geschnippelt / aufgeräumt

22.09.2025
- Gitarren: EQ und Kompressoren, Pannings
- Bass: EQ und Kompressor, Shure Mute

19.09.2025
- Bass: Subbass geboostet bei ca. 65Hz. Brauchen wir beide Basskanäle?

03.09.2025 Analyse des Ardour-Crashs
Tobias wollte zippen, während Ardour was exportiert hat. Irgendwie hat das wohl das Projekt gecrasht. Dann wollte Tob wohl nochmal pullen und dann kam es zum merge konflikt?

- Startet man das Projekt, sieht man:

>Here are a few hints at what might be wrong:
ERROR: Cannot get existing session information from /home/dav/ardour-sessions/Wellness-2025/WELLNESS-2025_KOMPLETT/WELLNESS-2025_KOMPLETT_Gitarren.ardour
ERROR: XML error: Extra content at the end of the document in /home/dav/ardour-sessions/Wellness-2025/WELLNESS-2025_KOMPLETT/WELLNESS-2025_KOMPLETT_Gitarren.ardour at line 2:2
ERROR: XML error: StartTag: invalid element name in /home/dav/ardour-sessions/Wellness-2025/WELLNESS-2025_KOMPLETT/WELLNESS-2025_KOMPLETT_Gitarren.ardour at line 2:2
ERROR: XML error: Extra content at the end of the document in /home/dav/ardour-sessions/Wellness-2025/WELLNESS-2025_KOMPLETT/WELLNESS-2025_KOMPLETT_Gitarren.ardour at line 2:2
ERROR: XML error: StartTag: invalid element name in /home/dav/ardour-sessions/Wellness-2025/WELLNESS-2025_KOMPLETT/WELLNESS-2025_KOMPLETT_Gitarren.ardour at line 2:2

- öffnet man die Projektdatei mit einem Code-Editor, sieht man, dass es offene merge-Konflikte gibt, die ja in die Datei geschrieben werden, und daher alles durcheinander bringen.

30.08.2025
- Calf Equalizer durch x42 ersetzt
- Hihat Phase umgedreht, weil die genau umgekehrt zu Ride und Snare ist
- Lautstärken: Bin nochmal durch alle Kompressoren gegangen und habe Attack & Release angepasst, das macht ganz schön viel aus!
- Juwelen Bass lauter gemacht bei Juwelen, Glockenmann, Dingeldongel, Tanker, Schlange letzter Teil
- grob alle Gitarrenlautstärken gemacht

23.08.2025
- Schlagzeug: Wurst und Kick vertragen sich leider gar nicht. **Wenn bei Wurst die Phase umgedreht wird, hat die Kick viel mehr Druck!**
- Schlagzeug EQs:
    - Kick braucht quasi nix
    - EQ bei Wurst + Snare
- Schlagzeug Dynamik:
    - Einzelne Kompressoren bei Wurst, Snare, Ride
    - kleiner Kompressor auf Gruppenspur
- Grobe Gesamtdynamik:
    - Bass mit Kompressor auf Gruppenspur
- **Management**: Halleffekt etwas rausgenommen
- **Schlange**: Halleffekt mehr rausgenommen
- **Glockenmann**: Halleffekt etwas reingedreht
- Gesamt-Mix: Insgesamt fehlt es total an Höhen im Mix! Habe jetzt stumpf auf Master ein High Shelf gesetzt erstmal. Man müsste wahrscheinlich ausarbeiten, welche
