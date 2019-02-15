BRANCH = ${CIRCLE_BRANCH}
ifeq ($(BRANCH),master)
        BRANCH=latest
endif
IMG=myimage:$(BRANCH)

all: build

build:
        docker build -t $(IMG)
