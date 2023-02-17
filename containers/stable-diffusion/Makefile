version ?= v0.1

all: build push

build:
	docker build --tag GJSissons/stable-diffusion-nf:${version} .
	
push:
	docker push GJSissons/stable-diffusion-nf:${version}
