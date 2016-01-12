all: help

help:
	@echo ""
	@echo "-- Help Menu"
	@echo ""
	@echo "   1. make build            - build all cogrob images"
	@echo "   1. make clean            - remove all cogrob images"
	@echo ""

build:
	@docker build --tag=videosegment:dev dev/.
	@docker build --tag=videosegment:dep dep/.
	@docker build --tag=videosegment:seg seg/.

clean:
	@docker rmi -f videosegment:dev
	@docker rmi -f videosegment:dep
	@docker rmi -f videosegment:seg
