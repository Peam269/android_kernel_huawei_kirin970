# SPDX-License-Identifier: GPL-2.0
dtb-y := $(patsubst $(srctree)/$(src)/%.dts,%.dtb, \
	$(sort $(wildcard $(srctree)/$(src)/*/boards/*.dts)))
always := $(dtb-y)
clean-files := */boards/*.dtb
