BRANCH  ?= $(shell git rev-parse --abbrev-ref HEAD)
ifeq ($(BRANCH),master)
        BRANCH=latest
endif
IMG=myimage:$(BRANCH)

all: build

build:
        docker build -t $(IMG)
