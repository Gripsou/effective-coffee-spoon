NOTE(S)
=======

Brief
-----

This file exists only to track some components that have catched my attention and that I want to implement
in a library (here or elsewhere)


Part references and Links
-------------------------

### [Digital Potentiometers (POTs) | CAT5138](https://www.onsemi.com/products/signal-conditioning-control/digital-potentiometers-pots/cat5138) ###

CAT5136, CAT5137, and CAT5138 are a family of digital POTs operating like mechanical potentiometers in
various configurations. The tap points between the 127 equal resistive elements are connected to the wiper
output via CMOS switches. The switches are controlled by a 7-bit Wiper Control Register (WCR) via the I2C serial
bus. CAT5136 is configured as a variable resistor. CAT5137 and CAT5138 are resistive voltage dividers, with one
terminal of the potentiometer connected to GND. CAT5137 and CAT5138 have different device IDs, which makes it
possible to use both on the same I2C bus. Upon power-up, the WCR is set to mid-scale (1000000).

[Datasheet](https://www.onsemi.com/download/data-sheet/pdf/cat5136-d.pdf)


### [SRAM Memory | N01S830](https://www.onsemi.com/products/timing-logic-memory/memory/sram-memory/n01s830) ###

The onsemi serial SRAM family includes severalintegrated memory devices including this 1 Mb serially
accessedStatic Random Access Memory, internally organized as 128 K wordsby 8 bits. The devices are designed and
fabricated usingonsemi’s advanced CMOS technology to provide bothhigh-speed performance and low power. The
devices operate with asingle chip select (CS) input and use a simple Serial PeripheralInterface (SPI) protocol.
In SPI mode, a single data-in (SI) anddata-out (SO) line is used along with the clock (SCK) to access datawithin
the device. In DUAL mode, two multiplexed data-in/data-out(SIO0-SIO1) lines are used and in QUAD mode, four
multiplexeddata-in/data-out (SIO0-SIO3) lines are used with the clock to accessthe memory. The devices can
operate over a wide temperature range of−40°C to +85°C and are available in a 8-lead TSSOP package. The N01S830xA
device has two different variations, a HOLD version thatallows communication to the device to be paused and a
batteryback-up (BBU) version to be used with a battery to retain data whenpower is lost.

[Datasheet](https://www.onsemi.com/download/data-sheet/pdf/n01s830ha-d.pdf)


### [EEPROM Memory | CAT25M01](https://www.onsemi.com/products/timing-logic-memory/memory/eeprom-memory/cat25m01) ###

The CAT25M01 is a EEPROM Serial 1-Mb SPI device internally organized as 128Kx8 bits. This features a 256-byte
page write buffer and supports the Serial Peripheral Interface (SPI) protocol. The device is enabled through a
Chip Select (CS) input. In addition, the required bus signals are clock input (SCK), data input (SI) and data
output (SO) lines. The HOLD input may be used to pause any serial communication with the CAT25M01 device. The
device features software and hardware write protection, including partial as well as full array protection.

On-Chip ECC (Error Correction Code) makes the device suitable for high reliability applications.

[Datasheet](https://www.onsemi.com/download/data-sheet/pdf/cat25m01-d.pdf)


### [Voltage Controlled Oscillators (VCOs) | MC100EL1648](https://www.onsemi.com/products/timing-logic-memory/clock-generation/voltage-controlled-oscillators-vcos/mc100el1648) ###

The MC100EL1648 requires an external parallel tank circuit consisting of the inductor (L) and capacitor (C).
A varactor diode may be incorporated into the tank circuit to provide a voltage variable input for the
oscillator (VCO). This device may also be used in many other applications requiring a fixed frequency clock. The
MC100EL1648 is ideal in applications requiring a local oscillator. Systems include electronic test equipment and
digital high-speed telecommunications.

The MC100EL1648 is based on the VCO circuit topology of the MC1648. The MC100EL1648 uses advanced bipolar
process technology which results in a design which can operate at an extended frequency range.

The ECL output circuitry of the MC100EL1648 is not a traditional open emitter output structure and instead has
an on-chip termination resistor with a nominal value of 510 ohms. This facilitates direct ac-coupling of the
output signal into a transmission line. Because of this output configuration, an external pull-down resistor is
not required to provide the output with a dc current path. This output is intended to drive one ECL load. If the
user needs to fanout the signal, an ECL buffer such as the MC10EL16 Line Receiver/Driver should be used

**IMPORTANT: The MC100EL1648 is NOT useable as a crystal oscillator.**

[Datasheet](https://www.onsemi.com/download/data-sheet/pdf/mc100el1648-d.pdf)


[...]
