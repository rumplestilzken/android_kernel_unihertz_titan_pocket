subdir-ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include
subdir-ccflags-$(CONFIG_MACH_MT8167)+= -Werror -I$(srctree)/drivers/misc/mediatek/accdet/$(MTK_PLATFORM)

subdir-ccflags-y += -Wpointer-arith
#subdir-ccflags-y += -Werror -I$(srctree)/drivers/misc/mediatek/accdet/$(MTK_PLATFORM)
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6391)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6391
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6355)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6355
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6357)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6357
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6358)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6358
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6323)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6323
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6359)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6359
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6359P)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6359
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6390)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6357
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6771)+= -I$(srctree)/drivers/misc/mediatek/accdet/mt6771

obj-$(CONFIG_MTK_ACCDET) := accdet_drv.o


obj-$(CONFIG_MTK_PMIC_CHIP_MT6391) += mt6391/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6355) += mt6355/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6357) += mt6357/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6358) += mt6358/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6323) += mt6323/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6359) += mt6359/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6359P) += mt6359/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6390) += mt6357/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6771) += mt6771/
obj-$(CONFIG_MACH_MT8167) += mt8167/
