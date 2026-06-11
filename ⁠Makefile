ARCHS = arm64
TARGET = iphone:clang:latest:14.0

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = MWEngine
MWEngine_FILES = Tweak.cpp
MWEngine_CXXFLAGS = -std=c++11 -I$(THEOS)/include -I./include
MWEngine_LDFLAGS = -L./lib -lopencv_core -lopencv_imgproc -ldlib

include $(THEOS)/makefiles/tweak.mk
