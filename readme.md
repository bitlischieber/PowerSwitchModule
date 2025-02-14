# Power Switch Modul

Saves battery by disconnecting you microcontroller or electronics module from the power source.

- Connect _SW_ON_ to the input power source to the to enable power on the _VCC_ net.
- If you power a micro, use a GPIO set to high on _PWR_ON_ to keep the power on.
    - In this way, for _SW_ON_ a momentary switch can be used.
    - To power off, set _SW_ON_ to low (selfkill of the micro).

The board can be ordered (assembled) e.g. from (JLC PCB)[https://jlcpcb.com/].

Increase C1 if the startup time of the micro is too slow.
