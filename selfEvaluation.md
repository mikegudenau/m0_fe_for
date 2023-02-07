# Self Evaluation

1. How confident do you feel in your understanding and fluency with the `for` statement?
I feel great coming out to the "for" assignment. I've been working on for loops in my spare time outside of Turing so that has definitely helped. I feel that I was able to complete this assignment in a reasonable amount of time. 


2. This was a much more advanced concept than anything you've done in Mod 0, and the exercises required you to push yourself to apply other background knowledge or learn things outside of the curriculum - how did that feel? Did you have productive struggle? Unproductive struggle?

I had fun time completing the code challenges. Some of the questions had me stumped initially. Especially the code challenge "Print out only names that begin with 'P'". I went through 6 iterations of trying to get the problem solved and then I persevered. I felt my brain using my logical reasoning skills. I found myself google searching during this assignment more than any other. It's fun to flex the google searching skills. To me, this assignment felt like a productive struggle because I didn't give up and I was getting closer to the solutions each time I came at it from a different angle. 


3. What do you still need to practice or learn? How will you do that? Do you need to adjust your calendar in order to do that?

I still need to practice using array methods and printing out specific directions. I really enjoyed the challange of having to combine methods to print something specific such as "Print out only names that begin with 'P'". This meant I had to use a 'includes' method and a 'chatAt()' method. Unless there is an easier way...


4. What questions do you still have? How will you get the answers you need?

I don't really have a question...just more of an observation. 

I noticed when using '.length' to find the the length of values in an array, it doesn't use the 0th index. But when using a for loop, the 0th index is used. This is good to remember when using '.length' in a for loop to know what '.length' actually represents. 

For example:
``` javascript 
var fruits = ['apples', 'oranges', 'bananas'];
console.log(fruits.length); // this outputs 3
```

``` javascript 
for (var i = 0; i < fruits.length; i++) {
    console.log(i);
}
```

this prints:
// 0
// 1
// 2

