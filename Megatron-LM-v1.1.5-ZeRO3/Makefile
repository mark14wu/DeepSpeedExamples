clean:
	rm report*

reset:
	rm -rf ssd1

run:
	sh examples/ds_pretrain_gpt2.sh

profile:
	nsys profile --stats=true -t cuda sh examples/ds_pretrain_gpt2.sh
