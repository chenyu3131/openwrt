# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for VSFTPD
LUCI_DEPENDS:=+vsftpd-tls
LUCI_PKGARCH:=all
PKG_VERSION:=1.0
PKG_RELEASE:=5

define Package/luci-app-vsftpd/conffiles
/etc/config/vsftpd
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature

