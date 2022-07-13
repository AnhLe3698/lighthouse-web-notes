### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  console.log("I don't know what to do!");
  if (hungry === false) {
    console.log("You are not hungry, please wait until you are hungry");
  } else if (availableTime < 20 && availableTime > 0) {
    console.log("Please grab a snack or something you already have at home");
  } else if (availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break! Please cook a tasty meal.");
  } else if (availableTime > 30) {
    console.log("This is an intese program, please reconsider the length of your break!");
  }
};
```