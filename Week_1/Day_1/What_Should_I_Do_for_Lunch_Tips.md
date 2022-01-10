### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
\

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      console.log(
        `You are hungry and have ${availableTime} minutes, pick something up and eat in back in the Lab, where you can get to know your fellow classmates.`
      );
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log(
        ` You are hungry and have ${availableTime} minutes, you deserve a break and could try a place in Gastown.`
      );
    } else if (availableTime > 30) {
      console.log(
        `You are hungry and have ${availableTime} minutes for lunch, remember how much time we have to spare.`
      );
    }
  } else {
    console.log(
      `Im not hungry and have ${availableTime} minutes, get back to work.`
    );
  }
```
