# SPDX-License-Identifier: GPL-2.0

ifeq ($(CONFIG_CAMERA_DREAM),y)
ifeq ($(CONFIG_WLAN_REGION_CODE),200)
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_kor_05.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_kor_07.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_kor_09.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_kor_10.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_kor_11.dtb
else
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_eur_open_05.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_eur_open_07.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_eur_open_08.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_eur_open_09.dtb
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_eur_open_10.dtb
endif
endif

ifeq ($(CONFIG_CAMERA_DREAM2),y)
ifeq ($(CONFIG_WLAN_REGION_CODE),200)
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_kor_06.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_kor_07.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_kor_09.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_kor_10.dtb
else
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_eur_open_07.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_eur_open_08.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_eur_open_09.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_eur_open_10.dtb
endif
endif

ifeq ($(CONFIG_CAMERA_GREAT),y)
ifeq ($(CONFIG_WLAN_REGION_CODE),200)
dtb-$(CONFIG_CAMERA_GREAT) += exynos8895-greatlte_kor_02.dtb
dtb-$(CONFIG_CAMERA_GREAT) += exynos8895-greatlte_kor_06.dtb
else
dtb-$(CONFIG_CAMERA_GREAT) += exynos8895-greatlte_eur_open_02.dtb
dtb-$(CONFIG_CAMERA_GREAT) += exynos8895-greatlte_eur_open_06.dtb
endif
endif

always            := $(dtb-y) $(dtbo-y)
clean-files       := *.dtb*
