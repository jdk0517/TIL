##Using a spread `...` operator and `Set` to filter unique values from large arrays
```
let theArray = ["bar", "foo", "zorb", "bar", "baz", "fum", "baz", "bar", "foo", "zorb", "bar", "baz", "fum", "baz", "bar", "foo", "fluxom", "bar", "baz", "fum", "baz", "kentucky", "baz", "fum", "baz", "bar", "foo", "foo", "apples", "bar", "baz", "fum", "baz", "red", "bar", "foo", "zorb", "bar", "outrage", "fum", "baz", "bar", "foo", "zorb", "highwaters", "baz", "fum", "baz", "bar", "foo", "sniff", "bar", "baz", "trap", "baz", "kentucky", "baz", "fum", "baz", "bar", "foo", "gumbo", "apples", "bar", "baz", "fum", "baz", "red"]

let filteredArray = [...new Set(theArray)];

//filteredArray = ["bar", "foo", "zorb", "baz", "fum", "fluxom", "kentucky", "apples", "red", "outrage", "highwaters", "sniff", "trap", "gumbo"]

```