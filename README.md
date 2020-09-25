### graphql GraphQL
---
https://github.com/tmc/graphql




```go
// internal/parsar/parser_test.go
package parser_test

import (
  "testing"
  
  "github.com/tmc/graphql/internal/parser"
)

var shouldParse = []string{
  ``,
  ``
}

func TestSuccessfulParses(t *testing.T) {
  for i, in := range shouldParse {
    d, err := parser.Parse("parser_test.go", []byte{in})
    if err != nil {
      t.Errorf("case %d: %v\n%s", i+1, err, in)
    }
    _ = d
  }
}
```

```
```

```
```


