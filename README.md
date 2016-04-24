# softbus
Software drivers for various serial bus systems

This is a placeholder for software (bit-bashed) drivers for various serial bus systems.
Such as SPI, I2C, OneWire, UART and others. All will be written in C.

Most of the work behind this is done already in other projects of mine, but I plan to
pull all the work into this single repo as an upstream master, and then downstream it
into the other projects.

The reason for putting SPI/I2C and other busses in a single repo/package, is that there
are some support files (such as for debug and delay generation) that it is convenient
to share as a single package.

Here is where all the 'bits' are at the moment:

TRACE: https://github.com/whaleygeek/pyenergenie/blob/master/src/energenie/drv/trace.h

DELAY: https://github.com/whaleygeek/pyenergenie/blob/master/src/energenie/drv/delay_posix.c

GPIO: https://github.com/whaleygeek/pyenergenie/blob/master/src/energenie/drv/gpio_sim.c

SPI: https://github.com/whaleygeek/pyenergenie/blob/master/src/energenie/drv/spis.c

I2C: http://blog.whaleygeek.co.uk/raspberry-pi-rfid-tag-reader/

David Whale

@whaleygeek

April 2016

