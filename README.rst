========
gpioone
========

A simple module to control and interface to things connected  to the GPIO pins on the Raspberry Pi.

based on GPIOZero created by `Ben Nuttall`_ of the `Raspberry Pi Foundation`_, `Dave Jones`_, and
other contributors

Latest release
==============

Their is no release yet

About
=====

With very little code, you can quickly get going connecting your physical
components together::

    import gpioone as gp
    gp.pinnames(BCM) // not needed if using physical pin numbers but included for Cambridge compatibility
    led = gp.pin(11) // pins 11,12,13,15,18 are defaulted as output pins for controlling things
    button = gp.pin(7) // all other pins are defaulted to inputs

    while true:
      if button.pressed:
        led.on()
      else:
        led.off()

Install
=======

 Intstall not yet operational

Documentation
=============

Not done

Development
===========

This project is being developed on `GitHub`_. Join in:

* Provide suggestions, report bugs and ask questions as `Issues`_
* Contribute to the code


Contributors
============

- `Simon Walters`_ (project maintainer)

