# _____     ___ ____     ___ ____
#  ____|   |    ____|   |        | |____|
# |     ___|   |____ ___|    ____| |    \    PS2DEV Open Source Project.
#-----------------------------------------------------------------------
# Copyright 2001-2004, ps2dev - http://www.ps2dev.org
# Licenced under Academic Free License version 2.0
# Review ps2sdk README & LICENSE files for further details.

# IOP_CFLAGS += -DDEBUG -DDEBUG_EXTREME

IOP_CFLAGS += -mno-check-zero-division # -DSIF_CALLBACKS_12_13

IOP_INCS += -I$(PS2SDKSRC)/iop/iLink/iLinkman/include

IOP_OBJS = sbp2_driver.o imports.o main.o scsi.o fat_write.o fs_driver.o scache.o fat_driver.o part_driver.o

include $(PS2SDKSRC)/Defs.make
include $(PS2SDKSRC)/iop/Rules.bin.make
include $(PS2SDKSRC)/iop/Rules.make
include $(PS2SDKSRC)/iop/Rules.release
