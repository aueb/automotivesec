# Rad1o

The rad1o badge contains a full-featured SDR \(software defined radio\) half-duplex transceiver, operating in a frequency range of about 50 MHz - 4000 MHz, and is software compatible to the [HackRF](https://github.com/aueb/automotivesec/wiki/HackRF).

It is based on a Wimax transceiver which sends I/Q samples in the range of 2.3 to 2.7 GHz to an ARM Cortex M4 CPU. The CPU can process the data standalone for various applications \(like FM receiving, spectrogram display, RF controlled power outlets, etc.\), or pass the samples to a computer using USB 2.0 where further signal processing can be done e.g. using GNU Radio. Radio signal transmission is also possible in standalone mode by software running on the ARM CPU, or from samples that are sent to rad1o through USB.

The extended frequency range is enabled by a mixer that can be inserted into the RF path. For immediate usage, the board contains a 2.5 GHz PCB antenna. Alternatively, an external antenna can be attached to an SMA connector which can be easily soldered onto the badge by yourself.

The rad1o also provides a Nokia 6100 130×130 pixel LCD and a joystick already known from the r0ket from the last CCCamp 2011. We also included a 4-pin 3.5 mm audio connector which allows both \(mono\) headphone and microphone operation with a standard headset.

There are two micro USB ports, both can charge the battery. USB A can be used for software updates and data I/O to SDR software like GnuRadio.

* [https://rad1o.badge.events.ccc.de/](https://rad1o.badge.events.ccc.de/)
* [https://events.ccc.de/2015/07/10/rad1o/](https://events.ccc.de/2015/07/10/rad1o/)
* [https://github.com/rad1o](https://github.com/rad1o)
* [https://greatscottgadgets.com/2015/08-11-rad1obadge/](https://greatscottgadgets.com/2015/08-11-rad1obadge/)
* [https://twitter.com/rad1obadge](https://twitter.com/rad1obadge)

