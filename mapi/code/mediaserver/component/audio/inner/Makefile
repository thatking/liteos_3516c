ifeq ($(MAPI_PARAM_FILE), ) 
    MAPI_PARAM_FILE:=../../../../../Makefile.param
	OSTYPE=HuaweiLite
    include $(MAPI_PARAM_FILE)
endif

#*************************************************************************
# all source file in this module
SRCS := src/hi_mapi_inner_audio_component.c


#*************************************************************************
TARGET := $(HIARCH)_mapi_inner_audio_component

CFLAGS += -I$(REL_INC)
CFLAGS += -I../include
CFLAGS += -I./include

$(warning AUDIO_PATH $(AUDIO_PATH))
#*************************************************************************
# compile linux or HuaweiLite
include $(PWD)/../../../Make.$(OSTYPE)