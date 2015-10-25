obj-y += lcd/
obj-y += pv/
obj-y += axipv/
obj-y += dsi/

ifeq ($(CONFIG_SPLIT_VIDEO_CMD_MODE_INTERFACE),y)
obj-$(CONFIG_FB_BRCM_KONA) += kona_fb_video.o
else
obj-$(CONFIG_FB_BRCM_KONA) += kona_fb.o
endif
