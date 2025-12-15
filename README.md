<p align="right">
⭐ &nbsp;&nbsp;<strong>the project to show your appreciation.</strong> :arrow_upper_right:
</p>

<p align="right">
<a href="http://godoc.org/github.com/romance-dev/https-cert-go"><img src="http://godoc.org/github.com/romance-dev/https-cert-go?status.svg" /></a>
<a href="https://goreportcard.com/report/github.com/romance-dev/https-cert-go"><img src="https://goreportcard.com/badge/github.com/romance-dev/https-cert-go" /></a>
</p>

# Self Signed HTTPS Certificate Generation

Quickly generate TLS certificates in Go.

## Example

```go
import https "github.com/romance-dev/https-cert-go"

pub, priv, _ := https.GenerateKeys(https.GenerateOptions{Host: "thecucumber.app"})

```

[![Go Playground](https://img.shields.io/badge/Go-Playground-5593c7.svg?labelColor=41c3f3&style=for-the-badge)](https://go.dev/play/p/kUxlD0RsXyx)


### Extra Notes

Just remember to change the server's url from http to https. Also configure your http client code/application to allow self-signed certificates, otherwise they will spit out an error.


Other useful packages
------------

- [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Statistics and data manipulation
- [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go
- [electron-alert](https://github.com/rocketlaunchr/electron-alert) - SweetAlert2 for Electron Applications
- [igo](https://github.com/rocketlaunchr/igo) - A Go transpiler with cool new syntax such as fordefer (defer for for-loops)
- [mysql-go](https://github.com/rocketlaunchr/mysql-go) - Properly cancel slow MySQL queries
- [react](https://github.com/rocketlaunchr/react) - Build front end applications using Go
- [remember-go](https://github.com/rocketlaunchr/remember-go) - Cache slow database queries
