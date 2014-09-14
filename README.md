Arduino-SPI-over-RS-485-Shield
==============================

An Arduino shield that converts the SPI signals from the Arduino to RS-485 for communications over long distances. If the distance is long enough to where the delay caused by the wire and transceivers causes the SPI communications to get out of sync there is a second SPI channel that can act as an slave device and receive the data back from the delayed SPI. There is also an LCD display and 5 button D-Pad for a control interface.
