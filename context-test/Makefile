.DEFAULT_GOAL := build

.PHONY: build run-ok run-cancel

build:
	go build

run-ok: build
	./go-learning-context-test false

run-cancel: build
	./go-learning-context-test true