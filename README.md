# Hymnarium
A first Python prototype for a four-human-voice / barbershop-hymn generative desktop/tabletop synthesizer.

Design note
-----------
This is intentionally v0.1: four procedural human-like voices, close-harmony
voice leading, vowel/formant coloration, vibrato/human drift, stereo placement,
simple room reflections, instant SPACE-bar regeneration, and S-key preservation.

The white/grey panel + blue LCD + black rotary controls are a broad tabletop
hardware-synth aesthetic rather than a pixel-for-pixel copy of any commercial
instrument.CONTROL
-------
SPACE   REBIRTH / randomize a new quartet hymn and play it
ENTER   replay current hymn
S       save current full hymn as a 24-bit WAV
ESC     stop audio

The six macro knobs shape the next REBIRTH:
PACE, HUMAN, BREATH, VOWEL, WIDTH, ROOM.

INSTALL (inside your venv)
--------------------------
python -m pip install numpy sounddevice

On Ubuntu/Debian, if Tkinter is missing:
sudo apt install python3-tk

RUN
---
python hymnarium_v0_1.py

SAVES
-----
WAV files go to:
./HYMNArium_Saves/



