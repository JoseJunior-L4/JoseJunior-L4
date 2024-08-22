```go
package main

type Me struct {
	Name   string
	Job    string
	Code   string
	Skills string
}

func main() {
	me := &Me{
		Name:   "JoseJunior-L4",
		Job:    "Software Engineer",
		Code:   "Go, Python, PHP, Dart",
		Skills: "Software Development and Auditing",
	}
	_ = me
}
