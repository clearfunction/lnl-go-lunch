# Golang lunch notes

## Housekeeping
* Set a `$GOPATH`!  I use ~/gopath
  * **ALWAYS** use `$GOPATH/src/github.com/clearfunction/project-name` directory naming style!
    * I know you don't want to, but it's gonna be a huge pain and waste a lot of your time because most of the go tooling assumes you did it this way.
    * Sorry about your `~/Projects` and `c:\dev` folders!  I guess you could use symlinks or write your own `gocd project-name` scripts if you really wanna.
* Add `$GOPATH/bin` to your `$PATH`. This way any binaries you `go install` are available.

## Supplmental tools:
* github.com/fatih/vim-go
* goimports
