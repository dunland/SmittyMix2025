## x42 equalizer

- dependencies installieren:

`sudo apt-get install lv2-dev libfftw3-dev libcairo2-dev libpango1.0-dev libglu1-mesa-dev libgl1-mesa-dev libjack-dev`

- x42 eq installieren:

`git clone git@github.com:x42/fil4.lv2.git`
`cd fil4.lv2`
`make submodules`
`make`
`sudo make install PREFIX=/usr`

- fil4.lv2 nach .lv2 oder .vst in ~ kopieren
- in ardour plugins scannen
