# marlin_2.0_tmc2130_bltouch_tronxy_x8

my personal config

printer: tronxy x8 (abet a8 clone)

tmc2130 drivers (SPI)

mks gen 1.4 (mks 1.3 is selected in marlin configuration.h but pins are configured for 1.4)

bltouch

removed hal folders so that the firmware actually compiles: https://github.com/MarlinFirmware/Marlin/issues/16105
