# I2C-SignalTestJig
## License: CERN Open Hardware Licence v1.2

Test Jig for simple signal panels

An I2C slave board that drives 6x signal head drivers (effectively 3x IOB-Signal circuits)
in a form factor that mimics the panelization spacing of the simple signal boards.

This allows bulk testing after fabrication of an entire board in 2 (or 4) operations 
  * align a board with the pogo pins
  * press down on pins
  * observe the correct operation of the heads
     * mark any defective units
  * move panel to next set of contacts & repeat
