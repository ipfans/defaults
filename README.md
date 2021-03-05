# defaults

Fill default values of struct.

## How to Use

```go
type V struct {
	I int `defaults:"1"`
}

func main() {
	var v V
	defaults.Default(&v)
}
```