---
layout: post
title: "How I'd learn embedded systems from zero (again)"
date: 2026-11-02
description: "The order I'd do it in, the free resources, and what to buy at Hall Road."
---

If you came here from Instagram after commenting LAB: welcome. This is everything from the carousel, in order, with links.

You don't need an expensive kit or an engineering degree. You need one broken thing, one cheap board, and a trip to Hall Road.

## 1. Don't buy a kit. Buy something broken.

Open a dead laptop or phone before you touch a dev board. Screw discipline, thermal paste, ribbon cables, connectors you're scared to pull. The fear of breaking things dies here, and it's cheaper to learn on something already dead.

**What to get:** a precision screwdriver set, a plastic spudger, and a tube of thermal paste. Hall Road or Hafeez Center, both have all three.

## 2. Learn C and Linux before boards

Every board you'll touch runs C, runs Linux, or both. Pointers, memory, the terminal, file permissions. Boring now, saves you weeks later.

- [CS50x](https://cs50.harvard.edu/x/): free, Harvard. The first half is the best C introduction there is.
- [The Linux Command Line](https://linuxcommand.org/tlcl.php): free book by William Shotts. Read it with a terminal open.

## 3. One cheap board. One real project.

ESP32 or a Raspberry Pi. Not five boards. Pick one and stay with it.

The whole curriculum for month one is three steps:

1. Blink an LED.
2. Read a sensor.
3. Put it on the network.

**What to get at Hall Road:** an ESP32 dev board (or a Raspberry Pi if you want Linux on the board), a breadboard, a pack of jumper wires, some LEDs and resistors, and a basic multimeter.

- [Random Nerd Tutorials](https://randomnerdtutorials.com/): the best step-by-step ESP32 and Pi projects on the internet.
- [Raspberry Pi documentation](https://www.raspberrypi.com/documentation/): official, and actually good.

## 4. Read datasheets, not just tutorials

Tutorials show you the happy path. The datasheet tells you why your board keeps resetting.

It's dense. Read it anyway, one page at a time. Start with the pinout and the electrical characteristics table.

- [Espressif technical documents](https://www.espressif.com/en/support/documents/technical-documents): datasheets and reference manuals for every ESP32 variant.

## 5. Build something only Lahore needs

Everyone has the same weather station on GitHub. Build for your own problems:

- a load-shedding logger
- a UPS battery monitor
- a water-tank level sensor

Nobody else has that project, and it's the one you'll actually finish because you'll use it.

---

I'm documenting my own way back into this, from reviving old ThinkPads to Linux to eventually running ML on tiny devices. Follow along on [Instagram](https://www.instagram.com/_brownnerd/), [X](https://x.com/_brownnerd) and [YouTube](https://www.youtube.com/brownnerd).
