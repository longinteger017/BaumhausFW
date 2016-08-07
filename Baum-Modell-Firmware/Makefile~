TARGET_CHIP := NRF51822_QFAA_CA
BOARD := BOARD_PCA10001

C_SOURCE_FILES += main.c
C_SOURCE_FILES += nrf_delay.c
C_SOURCE_FILES += neopixel.c

OUTPUT_FILENAME := main
SDK_PATH = ../NordicSemiconductor/SDK_6.1.0/


#Uncomment correct line if you have s110 programmed on the chip.
DEVICE_VARIANT := xxaa
#DEVICE_VARIANT := xxab

#USE_SOFTDEVICE := s110
#USE_SOFTDEVICE := s210

include $(SDK_PATH)Source/templates/gcc/Makefile.common
