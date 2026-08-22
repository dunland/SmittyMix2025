# SmittyWerben 2025 Aufnahmen

aufgenommen am 9.+10. August 2025 in Hamburch  
Gitarren overdubs am 30.08., Gesang am 05.09. und 02.10.  

Mischpult: Mackie Onyx 1640i
DAW: Ardour 8.12
44.1kHz, 32bit

## Ordnerstruktur

https://manual.ardour.org/ardourmanual.html#whats-in-a-session

wichtig für git Versionierung:
- **session.ardour** – ardour Projekt
- **session.history** - undo history for the project

Der Ordner "interchange" sollte in der Cloud gespeichert sein.

## Release

### Kassetten

- David hat die Kassetten zu Hause bespielt:
- von Ardour-Projekt "Ardour-Kassetten", Computerlautstärke 100%, Kassettenrekorderlautstärke auf 4.5 ca.

### CDs

CD-Druckeinstellungen für bedruckbare CDs (Verbatim?):
- Vorlage in GIMP: 120x120 mm, Randloser Druck
- Paper Type: Printable Disk (Compatible)
- Paper Size: CD - Custom (119.9 x 119.9 mm)
- Color: CMYK
- Advanced Settings:
    - CD Hub Size: Print to Hub
    - Borderless: Yes
    - CD Size (Custom): 119.9 mm
    - CD Hub Size (Custom): 22.2 – hängt von CD ab, der Innenkreis ist gemeint. Muss man ausmessen
    - Vertical Displacement: 4.9 mm (Versatz in Richtung "Drucker-Inneres"; sonst wurde nicht zentriert gedruckt!
- zwei Typen von CDs:
    - cd-aufdruck mit vollständigem Toastbrot reserviert für standard-CD, also einfach alle songs wie bei bandcamp nacheinander
    - cd-aufdruck mit angebissenem Toastbrot reserviert für alternative CDs (lieder wie auf kassette, mit saxofon und skits)

### Recordjet

02.05.2026
- Man muss eine Artist ID angeben. Die kann man nur via Spotify oder Apple Music anfordern.  (bzw muss für beide jeweils?) Ich wähle .... nichts bisher

## Notizen für Daniel

17.02.2026

Daniel hat einmal alles grob gemastert. Oder so. Jetzt will er unsere Rückmeldungen haben und weiter mischen.

- Generell haben in unseren Ohren die Gitarren und Gesänge ein bisschen vertauschte Rollen; **Vocals dürften insgesamt leiser und Gitarren lauter.** Wir finden's wichtiger dass man versteht was bei den Gitarren passiert, als dass man den Text versteht (bei Magma und Antrieb scheint es schon ganz gut)
- **Gitarren scheinen sehr crunchy, derb**; vielleicht durch einen Höhenanteil, der jetzt stärker durchkommt. Evtl lassen die sich noch ein wenig "weichzeichnen"?
  Wenn ich den Mix mit mumpfigeren Kopfhörern höre, finde ich ihn insgesamt stimmiger :clown
- **Antrieb**: Tobis Gitarre darf bissi lauter
- **9Euro**:
    - Gesang etwas leiser (nur Hauptstimme; Chor kann bleiben)
    - Tobi Gitarre darf noch etwas lauter
    - Hihat ist besonders laut, vielleicht, weil sie offen gespielt wird? jedenfalls schluckt sie dadurch die Snare
        - genauer: von 0:03 bis 0:13 sowie 0:37 bis 0:47 (in den Strophen) werden Snare und Bassgitarre verschluckt
    - bei 0:24 **stolpert der Bass**...das war vorher nicht so! 
      klingt jedenfalls in alten Versionen nicht so. wenn's in der Aufnahme ist, muss ich nochmal rumschnippeln
    - Irgendwie fehlt bei dem Lied insgesamt noch ein bisschen Druck in den Mitten hat Vincent das Gefühl
- **Juwelenraub**: 
    - Vincents Stimme am Ende hat etwas dosigen Effekt. Wir verstehen den Vorschlag (als Betonung des unterschiedlichen Gesangsstils), fänden es aber ohne besser oder nochmal stärker reduziert.
    -  Der Gesang darf auch etwas leiser und Tobis Gitarre lauter.
-  **Glockenmann**: 
	- ~~In der zweiten Strophe kommt es vor, als würde Davids Stimme Vincents etwas hinterherhinken. Oder?~~ ist einfach unpräzise eingesungen..
	- Gesang darf ein bisschen leiser; Chor in der Strophe lauter
	- Tobis Gitarre darf lauter
- **Magma**
	- Gesang ein bissi leiser
	- (**überprüfen**) Chor Refrain alle gleich cutten am Ende
- **Franka**:
    - Gesang-Einsatz bei 1:27 klingt ein bisschen glitchy
- **Schlange**:
	- In der ruhigen Stelle (01:01): Hier ist jetzt die unpräzise Aufnahme der Gesänge deutlich hörbar anhand von aufeinander folgenden Konsonanten (Wortendungen). Das haben wir verkackt, aber es fiel vorher nicht so auf, da der Gesang nicht so schön herausgearbeitet war. Vielleicht verschafft hier auch ein bisschen weniger Prägnanz in den Höhen Abhilfe? Du hast bestimmt ne Idee..
	- Vocal-Effektgeflabber am Ende darf gerne wieder in den Mix rein, das hat so schöne psych-rock vibes
- **Tanker**: 
	- Tobis Gitarre am Ende mehr hervorheben (lauter? weniger Hall?)
	- (**überprüfen**) ganz am Ende den Gesangsschwanz cutten
	  diese Welt ist einfach nicht *faaaiiiirr*...


Trackliste, voraussichtlich:

1. Magma
2. Antrieb
3. Glockenmann
4. Franka
5. Juwelenraub
6. Schlange
7. DingelDongel
8. Management
9. Tanker
10. 9€

## Mixlog

21.01.2026 Stem-Export für Daniel

- Gehe track für track durch:
    1. mute immer alle Spuren, die nicht gebraucht werden
    2. Stem-Export
        1. Channels->Deselect All + Select Audio Tacks (Exclude Muted)
        2. TimeSpan: Track auswählen + Exportieren (32 bit, 44.1 kHz)
    3. schaue in Mixer: Haben Spuren übersteurert? Dann Fader um diese Menge herunterschrauben und erneut exportieren
    4. wenn alles gut ist: Projekt schließen, nicht speichern!

14.01.2026 Aufräumaktion

- Spur "Drums FX" entfernt – war leer.
- ganz viel Umbenennung von Regions, in der Hoffnung, Übersicht zu schaffen (hilft nicht, da Quelldateien nicht mit umbenannt werden..)

12.01.2026

- Antrieb
    - Vincent macht Hauptstimme; David ist leiser
- Schlange
    - alle Gesänge in Bridge leiser gemacht
- Management
    - bei "Unendliche Leiter" Gesänge leiser gemacht
    - Vincents Gitarre beim Einstieg ins Finale minimal verschoben
- Magma
    - Tob Gitarre ein paar dB lauter gemacht
- Juwelen
    - gewünscht: Mehr Effekt auf Gesang insgesamt
        - habe Clean-Gesang leiser gemacht. weiß nicht, ob Anheben der Lautstärke den gewünschten Effekt hat..

05.01.2026

- Gesang-Effekte werden zu Gesänge_FX-Bus geroutet
- reampte Gesang-FX um minimal nach hinten geschoben, damit Hauptgesänge präsent bleiben, wie [er hier](https://www.youtube.com/watch?v=qWAljsZ9EVA) sagt
    - Antrieb: 60000 ms / 172 BPM / 4 = 87ms Versatz
    - Franka, Dingeldongel -> 96 ms
    - Juwelen, Management -> 93 ms
    - Schlange -> 89 ms
    - Tanker -> 185 ms
    - 9€, Magma -> 90 ms
    - Glockenmann -> 73 ms
- Sidechain-Compression auf Effektspur, damit Original-Vocals die Effekte etwas wegdrücken, wie [er hier](https://www.youtube.com/watch?v=q9IVffynToc) sagt.
- Gate Filter auf Vincents Stimme
- Dingeldongel: Tobis Gesang lauter
- **Dingeldongel: Git_tob-2-Senn Phase umkehren!** Das habe ich nicht gemacht, aber fände ich famos, da dann alles weniger kratzig und dosig klingt.
- Bei 9€ fällt auf, dass Davids Stimme keine Höhen mehr hat und dadurch alle ß-Laute fehlen. Also habe ich im EQ den Lowpassfilter rausgenommen. Das habe ich bei allen Hauptstimmen für alle Lieder gemacht.

12.12.2025 Reampen

- Antrieb
    - Vincent+Mattias Gesang paar dB leiser und effektiert
- Franka: nur effektiert
- Management
    - **TO DO**: Gesangslautstärken nochmal checken?
- Glockenmann
    - Gesangslautstärken Vincent+David lauter gemacht
- Magma: (leider Effekte nicht fotografiert)
    - Refrain Gesangslautstärken angepasst: Tob leiser, David+Mattias lauter
- 9Euro nur effektiert
- **allgemein**
    - Hihat 2dB leiser!
- **TO DO**: Vincent will den Bass lauter. Manchmal hört man nur so die ganz tiefen Töne; nicht so sehr den Basslauf? Ist vielleicht aber auch ne Sache der Lautsprecher

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

12.10.2025

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
