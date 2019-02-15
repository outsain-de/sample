BRANCH=${CIRCLE_BRANCH}

IMG=myimage:$(BRANCH)

all: build

build:
        docker build -t $(IMG) .
