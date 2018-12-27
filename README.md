<br/>
<div align="center">

A curated list of awesome golang Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

_List inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing._

Supported by: [GuardRails.io](https://github.com/apps/guardrails)

</div>
<br/>

# Tools

## Web Framework Hardening

- [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
- [gorilla/csrf](https://github.com/gorilla/csrf) - Provides Cross Site Request Forgery (CSRF) prevention middleware for Go web applications & services.
- [gorilla/securecookie](https://github.com/gorilla/securecookie) - Encodes and decodes authenticated and optionally encrypted cookie values for Go web applications.
- [secure](https://github.com/unrolled/secure) -  Secure is an HTTP middleware for Go that facilitates most of your security needs for web applications.
- [unindexed](https://github.com/jordan-wright/unindexed) - A drop-in replacement for `http.Dir` which disables directory indexing.

## Libraries

- [paseto](https://github.com/o1egl/paseto) - Platform-Agnostic Security Tokens implementation in GO (Golang)
- [hsts](https://github.com/StalkR/hsts) - Go HTTP Strict Transport Security library

## Static Code Analysis

- [safesql](https://github.com/stripe/safesql) - Static analysis tool for Golang that protects against SQL injections. It does not seem to be actively maintained at the moment.
- [gosec](https://github.com/securego/gosec) - Inspects source code for security problems by scanning the Go AST and matching it with a set of rules. Comes bundled in a Docker container [securego/gosec](https://hub.docker.com/r/securego/gosec)
- [gometalinter](https://github.com/alecthomas/gometalinter) - Concurrently runs most of the existing go linters and normalizes their output.

## Vulnerabilities and Security Advisories

- [golang-announce](https://groups.google.com/forum/#!forum/golang-announce) - The golang release mailing list. Language-specific security issues are announced here.
- [snyk Vulnerability DB](https://snyk.io/vuln?type=golang) - Commercial but free listing of known vulnerabilities in libraries.
- [Common Vulnerabilities and Exposures](https://www.cvedetails.com/vulnerability-list/vendor_id-14185/Golang.html) - Vulnerabilities that were assigned a CVE. Covers the language and packages.
- [National Vulnerability Database](https://nvd.nist.gov/vuln/search/results?form_type=Basic&results_type=overview&query=golang&search_type=all) - Golang known vulnerabilities in the National Vulnerability Database.

## Private Key Infrastructure

- [CloudFlare SSL](https://github.com/cloudflare/cfssl) - CFSSL is CloudFlare's PKI/TLS swiss army knife. It is both a command line tool and an HTTP API server for signing, verifying, and bundling TLS certificates.

# Educational

## Hacking Playground

- [govwa](https://github.com/0c34/govwa) - A vulnerable golang application including the most common vulnerabilities found in web applications today
- [Lambhack](https://github.com/wickett/lambhack) - A very vulnerable serverless application in AWS Lambda

## Articles, Guides & Talks

- [gosea](https://github.com/komand/gosea) - Go Secure Example Application (GOSEA)
- [Go - Secure Coding Practices](https://www.owasp.org/images/2/2b/Owasp-171123063052.pdf) by OWASP - [PDF] Talk given by Sulhaedir at the OWASP Jakarta meetup.
- [Go - Secure Coding Practices](https://checkmarx.gitbooks.io/go-scp/) by Checkmarx - Go programming language secure coding practices guide
- [Memory Security in golang](https://cryptolosophy.org/memory-security-go/) - Handling data securely in memory.
- [A Go Programmer's Guide to Secure Connections](https://www.youtube.com/watch?v=kxKLYDLzuHA) - [Video] GopherCon 2018, Liz Rice
- [golang-tls](https://github.com/denji/golang-tls) - Simple Golang HTTPS/TLS Examples.
- [Hacking with Go](https://github.com/parsiya/Hacking-with-Go) - Hacking with Go for security professionals.

# Companies

- [GuardRails](https://www.guardrails.io) - A GitHub App that gives you instant security feedback in your Pull Requests.
- [Snyk](https://snyk.io) - A developer-first solution that automates finding & fixing known vulnerabilities in your dependencies.

# Other

## Reporting Bugs

- [Go Security Policy](https://golang.org/security)

# Contributing

Found an awesome project, package, article, or another type of resources related to golang Security? Send me a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

---

say _hi_ on [Twitter](https://twitter.com/pxlpnk)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
