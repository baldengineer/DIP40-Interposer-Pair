## DIP40 Interposer Board Pair
This adapter makes it easier to probe a DIP-40 (0.6" wide) chip using a logic analyzer or mixed-signal oscilloscope. The boards breakout each of the signals.

Originally this was designed to test the Z80 and ULA chips of a ZX-81. However, there is nothing chip-specific in this design.

Currently, the boards are untested and being manufactured.

## PCB-Side Board
This board plugs into the PCB or the socket on the PCB. It should have a 02x20 pin-socket in the middle facing "up". Two pin-headers go near the outside edges.

The rendered image shows right-angle and straight connectors. It is not clear yet which is a better option. Consider how your probes connect to the pins.

## Chip Carrier Board
The chip under test plugs into this board. Ideally, you probably want to use a socket to connect a 0.6" wide DIP-40 chip. Right-angled pin-headers allow for a clean mating. If you use "straight" header-pins, half of the logic probe pins are blocked.

## Bald Engineer on Twitch
This board was designed, built, and tested live with the Bald Engineer. Check out his electronics live stream at: [https://twitch.tv/baldengineer](https://twitch.tv/baldengineer).