# What's the deal with "if else" statements?

We can think of IF statements as conditional code: code that only runs if a certain condition is `true`.

```p5
var number = 3;

if(number === 3){
	ellipse(10,10,50,50);
}
```

The if statement checks to see if number is equal to 3
otherwise, nothing happens
the conditional statement is TRUE in this case, so a smiley face is printed

ELSE lets us determine what happens if the condition is NOT true, aka FALSE