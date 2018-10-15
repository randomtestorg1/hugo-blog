---
title: "Golang"
date: 2018-09-26T09:35:07+05:30
draft: true
---

## `net/http` package

`HandleFunc` method: creates a `Handler` type on `DefaultServeMux` handler, mapping the path passed to the function.
`Handler` type:
`DefaultServeMux` handler:

`ListenAndServe`
`ListenAndServeTLS`

## `log` package

`log.Fatal`: convenience function equivalent to calling `fmt.Print()` followed by `os.Exit(1)`

## `encoding/json` package
Standard library encoding and decoding JSON to and from Go types is both fast and easy

`Marshal-Unmarshal` functions:
`Encoder-Decoder` types: greater control when reading and writing streams of JSON data

# Thoughts

## Hello Server
1. Build and run the server
4. How to log beautiful requests as they come in?
5. Difference between HTTP server and TLS?
6. When is the `handler` argument in `ListenAndServe` supposed to be non-nil?
7. Example of when the `ListenAndServe` returns an error
8. Notice the exit status of `1`
9. Run this server in Docker
10. Show the use of Network Tab in the browser
1. Use time.Sleep and show metrics.


## JSON
1. Commenting
2. Exported/Unexported Types
3. `panic` and `recover`
4. Need for struct tags in JSON
    1. Convert fields to lower case and show no HTTP response
    2. Define struct tags 

### ASIDE
1. Built-in support for UTF-8 in Go