SUBDIRS = gametest spacecraft controller_test gamestate_test gameoflife usb_keyboard

SELF_DIR := $(dir $(lastword $(MAKEFILE_LIST)))
include $(addprefix $(SELF_DIR),$(addsuffix /Makefile,$(SUBDIRS)))
