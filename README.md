# grfron parser

parser for grfron object storage language for the game greyhack

## usage

```lua
string = "{
    people: [
        {
            name: John
            age: 25
        }
        {
            name: Jane
            age: 24
        }
        { name: Jack; age: 26 }
        [{name: jack is a fucker; age: 99}]
    ]
    this is an int: 55
    this is not an int: ""55""
    this is a double: 55.5
    another array: [ omg; another; array ]
}"
import_code("grfon.src")
print(parse(string))
```

## todo

- [x] deserialization
- [ ] seralization
