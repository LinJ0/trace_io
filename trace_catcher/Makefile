#  SPDX-License-Identifier: BSD-3-Clause
#  Copyright (C) 2015 Intel Corporation.
#  All rights reserved.
#

#SPDK_ROOT_DIR := $(CURDIR)/../../spdk

include $(SPDK_ROOT_DIR)/mk/spdk.common.mk
include $(SPDK_ROOT_DIR)/mk/spdk.modules.mk

APP = trace_catcher
SPDK_NO_LINK_ENV = 1

SPDK_LIB_LIST += trace_parser

CXX_SRCS := trace_catcher.cpp

include $(SPDK_ROOT_DIR)/mk/spdk.app_cxx.mk
