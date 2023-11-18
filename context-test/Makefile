.DEFAULT_GOAL := build

.PHONY: build run-ok run-cancel

build:
	go build

run-ok: build
	./go-primitives-context-test false

run-cancel: build
	./go-primitives-context-test true