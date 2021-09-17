clean:
	rm report*

reset:
	rm -rf ssd1

run:
	sh examples/ds_pretrain_gpt2.sh

profile:
	nsys profile --stats=true -t cuda,nvtx sh examples/ds_pretrain_gpt2.sh

server:
	python -m http.server
