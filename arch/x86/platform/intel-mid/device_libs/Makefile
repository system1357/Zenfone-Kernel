CFLAGS_platform_clv_regulator.o			:= -Werror
CFLAGS_platform_mrfl_regulator.o		:= -Werror

# IPC Devices
ifndef CONFIG_CRASH_DUMP
obj-$(subst m,y,$(CONFIG_SND_BYT_MACHINE))				+= platform_byt_audio.o
obj-y									+= platform_mrfld_audio.o
obj-y									+= platform_ipc.o
obj-y									+= platform_scu_mip.o
obj-y									+= platform_msic.o
obj-y									+= platform_msic_audio.o
obj-y									+= platform_msic_gpio.o
obj-y									+= platform_msic_ocd.o
obj-y									+= platform_tc35876x.o
obj-y									+= platform_ctp_audio.o
obj-y									+= platform_sst_audio.o
obj-y									+= platform_soc_thermal.o
endif
obj-y									+= pci/
obj-$(subst m,y,$(CONFIG_X86_MDFLD))					+= platform_clv_regulator.o
obj-$(subst m,y,$(CONFIG_X86_MRFLD))					+= platform_mrfl_regulator.o
obj-$(subst m,y,$(CONFIG_MSIC_GPADC))					+= platform_msic_adc.o
obj-$(subst m,y,$(CONFIG_BATTERY_INTEL_MDF))				+= platform_msic_battery.o
obj-$(subst m,y,$(CONFIG_INTEL_MID_POWER_BUTTON))			+= platform_msic_power_btn.o
obj-$(subst m,y,$(CONFIG_GPIO_INTEL_PMIC))				+= platform_pmic_gpio.o
obj-$(subst m,y,$(CONFIG_MID_PWM))                                      += platform_mid_pwm.o
obj-$(subst m,y,$(CONFIG_INTEL_MFLD_THERMAL))				+= platform_msic_thermal.o
obj-$(subst m,y,$(CONFIG_SENSORS_THERMAL_MRFLD))			+= platform_mrfl_thermal.o
ifdef CONFIG_INTEL_BYT_THERMAL
obj-$(subst m,y,$(CONFIG_INTEL_BYT_THERMAL))				+= platform_byt_thermal.o
else
obj-$(subst m,y,$(CONFIG_INTEL_BYT_EC_THERMAL))				+= platform_byt_thermal.o
endif
obj-$(subst m,y,$(CONFIG_SENSORS_MID_VDD))				+= platform_msic_vdd.o
obj-$(subst m,y,$(CONFIG_SENSORS_MRFL_OCD))				+= platform_mrfl_ocd.o
obj-$(subst m,y,$(CONFIG_PMIC_CCSM))                                    += platform_mrfl_pmic.o
obj-$(subst m,y,$(CONFIG_I2C_PMIC))                                    += platform_mrfl_pmic_i2c.o
obj-$(subst m,y,$(CONFIG_INTEL_SCU_FLIS))				+= platform_scu_flis.o
obj-$(subst m,y,$(CONFIG_IIO_BASINCOVE_GPADC))				+= platform_bcove_adc.o
obj-$(subst m,y,$(CONFIG_VLV2_PLAT_CLK))				+= platform_vlv2_plat_clk.o
# I2C Devices
obj-$(subst m,y,$(CONFIG_I2C_DESIGNWARE_PCI))				+= platform_dw_i2c.o
obj-$(subst m,y,$(CONFIG_SENSORS_EMC1403))				+= platform_emc1403.o
obj-$(subst m,y,$(CONFIG_SENSORS_HMC5883))				+= platform_hmc5883.o
obj-$(subst m,y,$(CONFIG_SENSORS_LIS3LV02D))				+= platform_lis331.o
obj-$(subst m,y,$(CONFIG_GPIO_PCA953X))					+= platform_max7315.o
obj-$(subst m,y,$(CONFIG_SENSORS_MPU3050))				+= platform_mpu3050.o
obj-$(subst m,y,$(CONFIG_SENSORS_MPU6500)) 				+= platform_mpu6500.o
obj-$(subst m,y,$(CONFIG_SENSORS_LTR502ALS))				+= platform_ltr502als.o
obj-$(subst m,y,$(CONFIG_GPIO_PCA953X))					+= platform_tca6416.o
obj-$(subst m,y,$(CONFIG_SENSORS_KXTJ9))                                += platform_accel.o
obj-$(subst m,y,$(CONFIG_SENSORS_AK09911))                              += platform_akm09911.o
obj-$(subst m,y,$(CONFIG_SENSORS_AK09911_a600cg))                              += platform_akm09911.o
obj-$(subst m,y,$(CONFIG_SENSORS_CM3628)) 				+= platform_cm3628.o
ifdef CONFIG_BATTERY_MAX17042
obj-$(subst m,y,$(CONFIG_BATTERY_MAX17042))				+= platform_max17042.o
else
obj-$(subst m,y,$(CONFIG_BATTERY_MAX17050))				+= platform_max17042.o
endif
obj-$(subst m,y,$(CONFIG_BYT_ULPMC_BATTERY))				+= platform_ulpmc_battery.o
obj-$(subst m,y,$(CONFIG_BYT_FFRD8_CHARGER))				+= platform_byt_ffrd8_charger.o
obj-$(subst m,y,$(CONFIG_EXTCON_FSA9285))				+= platform_fsa9285.o
obj-$(subst m,y,$(CONFIG_TOUCHSCREEN_ATMEL_MXT224))			+= platform_mxt224.o
obj-$(subst m,y,$(CONFIG_A1026))					+= platform_a1026.o
obj-$(subst m,y,$(CONFIG_SENSORS_APDS990X))				+= platform_apds990x.o
obj-$(subst m,y,$(CONFIG_CHARGER_BQ24192))				+= platform_bq24192.o
obj-$(subst m,y,$(CONFIG_CHARGER_SMB347))				+= platform_smb347.o
obj-$(subst m,y,$(CONFIG_SENSORS_L3G4200D_POLL))			+= platform_l3g4200d.o
obj-$(subst m,y,$(CONFIG_SENSORS_LIS3DH_ACC))				+= platform_lis3dh.o
obj-$(subst m,y,$(CONFIG_SENSORS_LSM303_MAG))				+= platform_lsm303.o
obj-$(subst m,y,$(CONFIG_PN544_NFC))					+= platform_pn544.o
obj-$(subst m,y,$(CONFIG_PN544_NFC_FORK))				+= platform_pn544.o
obj-$(subst m,y,$(CONFIG_SENSORS_MS5607))				+= platform_ms5607.o
ifdef CONFIG_TOUCHSCREEN_SYNAPTICS_RMI4_I2C
obj-$(subst m,y,$(CONFIG_TOUCHSCREEN_SYNAPTICS_RMI4_I2C))              += platform_rmi4.o
else
obj-$(subst m,y,$(CONFIG_TOUCHSCREEN_SYNAPTICS_I2C_RMI4))              += platform_rmi4.o
endif
obj-$(subst m,y,$(CONFIG_BQ24261_CHARGER))                            += platform_bq24261.o
obj-$(subst m,y,$(CONFIG_TOUCHSCREEN_R69001_I2C))			+= platform_r69001.o
obj-$(subst m,y,$(CONFIG_SND_SOC_WM5102))				+= platform_wm5102.o
obj-$(subst m,y,$(CONFIG_SND_SOC_CS42L73))                              += platform_cs42l73.o
obj-$(subst m,y,$(CONFIG_SND_SOC_WM8994))				+= platform_wm8994.o
ifdef CONFIG_TOUCHSCREEN_SYNAPTICS_DSX_I2C
obj-$(subst m,y,$(CONFIG_TOUCHSCREEN_SYNAPTICS_DSX_I2C))                += platform_synaptics_dsx.o
endif
# Camera
obj-$(subst m,y,$(CONFIG_VIDEO_ATOMISP_TMP))				+= platform_camera.o
ifdef CONFIG_VIDEO_ATOMISP_TMP
obj-$(subst m,y,$(CONFIG_VIDEO_MT9E013))				+= platform_mt9e013.o
obj-$(subst m,y,$(CONFIG_VIDEO_MT9D113))				+= platform_mt9d113.o
obj-$(subst m,y,$(CONFIG_VIDEO_MT9M114))				+= platform_mt9m114.o
obj-$(subst m,y,$(CONFIG_VIDEO_MT9V113))				+= platform_mt9v113.o
obj-$(subst m,y,$(CONFIG_VIDEO_OV8830))					+= platform_ov8830.o
obj-$(subst m,y,$(CONFIG_VIDEO_IMX))					+= platform_imx175.o
obj-$(subst m,y,$(CONFIG_VIDEO_IMX))					+= platform_imx135.o
obj-$(subst m,y,$(CONFIG_VIDEO_IMX))					+= platform_imx132.o
obj-$(subst m,y,$(CONFIG_VIDEO_IMX))					+= platform_imx134.o
obj-$(subst m,y,$(CONFIG_VIDEO_HM2056)) 				+= platform_hm2056.o
obj-$(subst m,y,$(CONFIG_VIDEO_GC0339)) 				+= platform_gc0339.o
obj-$(subst m,y,$(CONFIG_VIDEO_IMX))					+= platform_imx111.o
obj-$(subst m,y,$(CONFIG_VIDEO_IMX219))					+= platform_imx219.o
obj-$(subst m,y,$(CONFIG_VIDEO_MN34130))                                += platform_mn34130.o
obj-$(subst m,y,$(CONFIG_VIDEO_S5K8AAY))				+= platform_s5k8aay.o
obj-$(subst m,y,$(CONFIG_VIDEO_OV9724))					+= platform_ov9724.o
obj-$(subst m,y,$(CONFIG_VIDEO_OV2722))					+= platform_ov2722.o
obj-$(subst m,y,$(CONFIG_VIDEO_LM3554))					+= platform_lm3554.o
obj-$(subst m,y,$(CONFIG_VIDEO_LM3559))					+= platform_lm3559.o
endif
# SPI Devices
obj-$(subst m,y,$(CONFIG_SERIAL_MRST_MAX3110))				+= platform_max3111.o
# HSI Devices
obj-$(subst m,y,$(CONFIG_HSI_ARASAN))					+= platform_hsi_modem.o
obj-$(subst m,y,$(CONFIG_HSI_ARASAN))					+= platform_ffl_modem.o
obj-$(subst m,y,$(CONFIG_HSI_ARASAN))					+= platform_edlp_modem.o
obj-$(subst m,y,$(CONFIG_HSI_ARASAN))					+= platform_edlp_fast.o
obj-$(subst m,y,$(CONFIG_HSI_ARASAN))					+= platform_logical_modem.o
# Modem control Device
obj-y									+= platform_modem_ctrl.o
# UART Devices
obj-$(subst m,y,$(CONFIG_SERIAL_MFD_HSU))				+= platform_hsu.o
# MISC Devices
obj-$(subst m,y,$(CONFIG_KEYBOARD_GPIO))				+= platform_gpio_keys.o
obj-$(subst m,y,$(CONFIG_SWITCH_MID))					+= platform_switch_mid.o
obj-$(subst m,y,$(CONFIG_SWITCH_MID_USER_NOTIFY))			+= platform_switch_mid_user_notify.o
obj-$(subst m,y,$(CONFIG_EXTCON_MID))					+= platform_extcon_mid.o
obj-$(subst m,y,$(CONFIG_I2C_GPIO))					+= platform_i2c_gpio.o
# WIFI
#obj-$(subst m,y,$(CONFIG_WL12XX_PLATFORM_DATA))				+= platform_wl12xx.o
obj-$(subst m,y,$(CONFIG_WIFI_PLATFORM_DATA))				+= platform_wifi.o
# Bluetooth
obj-$(subst m,y,$(CONFIG_TI_ST))					+= platform_btwilink.o
obj-$(subst m,y,$(CONFIG_TI_ST_FORK))					+= platform_btwilink.o
ifndef CONFIG_ACPI
obj-$(subst m,y,$(CONFIG_BCM_BT_LPM))					+= platform_btlpm.o
endif
# GPS
obj-$(subst m,y,$(CONFIG_INTEL_MID_GPS))				+= platform_gps.o
# Pin Control
obj-$(subst m,y,$(CONFIG_PINCTRL_INTEL_MID))				+= platform_mid_pinctrl.o
obj-$(subst m,y,$(CONFIG_INTEL_MID_OSNIB_ILB))				+= platform_osnib_ilb.o

obj-$(subst m,y,$(CONFIG_SCU_LOGGING))					+= platform_scu_log.o
# Panel Control Device
obj-$(subst m,y,$(CONFIG_DRM_MRFLD))					+= platform_panel.o

# Flash Driver IC
obj-$(subst m,y,$(CONFIG_VIDEO_RT8515))					+= platform_rt8515.o

# Charger Device
obj-$(subst m,y,$(CONFIG_A500CG_BATTERY_SMB347))			+= platform_a500cg_smb347.o

# LED driver
obj-$(subst m,y,$(CONFIG_LEDS_ASUS))					+= platform_leds_asus.o

ifeq ($(BT_UART_PORT), BCM2076_EVB)
KBUILD_CFLAGS += -DBCM2076_UART_PORT3
else 
KBUILD_CFLAGS += -DBCM2076_UART_PORT0
endif
