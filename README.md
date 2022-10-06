# larva
larva keyboard related sketches, materials, etc

# larva mk.2

![larva](https://user-images.githubusercontent.com/61553650/132993572-15b619b2-919a-49bb-8439-0263a30d82ef.png)

 Larva keyboard is designed as part of a personal platform for research 
of combined, adaptable, extended latin+cyrillic keymap and layout with better ergonomics for day-to-day use.

 Keyboards, keymap, layouts are developed concurrently, work in symbiosis.
I name the whole research project "mnemoNИk|Kombine". 

 Larva PCB+custom plate fits in "daisy40% hhkb" keyboard case by Kprepublic.
Larva mk1 has 4 through-hole LED positions, no rgb, uses *AU mcu. Mk2 has in addition 2 rgb smd LED slots for up-facing SK6812MINI-E LEDs 
and 2 pre-assembled mono-color smd LEDs as alternative to 2 lower through-hole LEDs(facedown, was an experimental feature)
and a few small QoL improvements and uses *MU mcu. Mk 2.1-light version cuts rgb and goes open-source.
Current software-side implementation consists of QMK/vial +custom Windows keymap.
 For activating the bootloader: press the RST button on the back of the pcb.

 (The keyboard design line is constantly evolving, can differ in shapes and sizes, but all serve the same ultimate goal.
 Current line consists of: Larva mk1; Larva mk2; Katerpillar; Katerpillar Infiltrator; Wodka; Wolof; Dragonfly; Butterfly; Mothra; Stargate; Galaga)


* Keyboard Maintainer: [grezeh](https://github.com/grezeh)
* Hardware Supported: *Larva mk.2 pcb (atmega32u4)*
* Hardware Availability: *discord, occasionally, maybe*

QMK hex file compilation for this keyboard (after setting up your build environment,in QMK SYS for Qmk Toolbox):

    qmk compile -kb grezeh/larva/larva2 -km default

VIAL hex file compilation:
    
	qmk compile -kb grezeh/larva/larva2 -km vial

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools)
 and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information.
 Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
 
 ps: lately vial have been giving errors, but locally still compiles fine. needs investigating
  (also, rgb is borked in current version- was experimental feature anyway, cut in version 2.1-light)
  
  oktoberfest'22- open sause the thing! 
  
  [now to need to make house in order, so noone brakes legs here. will upload simplified keymap later]
  
  feedback on possible schematics flaws/improvements is appreciated
