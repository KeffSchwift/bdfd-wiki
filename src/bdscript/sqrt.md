# $sqrt
Returns the square root of the input number

## Syntax
```
$sqrt[number]
```

### Arguments
- `number` `(Type: Integer/Float || Flag: Required)`: The input number.

## Example
```
$nomention
$onlyIf[$isNumber[$message]==true;❌ Enter a valid number!]
$sqrt[$message]
```

``` discord yaml
- user_id: 844691636754841600
  username: KeffSchwift
  color: "#E67E22"
  content: |
    !sqrt 81
- user_id: 1256493471372546080
  username: WikiBot
  color: "#378afa"
  bot: true
  verified: false
  content: |
    The square root of **81** is: 9
```
