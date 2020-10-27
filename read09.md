# About functional programming
- is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## Pure functions
- Just because your program contains functions does not necessarily mean that you are doing functional programming. Functional programming distinguishes between pure and impure functions.

![](https://devopedia.org/images/article/21/5929.1491735653.png)

## Pure Functions in JavaScript
Let’s look at some of the pure functions (methods) given by JavaScript.

1. Filter : As the name suggests, this filters the array.
EX:
```
array.filter(condition);
```

2. map: maps each item of array to a function and creates a new array based on the return values of the function calls.
EX:
```
array.map(mapper)
```

3. Reduce : reduce reduces the array to a single value.
EX:
```
array.reduce(reducer);
```

4. Concat : concat adds new items to an existing array to create a new array. It’s different from push() in the sense that push() mutates data, which makes it impure.
EX:
```
[1, 2].concat([3, 4])  
// [1, 2, 3, 4]
```

5. Object.assign : Object.assign copies values from the provided object to a new object. Since functional programming is predicated on immutable data, we use it to make new objects based on existing objects.
EX:
```
const obj = {a : 2};  
const newObj = Object.assign({}, obj);  
newObj.a = 3;  
obj.a;  
// 2
```

## Functions as first-class entities
## The idea of functions as first-class entities is that functions are also treated as values and used as data.
- Functions as first-class entities can:
1) refer to it from constants and variables
2) pass it as a parameter to other functions
3) return it as result from other functions



## Higher-order functions:
- takes one or more functions as arguments. or returns a function as its result.

-------------------------------------------------
# Refactoring javascript



![](https://miro.medium.com/fit/c/1838/551/1*1fGgnh-krPxk4o5343J5Vg.png)

### Scenario 1
- We're an URL-shortening website, like TinyURL. We accept a long URL and return a short URL that forwards visitors to the long URL. We have two functions.
```
/ Unrefactored code by Omar Zain

const URLstore = [];

function makeShort(URL) {
  const rndName = Math.random().toString(36).substring(2);
  URLstore.push({[rndName]: URL});
  return rndName;
}

function getLong(shortURL) {
  for (let i = 0; i < URLstore.length; i++) {
    if (URLstore[i].hasOwnProperty(shortURL) !== false) {
      return URLstore[i][shortURL];
    }
  }
}
```

### Scenario 2
- We’re a social media website where user URLs are generated randomly. Instead of random gibberish, we’re going to use the friendly-words package that the Glitch team works on. They use this to generate the random names for your recently created projects!
```
// Unrefactored code by Omar Zain

const friendlyWords = require('friendly-words');

function randomPredicate() {
  const choice = Math.floor(Math.random() * friendlyWords.predicates.length);
  return friendlyWords.predicates[choice];
}

function randomObject() {
  const choice = Math.floor(Math.random() * friendlyWords.objects.length);
  return friendlyWords.objects[choice];
}

async function createUser(email) {
  const user = { email: email };
  user.url = randomPredicate() + randomObject() + randomObject();
  await db.insert(user, 'Users')
  sendWelcomeEmail(user);
}
```
## Strategies
- Here are some straightforward to implement methods that can lead to easier to read code. There are no absolutes when it comes to clean code — there's always an edge case!
Return early from functions:
```
// By Omar Zain
function showProfile(user) {
  if (user.authenticated === true) {
    // ..
  }
}

// Refactor into ->

function showProfile(user) {
  // People often inline such checks
  if (user.authenticated === false) { return; }
  // Stay at the function indentation level, plus less brackets
}
```
Note:
-----
- It’s important to get your code right the first time because in many businesses there isn’t much value in refactoring.

HAVE A Nice READ :)

-----------------------------------------------------


[Table Of Content](https://github.com/omarXzain/301-reading-notes)


