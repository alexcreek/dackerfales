image := 192.168.1.10:4000/rutorrent:auto-$(shell git rev-parse --short HEAD)

build:
	docker build -t ${image} .
	docker push ${image}
