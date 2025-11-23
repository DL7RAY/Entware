# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2011-2025 Entware

include $(TOPDIR)/rules.mk

ARCH:=aarch64
BOARD:=aarch64-4.19
BOARDNAME:=Entware (aarch64, Linux 4.19.294)
CPU_TYPE:=cortex-a53
FEATURES:=gpio usb audio pci
KERNEL_PATCHVER:=4.19

include $(INCLUDE_DIR)/target.mk

define Target/Description
  Build Software Repository for ARM64 NASes, like QNAP and Synology.
endef

$(eval $(call BuildTarget))
