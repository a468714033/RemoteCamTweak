ARCHS = arm64 arm64e
TARGET = iphone:clang:14.5:14.0

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = RemoteCamTweak

RemoteCamTweak_FILES = Tweak.xm
RemoteCamTweak_CFLAGS = -fobjc-arc
RemoteCamTweak_FRAMEWORKS = UIKit AVFoundation CoreVideo CoreMedia
RemoteCamTweak_LDFLAGS = -lsubstrate

include $(THEOS_MAKE_PATH)/tweak.mk
