# SmittyWerben 2025 Aufnahmen

aufgenommen am 9.+10. August 2025 in Hamburch  
Ardour 8.12

## Ordnerstruktur

https://manual.ardour.org/ardourmanual.html#whats-in-a-session

wichtig für git Versionierung:
- **session.ardour** – ardour Projekt
- **session.history** - undo history for the project

Der Ordner "interchange" sollte in der Cloud gespeichert sein.

## Mixlog

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
