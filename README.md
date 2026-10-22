# ArduDimmer
## A quick and dirty Arduino based light dimmer

This is a project I created many years ago, which I recently discovered deep within a backup hard drive.

It is a light dimmer based on an Arduino board. It just use two pins, one for a user button and an PWM output. The input button is wired between the GPIO and GND and the PWM output goes to a MOSFET which switch a light bulb, LED, etc.

Usage is very simple: a short press turns the light on or off. Keeping the button pressed changes the light intensity.

The table[] array is a linearization according to the human eye response... sort of.

It was made for an Arduino Nano, but needing only two pins, propaby it can be ported to something smaller, like an ATtiny processor.

## License

ArduDimmer is made available under the GPLv3 license.
