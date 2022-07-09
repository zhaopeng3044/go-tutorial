# Go-tutorial
A tutorial repository for Go langurage.

# Develop environment set up

## Go Environment Variable

- GOROOT: the path your Go SDK installed. If your Go SDK was installed default path(/user/local/bin/go) ignore this variable.

- GOPATH: Find go customer libs. Go libs installed by command `go get` will be at GOPATH folder.

## local go develop project folder structure

Go local project workspace location should append to GOPATH. So Go SDK could find out you code.
local path should exist three fold:
- src: all go project should be add to this folder.
- pgk: middle compiled files.
- bin: final compiled and builded binary file.