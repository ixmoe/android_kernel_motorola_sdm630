#
# Makefile for the FTS touchscreen driver.
#
ccflags-y += -Idrivers/input/touchscreen/st/fts_lib
obj-$(CONFIG_TOUCHSCREEN_ST_I2C) += ftsCompensation.o \
	ftsCrossCompile.o ftsError.o ftsFrame.o ftsIO.o ftsTest.o \
	ftsTime.o ftsTool.o ftsFlash.o ftsGesture.o
