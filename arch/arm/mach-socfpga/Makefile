# SPDX-License-Identifier: GPL-2.0-only

pbl-$(CONFIG_ARCH_SOCFPGA_CYCLONE5) += cyclone5-init.o cyclone5-freeze-controller.o cyclone5-scan-manager.o cyclone5-system-manager.o
pbl-$(CONFIG_ARCH_SOCFPGA_CYCLONE5) += cyclone5-clock-manager.o
obj-$(CONFIG_ARCH_SOCFPGA_CYCLONE5) += cyclone5-generic.o nic301.o cyclone5-bootsource.o cyclone5-reset-manager.o

pbl-$(CONFIG_ARCH_SOCFPGA_ARRIA10) += arria10-xload.o \
				      arria10-xload-emmc.o
obj-pbl-$(CONFIG_ARCH_SOCFPGA_ARRIA10) += arria10-bootsource.o \
	    				  arria10-clock-manager.o \
					  arria10-generic.o \
					  arria10-reset-manager.o \
					  arria10-init.o \
					  arria10-sdram.o

ifdef CONFIG_ARCH_SOCFPGA_CYCLONE5
obj-$(CONFIG_ARCH_SOCFPGA_XLOAD) += xload.o
endif
