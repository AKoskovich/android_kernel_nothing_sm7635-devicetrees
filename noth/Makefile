VOLCANO_BASE_DTB += ../qcom/volcano.dtb

NOTH_VOLCANO_BOARDS += \
	asteroids-base-overlay.dtbo \
	asteroids-pro-overlay.dtbo

dtb-y += $(NOTH_VOLCANO_BOARDS) $(VOLCANO_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
