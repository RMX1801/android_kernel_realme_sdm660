#ifdef CONFIG_PRODUCT_REALME_RMX1801
#xiang.fei@PSW.MM.AudioDriver.SmartPA, 2017/01/13, Add for tfa9890
snd-soc-tfa98xx-objs := tfa98xx.o tfa_dsp.o tfa_container.o tfa9891_init.o tfa9887_init.o tfa9887B_init.o tfa9888_init.o tfa9890_init.o tfa9897_init.o tfa_debug.o
obj-y += snd-soc-tfa98xx.o

ifeq ($(CONFIG_ANDROID),y)
CFLAGS_tfa98xx.o += -DCONFIG_DEBUG_FS
CFLAGS_tfa_dsp.o += -DCONFIG_DEBUG_FS
endif
#endif /* CONFIG_PRODUCT_REALME_RMX1801 */
