IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-lfe-motion
PROJECT_PATH := ../../plc-lfe-motion/plc-lfe-motion.tsproj
PLC = lfe_motion

PYTMC_OPTS :=
PREFIX = PLC:LFE:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
