# SPDX-License-Identifier: GPL-2.0

obj-$(CONFIG_KFENCE) := core.o report.o

CFLAGS_kfence_test.o := -fno-omit-frame-pointer -fno-optimize-sibling-calls
obj-$(CONFIG_KFENCE_KUNIT_TEST) += kfence_test.o
