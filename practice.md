# What did I learn in Lecture 1?

I learned about template literals and how either `const stuff = "I'm gonna insert a " + value + " here";` or ``const stuff = `I'm gonna insert a ${value} here`;`` can be used.
This is a lot easier to type out, similar to python f-strings, and supports multi-line strings.

# Code snippet input
```javascript
const kaelyn = {name: "kaelyn", age: "19"}
console.log(kaelyn)
const json = JSON.stringify(kaelyn)
console.long(json)
```

# Code snippet output
```
{ name: 'kaelyn', age: '19' }
{"name":"kaelyn","age":"19"}
```

### bullet point list of the JavaScript types
* number
* string
* boolean
* object
* array
* function
