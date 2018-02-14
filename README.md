byteswriter
===========

This Go package implements a `io.Writer` that wraps a `[]byte`.
It's like `bytes.Reader`, but then a Writer.

```golang
b := make([]byte, 20)
w := byteswriter.NewWriter(b)
// use io.Writer w
```

See [godoc documentation](https://godoc.org/github.com/bwesterb/byteswriter)
