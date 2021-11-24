# bibtex ![Build Status](https://github.com/Jblew/bibtex/actions/workflows/test.yml/badge.svg) [![Go Reference](https://pkg.go.dev/badge/github.com/Jblew/bibtex.svg)](https://pkg.go.dev/github.com/Jblew/bibtex)

## `nickng/bibtex` is a bibtex parser and library for Go.

The bibtex format is not standardised, this parser follows the descriptions found
[here](http://maverick.inria.fr/~Xavier.Decoret/resources/xdkbibtex/bibtex_summary.html).
Please file any issues with a minimal working example.

To get:

    go get -u github.com/Jblew/bibtex/...

This will also install `prettybib`, a bibtex pretty printer.
To parse and pretty print a bibtex file, for example:

    cd $GOPATH/src/github.com/Jblew/bibtex
    prettybib -in example/simple.bib
