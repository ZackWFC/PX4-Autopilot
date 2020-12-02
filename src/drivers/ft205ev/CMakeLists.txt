px4_add_module(
	MODULE drivers__ft205ev
	MAIN ft205ev
	COMPILE_FLAGS
		-Wno-cast-align # TODO: fix and enable
	SRCS
		ft205ev.cpp
	MODULE_CONFIG
		module.yaml
	)
