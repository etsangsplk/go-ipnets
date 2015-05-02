# go-ipnets

[![GoDoc](https://godoc.org/github.com/stanvit/go-ipnets?status.svg)](https://godoc.org/github.com/stanvit/go-ipnets)

ipnets library provides a slice of [net.IPNet](https://golang.org/pkg/net/#IPNet) instances,
allows to parse comma-separated list of individual IP addresses and networks in CIDR format
using [flag](https://golang.org/pkg/flag/) package fulfilling
[flag.Value](https://golang.org/pkg/flag/#Value) interface. It is possible to check if
individual [net.IP](https://golang.org/pkg/net/#IP) matches any of the networks in the slice.
