The following code comes from an exercise on git-conventions for pushing work to a remote branch. 

The lesson begins by cloning a remote repo. Here's a quick overview of the git workflow.

```command-line
git clone <remotereponame> <localversionname>
cd <localversionname>
git co -b <banchname>
[
	begin work in whichever editor you like
]
git add <filename(s)>
git commit -m "your-commit-msg"
git push origin <branchname>
```

This is a block of code we have editted and commented on.

```javascript
// Mary Rose's JavaScript Homework

  

// 1. Write an if/else statement

var APPLE_QUANTITY = 8;

  

if (APPLE_QUANTITY < 5){

console.log("You have fewer than 5 apples.");

} else {

console.log("You have 5 or more apples. Hurrah!");

}

  

// 2. Changed provided for-loop

for(i=0; i < APPLE_QUANTITY; i ++){

console.log("Very cool, I am a loop")

}

  

// 3. Write a function

var sayHello = function(){

console.log("Hello!")

}

  

// 4. Create an object

var mary = {

name: "Mary Rose",

codeNinja: true,

country: "UK"

}

//This is a comment in javascript  

// Added and changed some things
```

#code #computer-science #user-guide #git #javascript 