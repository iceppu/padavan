RT_DRV_DIR  := rt5592
RT_DRV_PATH := ../$(RT_DRV_DIR)
RT_DRV_NAME := rt5592_ap

obj-$(CONFIG_RT5592_AP) += $(RT_DRV_NAME).o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_md5.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_sha2.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_hmac.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_aes.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_arc4.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/mlme.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_wep.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/action.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/ba_action.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_data.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rtmp_init.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rtmp_init_inf.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_tkip.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_aes.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_sync.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_sanity.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_info.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_cfg.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_wpa.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_radar.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/spectrum.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rtmp_timer.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rt_channel.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_profile.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_asic.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_cmd.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rtmp_mcu.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_mac_pci.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_data_pci.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rt_os_util.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/ps.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/uapsd.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/ee_prom.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/ee_efuse.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/ee_flash.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/eeprom.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rt_rf.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/rate_ctrl/ra_ctrl.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/rate_ctrl/alg_legacy.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_assoc.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_auth.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_connect.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_mlme.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_sanity.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_sync.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_wpa.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_data.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_autoChSel.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_qload.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_cfg.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_proc.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_main_dev.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_pci_rbus.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_profile.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_linux.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_rbus_pci_util.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/rt_rbus_pci_drv.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/ap_ioctl.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/os/linux/pci_main_dev.o

