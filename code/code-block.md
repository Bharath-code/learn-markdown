# Code Block

This is represented by 
```Javascript
let i = 0
```
Triple backtick

### Example
```Javascript
   function loop(n){
    for (let index = 0; index < n; index++) {
        console.log(index)
        
    }
    for(let j=0 ; j <n;j++){
        console.log(j)
    }
}
console.log(loop(5))
```

```Go
    package main

import "fmt"

func main() {

    m := make(map[string]int)

    m["k1"] = 7
    m["k2"] = 13

    fmt.Println("map:", m)

    v1 := m["k1"]
    fmt.Println("v1:", v1)

    v3 := m["k3"]
    fmt.Println("v3:", v3)

    fmt.Println("len:", len(m))

    delete(m, "k2")
    fmt.Println("map:", m)

    _, prs := m["k2"]
    fmt.Println("prs:", prs)

    n := map[string]int{"foo": 1, "bar": 2}
    fmt.Println("map:", n)
}
```