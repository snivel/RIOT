APPLICATION = driver_hd44780
include ../Makefile.tests_common

# the stm32f4discovery does not have the arduino pinout
BOARD_BLACKLIST := stm32f4discovery
# currently the test provides config params for arduinos only
FEATURES_REQUIRED += arduino

USEMODULE += hd44780

test:
	tests/01-run.py

include $(RIOTBASE)/Makefile.include
