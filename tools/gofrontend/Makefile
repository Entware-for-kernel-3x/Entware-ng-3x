#
# Copyright (C) 2014 Qualcomm-Atheros Inc.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=gofrontend
PKG_VERSION:=1.8rc1

PKG_SOURCE_PROTO:=git
PKG_SOURCE_URL:=https://github.com/golang/gofrontend.git
PKG_SOURCE_VERSION:=2b3d389f961b8461b3fdf42318a628f68b56f8b1
PKG_SOURCE_SUBDIR:=$(PKG_NAME)-$(PKG_VERSION)

PKG_SOURCE:=$(PKG_NAME)-$(PKG_VERSION).tar.gz
HOST_BUILD_DIR=$(BUILD_DIR_HOST)/$(PKG_NAME)
HOST_UNPACK:=gzip -dc $(DL_DIR)/$(PKG_SOURCE) | tar -C $(HOST_BUILD_DIR) --strip-components=1 -xf -



PKG_BUILD_PARALLEL:=1

include $(INCLUDE_DIR)/host-build.mk

define Host/Compile
endef

define Host/Install
endef

$(eval $(call HostBuild))
