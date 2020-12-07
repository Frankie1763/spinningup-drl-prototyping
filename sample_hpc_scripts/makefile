clean:
	rm *.err *.out
plot_ant:
	python -m spinup.run plot -s 10 \
	../data/SAC_multistep_k1_ant-v2/ ../data/SAC_multistep_k5_ant-v2/ ../data/SAC_use_single_variant_multistep_k1_ant-v2/ ../data/SAC_use_single_variant_multistep_k5_ant-v2/ \
	--legend SAC MSAC-5 SAC-Single MSAC-Single-5 \
	--xlabel timestep \
	--value Performance \
	--ylabel Performance \

plot_ant_bias:
	python -m spinup.run plot -s 10 \
	../data/SAC_multistep_k1_ant-v2/ ../data/SAC_multistep_k5_ant-v2/ ../data/SAC_use_single_variant_multistep_k1_ant-v2/ ../data/SAC_use_single_variant_multistep_k5_ant-v2/ \
	--legend SAC MSAC-5 SAC-Single MSAC-Single-5 \
	--xlabel timestep \
	--value QBias \
	--ylabel QBias \

plot_hopper:
	python -m spinup.run plot -s 10 \
	../data/SAC_multistep_k1_hopper-v2/ ../data/SAC_multistep_k5_hopper-v2/ ../data/SAC_use_single_variant_multistep_k1_hopper-v2/ ../data/SAC_use_single_variant_multistep_k5_hopper-v2/ \
	--legend SAC MSAC-5 SAC-Single MSAC-Single-5 \
	--xlabel timestep \
	--value Performance \
	--ylabel Performance \

plot_hopper_bias:
	python -m spinup.run plot -s 10 \
	../data/SAC_multistep_k1_hopper-v2/ ../data/SAC_multistep_k5_hopper-v2/ ../data/SAC_use_single_variant_multistep_k1_hopper-v2/ ../data/SAC_use_single_variant_multistep_k5_hopper-v2/ \
	--legend SAC MSAC-5 SAC-Single MSAC-Single-5 \
	--xlabel timestep \
	--value QBias \
	--ylabel QBias \

plot_k_ant:
	python -m spinup.run plot -s 10 \
	../data/SAC_k_2_ant-v2/ ../data/SAC_k_8_ant-v2/ \
	--legend MSAC-2 MSAC-8 \
	--xlabel timestep \
	--value Performance \
	--ylabel Performance \

plot_k_ant_bias:
	python -m spinup.run plot -s 10 \
	../data/SAC_k_2_ant-v2/ ../data/SAC_k_8_ant-v2/ \
	--legend MSAC-2 MSAC-8 \
	--xlabel timestep \
	--value QBias \
	--ylabel QBias \

plot_k_hopper:
	python -m spinup.run plot -s 10 \
	../data/SAC_k_2_hopper-v2/ ../data/SAC_k_8_hopper-v2/ \
	--legend MSAC-2 MSAC-8 \
	--xlabel timestep \
	--value Performance \
	--ylabel Performance \

plot_k_hopper_bias:
	python -m spinup.run plot -s 10 \
	../data/SAC_k_2_hopper-v2/ ../data/SAC_k_8_hopper-v2/ \
	--legend MSAC-2 MSAC-8 \
	--xlabel timestep \
	--value QBias \
	--ylabel QBias \