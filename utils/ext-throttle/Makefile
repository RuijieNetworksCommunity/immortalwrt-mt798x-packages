#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-throttle
PKG_VERSION:=1.000
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/ext-throttle
  SECTION:=utils
  CATEGORY:=ROOter
  SUBMENU:=Optional Applications
  TITLE:=support for Traffic Throttling
  PKGARCH:=all
endef

define Package/ext-throttle/description
  Helper scripts to enable Traffic Throttling
endef


define Build/Compile
endef

define Package/ext-throttle/install
	$(CP) ./files/* $(1)/
endef

$(eval $(call BuildPackage,ext-throttle))
