#Challenge: Local Scope and Functions

Variables which are declared within a function, as well as the function parameters have local scope. That means, they are only visible within that function.

Here is a function `myTest` with a local variable called `loc`.

```js
function myTest() {
  var loc = "foo";
  console.log(loc);
}
myTest(); // "foo"
console.log(loc); // "undefined"
```

`loc` is not defined outside of the function.