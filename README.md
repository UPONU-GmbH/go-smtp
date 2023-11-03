# go-smtp

[![Go Reference](https://pkg.go.dev/badge/github.com/emersion/go-smtp.svg)](https://pkg.go.dev/github.com/emersion/go-smtp)
[![builds.sr.ht status](https://builds.sr.ht/~emersion/go-smtp/commits.svg)](https://builds.sr.ht/~emersion/go-smtp/commits?)

An ESMTP client and server library written in Go.

## Features

* ESMTP client & server implementing [RFC 5321](https://tools.ietf.org/html/rfc5321)
* Support for SMTP [AUTH](https://tools.ietf.org/html/rfc4954) and [PIPELINING](https://tools.ietf.org/html/rfc2920)
* UTF-8 support for subject and message
* [LMTP](https://tools.ietf.org/html/rfc2033) support

## Relationship with net/smtp

The Go standard library provides a SMTP client implementation in `net/smtp`.
However `net/smtp` is frozen: it's not getting any new features. go-smtp
provides a server implementation and a number of client improvements.

## Licence

MIT