### RT5592
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/chips/rtmp_chip.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/chips/rt30xx.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/chips/rt5592.o
ifeq ($(CONFIG_RT5592_AP_ATE),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ate/chips/rt30xx_ate.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ate/chips/rt5592_ate.o
endif

ifeq ($(CONFIG_RT5592_AP_ATE),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ate/common/rt_ate.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ate/common/ate_pci.o
ifeq ($(CONFIG_RT5592_AP_QA),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ate/common/rt_qa.o
endif
endif

ifeq ($(CONFIG_RT5592_AP_VIDEO_TURBINE),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_video.o
endif

ifeq ($(CONFIG_RT5592_AP_LED),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/rt_led.o
endif

ifeq ($(CONFIG_RT5592_AP_WSC),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/wsc.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/wsc_tlv.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_dh.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/wsc_ufd.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/crypt_biginteger.o
ifeq ($(CONFIG_RT5592_AP_WSC_V2),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/wsc_v2.o
endif
endif

ifeq ($(CONFIG_RT5592_AP_WDS),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_wds.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_wds_inf.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/client_wds.o
endif

ifeq ($(CONFIG_RT5592_AP_MBSS),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_mbss.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_mbss_inf.o
endif

ifeq ($(CONFIG_RT5592_AP_APCLI),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_apcli.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_apcli_inf.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/apcli_assoc.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/apcli_auth.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/apcli_ctrl.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/apcli_sync.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_mat.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_mat_iparp.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_mat_pppoe.o
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_mat_ipv6.o
endif

ifeq ($(CONFIG_RT5592_AP_IGMP_SNOOP),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/igmp_snoop.o
endif

ifeq ($(CONFIG_RT5592_AP_NETIF_BLOCK),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/netif_block.o
endif

ifeq ($(CONFIG_RT5592_AP_DLS),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_dls.o
endif

ifeq ($(CONFIG_RT5592_AP_IDS),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/ap/ap_ids.o
endif

ifeq ($(CONFIG_RT5592_AP_WAPI),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/wapi.o
endif

ifeq ($(CONFIG_RT5592_AP_DFS),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_dfs.o
endif

ifeq ($(CONFIG_RT5592_AP_BRIDGE_FASTPATH),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/br_ftph.o
endif

ifeq ($(CONFIG_RT5592_AP_CARRIER),y)
$(RT_DRV_NAME)-objs += $(RT_DRV_PATH)/common/cmm_cs.o
endif


###################
#  CFLAGS
###################
EXTRA_CFLAGS  = -Wall -Wstrict-prototypes -Wno-trigraphs
EXTRA_CFLAGS += -Idrivers/net/wireless/$(RT_DRV_DIR)/include
ifeq ($(CONFIG_RT5592_AP_ATE),y)
EXTRA_CFLAGS += -Idrivers/net/wireless/$(RT_DRV_DIR)/ate/include
endif
EXTRA_CFLAGS += -DAGGREGATION_SUPPORT -DPIGGYBACK_SUPPORT -DWMM_SUPPORT -DLINUX
EXTRA_CFLAGS += -DCONFIG_AP_SUPPORT -DAP_SCAN_SUPPORT -DUAPSD_SUPPORT -DDOT11_N_SUPPORT -DDOT1X_SUPPORT
EXTRA_CFLAGS += -DRTMP_MAC_PCI -DRTMP_PCI_SUPPORT -DRTMP_RF_RW_SUPPORT
EXTRA_CFLAGS += -DSTATS_COUNT_SUPPORT -DENHANCED_STAT_DISPLAY
EXTRA_CFLAGS += -DRSSI_FEEDBACK
EXTRA_CFLAGS += -DRESOURCE_PRE_ALLOC

ifeq ($(CONFIG_RT_FIRST_CARD),2860)
EXTRA_CFLAGS += -DRT_SOC_SUPPORT
endif

ifeq ($(CONFIG_RT_FIRST_CARD),5592)
EXTRA_CFLAGS += -DRT_IFNAME_1ST
ifeq ($(CONFIG_RT_FIRST_CARD_EEPROM),"efuse")
EXTRA_CFLAGS += -DRTMP_EFUSE_SUPPORT
else
EXTRA_CFLAGS += -DRTMP_FLASH_SUPPORT
endif
else
ifeq ($(CONFIG_RT_SECOND_CARD_EEPROM),"efuse")
EXTRA_CFLAGS += -DRTMP_EFUSE_SUPPORT
else
EXTRA_CFLAGS += -DRTMP_FLASH_SUPPORT
endif
endif

ifeq ($(CONFIG_RT5592_AP_READ_MAC_FROM_MTD),y)
EXTRA_CFLAGS += -DREAD_MAC_FROM_EEPROM
endif

# do not lock CountryRegion from EEPROM
EXTRA_CFLAGS += -DEEPROM_COUNTRY_UNLOCK

# provide roaming support
#EXTRA_CFLAGS += -DIAPP_SUPPORT

# provide information on the current STA population and traffic levels in the QBSS
#EXTRA_CFLAGS += -DAP_QLOAD_SUPPORT -DQLOAD_FUNC_BUSY_TIME_STATS

ifneq ($(CONFIG_RA_HW_NAT_WIFI),y)
EXTRA_CFLAGS += -DCONFIG_RA_NAT_NONE
endif

ifeq ($(CONFIG_RA_NETWORK_WORKQUEUE_BH),y)
EXTRA_CFLAGS += -DWORKQUEUE_BH
endif

### RT5592
EXTRA_CFLAGS += -DRT30xx -DRT5592
EXTRA_CFLAGS += -DA_BAND_SUPPORT
EXTRA_CFLAGS += -DRX_DMA_SCATTER
EXTRA_CFLAGS += -DVCORECAL_SUPPORT
EXTRA_CFLAGS += -DIQ_CAL_SUPPORT
EXTRA_CFLAGS += -DRTMP_TEMPERATURE_COMPENSATION
#EXTRA_CFLAGS += -DSPECIFIC_BCN_BUF_SUPPORT
ifeq ($(CONFIG_RT5592_AP_EP_SUPPORT),y)
EXTRA_CFLAGS += -DRT5592EP_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_DBG),y)
EXTRA_CFLAGS += -DDBG
EXTRA_CFLAGS += -DSYSTEM_LOG_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_ATE),y)
EXTRA_CFLAGS += -DRALINK_ATE -DCONFIG_RT2880_ATE_CMD_NEW
ifeq ($(CONFIG_RT5592_AP_QA),y)
EXTRA_CFLAGS += -DRALINK_QA
endif
endif

ifeq ($(CONFIG_RT5592_AP_DLS),y)
EXTRA_CFLAGS += -DQOS_DLS_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_IDS),y)
EXTRA_CFLAGS += -DIDS_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_WAPI),y)
EXTRA_CFLAGS += -DWAPI_SUPPORT -DEXPORT_SYMTAB
endif

ifeq ($(CONFIG_RT5592_AP_GREENAP),y)
EXTRA_CFLAGS += -DGREENAP_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_MCAST_RATE_SPECIFIC),y)
EXTRA_CFLAGS += -DMCAST_RATE_SPECIFIC
endif

ifeq ($(CONFIG_RT5592_AP_80211N_DRAFT3),y)
EXTRA_CFLAGS += -DDOT11N_DRAFT3
endif

ifeq ($(CONFIG_RT5592_AP_LED),y)
EXTRA_CFLAGS += -DLED_CONTROL_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_WSC),y)
EXTRA_CFLAGS += -DWSC_AP_SUPPORT
ifeq ($(CONFIG_RT5592_AP_WSC_V2),y)
EXTRA_CFLAGS += -DWSC_V2_SUPPORT
endif
ifeq ($(CONFIG_RT5592_AP_LED),y)
EXTRA_CFLAGS += -DWSC_LED_SUPPORT
endif
endif

ifeq ($(CONFIG_RT5592_AP_LED_SOFT),y)
EXTRA_CFLAGS += -DLED_SOFT_SUPPORT
EXTRA_CFLAGS += -DLED_SOFT_BLINK_GPIO=$(CONFIG_RT5592_AP_LED_SOFT_GPIO)
endif

ifeq ($(CONFIG_RT5592_AP_LLTD),y)
EXTRA_CFLAGS += -DLLTD_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_WDS),y)
EXTRA_CFLAGS += -DWDS_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_MBSS),y)
EXTRA_CFLAGS += -DMBSS_SUPPORT
ifeq ($(CONFIG_RT5592_AP_MBSS_NEW_MBSSID_MODE),y)
EXTRA_CFLAGS += -DNEW_MBSSID_MODE
endif
endif

ifeq ($(CONFIG_RT5592_AP_APCLI),y)
EXTRA_CFLAGS += -DAPCLI_SUPPORT -DMAT_SUPPORT
EXTRA_CFLAGS += -DAPCLI_AUTO_CONNECT_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_IGMP_SNOOP),y)
EXTRA_CFLAGS += -DIGMP_SNOOP_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_NETIF_BLOCK),y)
EXTRA_CFLAGS += -DBLOCK_NET_IF
endif

ifeq ($(CONFIG_RT5592_AP_VIDEO_TURBINE),y)
EXTRA_CFLAGS += -DVIDEO_TURBINE_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_EXT_CHANNEL_LIST),y)
EXTRA_CFLAGS += -DEXT_BUILD_CHANNEL_LIST
endif

ifeq ($(CONFIG_RT5592_AP_SINGLE_SKU),y)
EXTRA_CFLAGS += -DSINGLE_SKU
endif

ifeq ($(CONFIG_RT5592_AP_MC_SUPPORT),y)
EXTRA_CFLAGS += -DMULTIPLE_CARD_SUPPORT
endif

ifeq ($(CONFIG_RT5592_AP_BRIDGE_FASTPATH),y)
EXTRA_CFLAGS += -DBG_FT_SUPPORT
endif


clean:
	@rm -f `find ./ -name "*.o.cmd"`
	@rm -f `find ./ -name "*.ko"`
	@rm -f `find ./ -name "*.o"`
