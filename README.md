# godexter

```golang
type Info struct {
	Username string
	Age  uint8
	ProgrammingLanguages [2]string
}

func NewInfo() *Info {
	return &Info{
		Username: "dexter",
		Age: 16,
		ProgrammingLanguages: [2]string{"Go", "JavaScript"},
	}
}

```
