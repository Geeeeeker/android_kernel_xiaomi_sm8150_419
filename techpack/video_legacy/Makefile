# SPDX-License-Identifier: GPL-2.0-only
# auto-detect subdirs
ifeq ($(CONFIG_ARCH_SM8150), y)
include $(srctree)/techpack/video_legacy/config/sdm845.conf
endif

ifeq ($(CONFIG_ARCH_SM8150), y)
LINUXINCLUDE    += -include $(srctree)/techpack/video_legacy/config/sdm845.h
endif

obj-y +=msm/
