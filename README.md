Prawnblaster PCB
================

Provides nice panel-mountable BNC connections and ground-isolated USB
for the Prawnblaster (<https://github.com/labscript-suite/prawnblaster>).

Loosely based on <https://github.com/TU-Darmstadt-APQ/Prawnblaster_Breakout>.

-Trigger input is buffered to allow 5V input without risk to Pi Pico.

-Output clocklines are buffered to drive at 5V (and avoid damage to Pi Pico from those lines floating to 5V).

-Clock input is buffered.

-Analog ADuM5000 used for 5V power isolation and Analog ADuM4160 used for USB isolation. Note that speed is fixed at high speed.

-Fits in 1U Bud box (slightly too tall, so upper panel bends slightly, but probably fine).
