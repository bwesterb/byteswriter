byteswriter
===========

This Go package implements a `io.Writer` that wraps a `[]byte`.
It's like `bytes.Reader`, but then a Writer.

```
b := make([]byte, 20)
w := byteswriter.NewWriter(b)
// use io.Writer w
```
